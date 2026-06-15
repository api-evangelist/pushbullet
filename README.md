# Pushbullet (pushbullet)

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
