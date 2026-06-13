# Bandsintown (bandsintown)

Bandsintown is a concert discovery platform that connects fans with live music events through a REST API for accessing artist event listings, venue information, and fan notification management. The platform serves as the largest database of upcoming concert listings and concert tickets, enabling artists, developers, and partners to display tour dates, retrieve artist metadata, filter events by date range, and drive fan engagement through RSVP and notification tracking.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/bandsintown/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=bandsintown-api-evangelist&utm_content=repo

---

## Tags

concerts, live music, events, artists, venues, music discovery, tour dates, tickets, fan notifications, entertainment

---

## APIs

### Bandsintown Public API

The Bandsintown Public API (v3) provides REST endpoints for retrieving artist information and event listings. Developers can look up artists by name, Bandsintown ID, or Facebook page ID, retrieve upcoming, past, or date-range-filtered event listings, and access venue details.

- **Documentation:** https://help.artists.bandsintown.com/en/articles/9186477-api-documentation
- **Getting Started:** https://help.artists.bandsintown.com/en/articles/7053475-what-is-the-bandsintown-api
- **Base URL:** https://rest.bandsintown.com
- **OpenAPI Spec:** https://app.swaggerhub.com/apis/Bandsintown/PublicAPI/3.0.0
- **Postman:** https://www.postman.com/bandsintowndev/bandsintown-api/overview

---

## Plans, Rate Limits, and FinOps

### Plans

| Plan | Cost | Scope |
|------|------|-------|
| Artist API Key | Free | Single artist via Bandsintown for Artists account |
| Partnership Access | Custom | Multi-artist, negotiated terms via API@bandsintown.com |

Full plans detail: [plans/bandsintown-plans-pricing.yml](plans/bandsintown-plans-pricing.yml)

### Rate Limits

Specific numeric rate limits are not publicly published. The API is described as having generous limits for typical artist website use cases. Rate limits for partnership integrations are defined in custom agreements.

Full rate limits detail: [rate-limits/bandsintown-rate-limits.yml](rate-limits/bandsintown-rate-limits.yml)

### FinOps

Billing model: free for artist-scoped access; partnership agreements have custom terms. No published per-request pricing. Primary cost consideration is partnership agreement terms negotiated with Bandsintown directly.

Full FinOps detail: [finops/bandsintown-finops.yml](finops/bandsintown-finops.yml)

---

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-06-13

---

## Common Properties

| Property | URL |
|----------|-----|
| Website | https://www.bandsintown.com/ |
| Documentation | https://help.artists.bandsintown.com/en/articles/9186477-api-documentation |
| Getting Started | https://help.artists.bandsintown.com/en/articles/7053475-what-is-the-bandsintown-api |
| GitHub Organization | https://github.com/bandsintown |
| SDKs (Ruby) | https://github.com/bandsintown/api-gem |
| Status Page | https://status.bandsintown.com/ |
| Terms of Service | https://corp.bandsintown.com/terms |
| Privacy Policy | https://corp.bandsintown.com/privacy |
| Blog | https://artists.bandsintown.com/blog |
| Contact | API@bandsintown.com |

---

## Maintainers

- **Kin Lane** — kin@apievangelist.com
