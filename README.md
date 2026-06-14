# PeerTube

PeerTube is a free, decentralized, and federated video hosting platform developed by Framasoft as an open-source alternative to centralized video services like YouTube. Built on ActivityPub, PeerTube instances federate with one another to form a global network of over 1,600 platforms hosting more than one million videos. Anyone can self-host a PeerTube instance and join the federated network without fees or vendor lock-in.

## API

The PeerTube REST API provides access to all platform functionality through an OpenAPI 3.0 specification. Authentication uses OAuth 2.0 with three role levels (Administrator, Moderator, User). The API covers:

- Video upload, management, captions, chapters, and transcoding
- Live streaming
- Channel and playlist management
- User accounts and subscriptions
- Search and discovery across federated instances
- Content moderation (abuse reports, blocklists, auto-tags)
- Instance configuration and plugin management
- Federation and redundancy controls
- Distributed transcoding via remote runner jobs
- RSS/Atom syndication feeds

**Base URL:** `https://{instance}/api/v1`

**Authentication:** OAuth 2.0 Bearer Token

**Rate Limits:** 50 req/10s (general), 15 req/5min (login), 2 req/5min (registration)

## Links

- **Website:** https://joinpeertube.org/
- **Documentation:** https://docs.joinpeertube.org/
- **API Reference:** https://docs.joinpeertube.org/api-rest-reference.html
- **Getting Started:** https://docs.joinpeertube.org/api/rest-getting-started
- **OpenAPI Spec:** https://raw.githubusercontent.com/Chocobozzz/PeerTube/develop/support/doc/api/openapi.yaml
- **GitHub:** https://github.com/Chocobozzz/PeerTube
- **Forum:** https://framacolibri.org/c/peertube

## Maintainer

**API Evangelist** — https://apievangelist.com
