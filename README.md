# Bitmovin (bitmovin)

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
