# Bitmovin (bitmovin)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Bitmovin is an Emmy Award-winning video streaming infrastructure platform providing REST APIs for cloud video encoding (VOD and live), adaptive bitrate packaging (HLS, MPEG-DASH), DRM integration, an HTML5 player, and analytics for quality-of-experience observability. Its encoding pipeline covers 800+ endpoints across Java, JavaScript, Python, Go, PHP, and C# open-source SDKs.

APIs.json: https://raw.githubusercontent.com/api-evangelist/bitmovin/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=bitmovin-api-evangelist&utm_content=repo

## Tags

Video, Encoding, Streaming, Live Streaming, VOD, Adaptive Bitrate, HLS, DASH, DRM, Player, Analytics, Media, Cloud

## APIs

| Name | Description |
|------|-------------|
| Bitmovin Encoding API | REST API for cloud-based VOD and live video encoding supporting H.264, HEVC, VP9, AV1, adaptive bitrate packaging, and DRM |
| Bitmovin Player API | APIs for embedding and configuring the Bitmovin HTML5 player, managing licenses, and collecting playback events |
| Bitmovin Analytics API | REST API for querying quality-of-experience metrics including buffering, startup time, and error rates |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/bitmovin-plans-pricing.yml](plans/bitmovin-plans-pricing.yml) |
| Rate Limits | [rate-limits/bitmovin-rate-limits.yml](rate-limits/bitmovin-rate-limits.yml) |
| FinOps | [finops/bitmovin-finops.yml](finops/bitmovin-finops.yml) |

**Pricing summary:** Pay-as-you-go with no fixed monthly cost. Free tier includes 2,000 VOD encoding minutes, 360 live encoding minutes, 10,000 player impressions, and 100,000 analytics impressions per month. VOD encoding starts at $0.02/min (SD baseline) with resolution and codec multipliers. Enterprise custom plans available via sales.

**Rate limits:** 300 requests/min default; endpoint-specific limits range from 3/min (password reset) to 20,000/min (encoding sub-resources). HTTP 429 returned on breach.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://bitmovin.com |
| Documentation | https://developer.bitmovin.com/ |
| GitHub | https://github.com/bitmovin |
| LinkedIn | https://www.linkedin.com/company/bitmovin |
| Blog | https://bitmovin.com/blog/ |
| Pricing | https://bitmovin.com/pricing |
| Status Page | https://status.bitmovin.com/ |
| X | https://x.com/bitmovin |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
