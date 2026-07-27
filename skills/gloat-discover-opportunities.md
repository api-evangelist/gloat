---
name: Discover opportunities and recommendations
description: Search Gloat's talent graph and fetch personalized opportunity recommendations for an end user.
api: https://developer.gloat.com/reference/
operations: [search-by-keyword-1, opportunities-personalized-1, getuserskills-1]
source: https://developer.gloat.com/reference/
generated: '2026-07-19'
method: generated
---

# Discover opportunities and recommendations

Surface jobs, roles, projects, and people from Gloat's talent marketplace for an end user.

## 1. Authenticate
Talent Marketplace endpoints use an API key: send `X-Gloat-API-Key` plus `X-Tenant-ID`
headers (see `authentication/gloat-authentication.yml`).

## 2. Search
Use `search-by-keyword-1` to return short descriptions of entities (jobs, roles, people)
for a free-text query. **This call costs 5 credits** — budget accordingly.

## 3. Personalized recommendations
Use `opportunities-personalized-1` to get opportunity recommendations for a specific
end user. **Also 5 credits per call.**

## 4. Ground on the user's skills
Fetch the user's current skills with `getuserskills-1` to explain or re-rank results.

## Notes
- Metered endpoints are quota-limited in credits — cache results and avoid redundant calls.
- HTTPS only. See `conventions/gloat-conventions.yml` for quota details.
