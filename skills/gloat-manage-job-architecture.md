---
name: Manage the Skills Foundation job architecture
description: Build and maintain job families, job codes, and position titles with skills and proficiency levels in Gloat's Skills Foundation.
api: https://developer.gloat.com/reference/skills-foundation
operations: [create_job_family_api_v2__company__job_architecture_job_families_post, create_job_code_api_v2__company__job_architecture_job_codes_post, create_job_title_api_v2__company__job_architecture_job_titles_post, bulk_patch_job_code_skills_api_v2__company__job_architecture_job_codes_skills_bulk_patch, list_job_codes_api_v2__company__job_architecture_job_codes_get]
source: https://developer.gloat.com/reference/skills-foundation
generated: '2026-07-19'
method: generated
---

# Manage the Skills Foundation job architecture

Model your organization's job architecture — families, codes, and titles — and attach
skills with proficiency levels.

## 1. Authenticate
Use the client-credentials JWT flow (see `authentication/gloat-authentication.yml`).

## 2. Create the hierarchy top-down
1. Create a **job family** with `create_job_family_api_v2__company__job_architecture_job_families_post`.
2. Create **job codes** under it with `create_job_code_api_v2__company__job_architecture_job_codes_post`.
3. Create **position titles** with `create_job_title_api_v2__company__job_architecture_job_titles_post`.

Descriptions are managed on separate `/description` sub-resources — set them explicitly
after creating the entity.

## 3. Attach skills and proficiency levels
Use `bulk_patch_job_code_skills_api_v2__company__job_architecture_job_codes_skills_bulk_patch`
to set skills + levels across many job codes in one call. Levels must be valid for the
company configuration. The response is **207 Multi-Status** with per-job-code success
and error (`not_found` skills) detail.

## 4. Verify
List with `list_job_codes_api_v2__company__job_architecture_job_codes_get` (filterable by
`genaiImpact`). Deleting a job family **cascade-deletes** its job codes and titles.

## Notes
- Ontologies are ordered by preference; the first ontology wins on conflicts.
- See `data-model/gloat-data-model.yml` for the full entity graph.
