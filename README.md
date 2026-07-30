# KRY

KRY is a Swedish digital healthcare provider headquartered in Stockholm, operating internationally under the **Livi** brand. It delivers primary care through video and chat consultations with doctors, nurses, psychologists, physiotherapists, dietitians and midwives via its iOS and Android apps, and also runs physical primary care centres (vårdcentraler), child health clinics and midwifery clinics across Sweden.

**Brands and markets:** Kry — Sweden ([kry.se](https://www.kry.se)) and Norway ([kry.no](https://www.kry.no)); Livi — United Kingdom ([livi.co.uk](https://www.livi.co.uk)) and France ([livi.fr](https://www.livi.fr)).

Backed by: accel, creandum, eqt-ventures — https://www.kry.se

## API surface

**KRY publishes no public API.** As of 2026-07-19 there is no developer portal, API reference, OpenAPI or AsyncAPI document, SDK or package on any public registry, CLI, MCP server, or webhook catalog. Every `/.well-known/` discovery path returns 404 on all four brand hosts. Integrations with pharmacies, regions and partner providers run through private commercial agreements rather than a published developer program. This profile therefore captures company identity plus the legal and security surface — the API-artifact tiers of the enrichment pipeline are correctly skipped rather than fabricated.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Vulnerability disclosure | `security/kry-vulnerability-disclosure.yml` | searched |
| Domain security | `security/kry-domain-security.yml` | probed |
| Well-known probe | `well-known/kry-well-known.yml` | searched (none published) |
| llms.txt | `llms/kry-llms.txt` | generated |

KRY publishes a real [vulnerability disclosure policy](https://www.kry.se/vulnerability-disclosure/) — reports to `security@kry.se` with PGP accepted, acknowledgement within 2 business days and validation within 15. No reward-based bug bounty program is offered.
