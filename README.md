# Pushbullet (pushbullet)

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

Pushbullet is a cross-device messaging and notification service that lets users sync notifications, links, files, and SMS between phones, tablets, and computers. The Pushbullet HTTP API enables developers to send pushes, manage devices and contacts, transfer files, subscribe to channels, and stream real-time events over WebSockets. Authentication uses access tokens passed in the `Access-Token` header, with optional OAuth 2.0 for third-party applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pushbullet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pushbullet/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Notifications
- Messaging
- Push Notifications
- Device Sync
- SMS
- File Transfer

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Pushbullet HTTP API

REST API for sending and managing pushes, devices, chats, channels, subscriptions, and file uploads across the Pushbullet ecosystem. Authentication uses an access token from account settings supplied via the `Access-Token` header; OAuth 2.0 is available for third-party apps.

- **Human URL:** [https://docs.pushbullet.com](https://docs.pushbullet.com)
- **Base URL:** `https://api.pushbullet.com/v2`

#### Tags

- Notifications
- Push
- Devices
- Messaging
- SMS

#### Properties

- [Documentation](https://docs.pushbullet.com)
- [O Auth](https://docs.pushbullet.com/#oauth2)
- [Realtime  Event  Stream](https://docs.pushbullet.com/#realtime-event-stream)
- [Postman Collection](collections/pushbullet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pushbullet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pushbullet Realtime Event Stream

Secure WebSocket stream that delivers realtime events to a Pushbullet account, including periodic `nop` keep-alives, `tickle` notifications that signal changes to pushes or devices, and `push` ephemerals for mirrored notifications, dismissals, and universal clipboard.

- **Human URL:** [https://docs.pushbullet.com/#realtime-event-stream](https://docs.pushbullet.com/#realtime-event-stream)
- **Base URL:** `wss://stream.pushbullet.com/websocket`

#### Tags

- Realtime
- WebSockets
- Streaming
- Push Notifications
- Events

#### Properties

- [Documentation](https://docs.pushbullet.com/#realtime-event-stream)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/pushbullet/refs/heads/main/openapi/pushbullet-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/pushbullet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pushbullet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/pushbullet)
- [LinkedIn](https://www.linkedin.com/company/pushbullet)
- [Website](https://www.pushbullet.com)
- [Documentation](https://docs.pushbullet.com)
- [Sign Up](https://www.pushbullet.com/signup)
- [Pricing](https://www.pushbullet.com/pro)
- [Account  Settings](https://www.pushbullet.com/#settings/account)
- [Help](https://help.pushbullet.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
