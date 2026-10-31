# PeerTube

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PeerTube is a free, decentralized, and federated video hosting platform developed by Framasoft as an open-source alternative to centralized video services like YouTube. It enables anyone to self-host a video platform that federates with other instances via ActivityPub, forming a global network of over 1,600 platforms hosting more than one million videos. The REST API supports video uploading and management, channel and playlist operations, live streaming, search and discovery across federated nodes, content moderation, plugin management, and distributed transcoding via remote runner jobs.

**Areas:** Video · Decentralized · Federation · Open Source · ActivityPub · Self-Hosted · Streaming

## PeerTube on APIs.io

Everything profiled for PeerTube is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/peertube/](https://apis.io/providers/peertube/)** — or go straight to one of the APIs or properties below.

### APIs (54)

- [PeerTube Abuses API](https://apis.io/apis/peertube/peertube-abuses-api/) — Abuses deal with reports of local or remote videos/comments/accounts alike.
- [PeerTube Account Blocklist API](https://apis.io/apis/peertube/peertube-account-blocklist-api/) — The Account Blocklist API from PeerTube — 5 operation(s) for account blocklist.
- [PeerTube Accounts API](https://apis.io/apis/peertube/peertube-accounts-api/) — Accounts encompass remote accounts discovered across the federation, and correspond to the main Actor, along with video channels a user can create, which…
- [PeerTube Automatic Tags API](https://apis.io/apis/peertube/peertube-automatic-tags-api/) — Automatic tags set on objects (like comments or videos) by specific rules (external link, watched words, etc.)
- [PeerTube Channels Sync API](https://apis.io/apis/peertube/peertube-channels-sync-api/) — Operations dealing with synchronizing PeerTube user's channel with channels of other platforms
- [PeerTube Client Config API](https://apis.io/apis/peertube/peertube-client-config-api/) — Configuration of the web client.
- [PeerTube Config API](https://apis.io/apis/peertube/peertube-config-api/) — Each server exposes public information regarding supported videos and options.
- [PeerTube Contact API](https://apis.io/apis/peertube/peertube-contact-api/) — Send a message to the instance administrators.
- [PeerTube Debug API](https://apis.io/apis/peertube/peertube-debug-api/) — Administrative debug endpoints.
- [PeerTube Homepage API](https://apis.io/apis/peertube/peertube-homepage-api/) — Get and update the custom homepage
- [PeerTube Instance Follows API](https://apis.io/apis/peertube/peertube-instance-follows-api/) — Managing servers which the instance interacts with is crucial to the concept of federation in PeerTube and external video indexation. The PeerTube server…
- [PeerTube Instance Redundancy API](https://apis.io/apis/peertube/peertube-instance-redundancy-api/) — Redundancy is part of the inter-server solidarity that PeerTube fosters. Manage the list of instances you wish to help by seeding their videos according to…
- [PeerTube Job API](https://apis.io/apis/peertube/peertube-job-api/) — Jobs are long-running tasks enqueued and processed by the instance itself. No additional worker registration is currently available.
- [PeerTube Live Videos API](https://apis.io/apis/peertube/peertube-live-videos-api/) — The Live Videos API from PeerTube — 4 operation(s) for live videos.
- [PeerTube Logs API](https://apis.io/apis/peertube/peertube-logs-api/) — Operations dealing with client, server and audit logs.
- [PeerTube My History API](https://apis.io/apis/peertube/peertube-my-history-api/) — Operations related to your watch history.
- [PeerTube My Notifications API](https://apis.io/apis/peertube/peertube-my-notifications-api/) — Notifications following new videos, follows or reports. They allow you to keep track of the interactions and overall important information that concerns…
- [PeerTube My Subscriptions API](https://apis.io/apis/peertube/peertube-my-subscriptions-api/) — Operations related to your subscriptions to video channels, their new videos, and how to keep up to date with their latest publications!
- [PeerTube My User API](https://apis.io/apis/peertube/peertube-my-user-api/) — Operations related to your own User, when logged-in.
- [PeerTube Ownership Change API](https://apis.io/apis/peertube/peertube-ownership-change-api/) — The Ownership Change API from PeerTube — 12 operation(s) for ownership change.
- [PeerTube Player Settings API](https://apis.io/apis/peertube/peertube-player-settings-api/) — Operations dealing with video player settings for videos and channels.
- [PeerTube Plugins API](https://apis.io/apis/peertube/peertube-plugins-api/) — Managing plugins installed from a local path or from NPM, or search for new ones.
- [PeerTube Register API](https://apis.io/apis/peertube/peertube-register-api/) — As a visitor, you can use this API to open an account (if registrations are open on that PeerTube instance). As an admin, you should use the dedicated [User…
- [PeerTube Runner Jobs API](https://apis.io/apis/peertube/peertube-runner-jobs-api/) — Manage runner jobs and runner-side job execution.
- [PeerTube Runner Registration Token API](https://apis.io/apis/peertube/peertube-runner-registration-token-api/) — Manage runner registration tokens.
- [PeerTube Runners API](https://apis.io/apis/peertube/peertube-runners-api/) — Register, list and remove remote runners.
- [PeerTube Search API](https://apis.io/apis/peertube/peertube-search-api/) — The search helps to find _videos_ or _channels_ from within the instance and beyond. Videos from other instances federated by the instance (that is,…
- [PeerTube Server Blocklist API](https://apis.io/apis/peertube/peertube-server-blocklist-api/) — The Server Blocklist API from PeerTube — 5 operation(s) for server blocklist.
- [PeerTube Session API](https://apis.io/apis/peertube/peertube-session-api/) — Sessions deal with access tokens over time. Only __one session token can currently be used at a time__.
- [PeerTube Static Video Files API](https://apis.io/apis/peertube/peertube-static-video-files-api/) — The Static Video Files API from PeerTube — 4 operation(s) for static video files.
- [PeerTube Stats API](https://apis.io/apis/peertube/peertube-stats-api/) — Statistics
- [PeerTube User Exports API](https://apis.io/apis/peertube/peertube-user-exports-api/) — To create an archive of user data.
- [PeerTube User Imports API](https://apis.io/apis/peertube/peertube-user-imports-api/) — To import an archive of user data.
- [PeerTube Users API](https://apis.io/apis/peertube/peertube-users-api/) — Using some features of PeerTube require authentication, for which User provide different levels of permission as well as associated user information. Each…
- [PeerTube Video API](https://apis.io/apis/peertube/peertube-video-api/) — Operations dealing with listing, uploading, fetching or modifying videos.
- [PeerTube Video Blocks API](https://apis.io/apis/peertube/peertube-video-blocks-api/) — Operations dealing with blocking videos (removing them from view and preventing interactions).
- [PeerTube Video Captions API](https://apis.io/apis/peertube/peertube-video-captions-api/) — Operations dealing with listing, adding and removing closed captions of a video.
- [PeerTube Video Channels API](https://apis.io/apis/peertube/peertube-video-channels-api/) — Operations dealing with the creation, modification and listing of videos within a channel.
- [PeerTube Video Chapters API](https://apis.io/apis/peertube/peertube-video-chapters-api/) — Operations dealing with managing chapters of a video.
- [PeerTube Video Comments API](https://apis.io/apis/peertube/peertube-video-comments-api/) — Operations dealing with comments to a video. Comments are organized in threads: adding a comment in response to the video starts a thread, adding a reply to…
- [PeerTube Video Download API](https://apis.io/apis/peertube/peertube-video-download-api/) — Download video files
- [PeerTube Video Embed Privacy API](https://apis.io/apis/peertube/peertube-video-embed-privacy-api/) — The Video Embed Privacy API from PeerTube — 2 operation(s) for video embed privacy.
- [PeerTube Video Feeds API](https://apis.io/apis/peertube/peertube-video-feeds-api/) — Server syndication feeds of videos
- [PeerTube Video Files API](https://apis.io/apis/peertube/peertube-video-files-api/) — Operations on video files
- [PeerTube Video Imports API](https://apis.io/apis/peertube/peertube-video-imports-api/) — Operations dealing with listing, adding and removing video imports.
- [PeerTube Video Mirroring API](https://apis.io/apis/peertube/peertube-video-mirroring-api/) — PeerTube instances can mirror videos from one another, and help distribute some videos. For importing videos as your own, refer to [video…
- [PeerTube Video Passwords API](https://apis.io/apis/peertube/peertube-video-passwords-api/) — Operations on video passwords.
- [PeerTube Video Playlists API](https://apis.io/apis/peertube/peertube-video-playlists-api/) — Operations dealing with playlists of videos. Playlists are bound to users and/or channels.
- [PeerTube Video Rates API](https://apis.io/apis/peertube/peertube-video-rates-api/) — Like/dislike a video.
- [PeerTube Video Stats API](https://apis.io/apis/peertube/peertube-video-stats-api/) — Video statistics
- [PeerTube Video Transcoding API](https://apis.io/apis/peertube/peertube-video-transcoding-api/) — Video transcoding related operations
- [PeerTube Video Upload API](https://apis.io/apis/peertube/peertube-video-upload-api/) — Operations dealing with adding video or audio. PeerTube supports two upload modes, and three import modes. ### Upload - [_legacy_](#operation/uploadLegacy),…
- [PeerTube Videos API](https://apis.io/apis/peertube/peertube-videos-api/) — The Videos API from PeerTube — 4 operation(s) for videos.
- [PeerTube Watched Words API](https://apis.io/apis/peertube/peertube-watched-words-api/) — Manage list of watched words to detect patterns on objects (like comments of videos)

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Peertube Agentic Access](https://apis.io/agentic-access/peertube/peertube-agentic-access/)

#### JSON Schema (171)

The data models the API reads and writes.

- [Abuse](https://apis.io/schemas/peertube/Abuse/)
- [AbuseMessage](https://apis.io/schemas/peertube/AbuseMessage/)
- [AbusePredefinedReasons](https://apis.io/schemas/peertube/AbusePredefinedReasons/)
- [AbuseStateConstant](https://apis.io/schemas/peertube/AbuseStateConstant/)
- [AbuseStateSet](https://apis.io/schemas/peertube/AbuseStateSet/)
- [Account](https://apis.io/schemas/peertube/Account/)
- [AccountBlock](https://apis.io/schemas/peertube/AccountBlock/)
- [AccountSummary](https://apis.io/schemas/peertube/AccountSummary/)
- [Actor](https://apis.io/schemas/peertube/Actor/)
- [ActorImage](https://apis.io/schemas/peertube/ActorImage/)
- [ActorInfo](https://apis.io/schemas/peertube/ActorInfo/)
- [AddUser](https://apis.io/schemas/peertube/AddUser/)
- [AddUserResponse](https://apis.io/schemas/peertube/AddUserResponse/)
- [AddVideoPasswords](https://apis.io/schemas/peertube/AddVideoPasswords/)
- [AutomaticTagAvailable](https://apis.io/schemas/peertube/AutomaticTagAvailable/)
- [BlockStatus](https://apis.io/schemas/peertube/BlockStatus/)
- [ChangeOwnership](https://apis.io/schemas/peertube/ChangeOwnership/)
- [ChangeOwnershipState](https://apis.io/schemas/peertube/ChangeOwnershipState/)
- [ChannelActivityListResponse](https://apis.io/schemas/peertube/ChannelActivityListResponse/)
- [CommentAutoTagPolicies](https://apis.io/schemas/peertube/CommentAutoTagPolicies/)
- [CommentThreadPostResponse](https://apis.io/schemas/peertube/CommentThreadPostResponse/)
- [CommentThreadResponse](https://apis.io/schemas/peertube/CommentThreadResponse/)
- [CustomHomepage](https://apis.io/schemas/peertube/CustomHomepage/)
- [FileRedundancyInformation](https://apis.io/schemas/peertube/FileRedundancyInformation/)
- [FileStorage](https://apis.io/schemas/peertube/FileStorage/)
- …and 146 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Peertube Context](https://apis.io/jsonld/peertube/peertube/)

#### Examples (290)

Example requests and responses.

- [Acceptregistration](https://apis.io/examples/peertube/acceptRegistration/)
- [Acceptvideochannelcollaborator](https://apis.io/examples/peertube/acceptVideoChannelCollaborator/)
- [Addlive](https://apis.io/examples/peertube/addLive/)
- [Addplaylist](https://apis.io/examples/peertube/addPlaylist/)
- [Addplugin](https://apis.io/examples/peertube/addPlugin/)
- [Adduser](https://apis.io/examples/peertube/addUser/)
- [Addvideoblock](https://apis.io/examples/peertube/addVideoBlock/)
- [Addvideocaption](https://apis.io/examples/peertube/addVideoCaption/)
- [Addvideochannel](https://apis.io/examples/peertube/addVideoChannel/)
- [Addvideochannelsync](https://apis.io/examples/peertube/addVideoChannelSync/)
- [Addvideopassword](https://apis.io/examples/peertube/addVideoPassword/)
- [Addvideoplaylistvideo](https://apis.io/examples/peertube/addVideoPlaylistVideo/)
- [Addview](https://apis.io/examples/peertube/addView/)
- [Blockaccount](https://apis.io/examples/peertube/blockAccount/)
- [Blockserver](https://apis.io/examples/peertube/blockServer/)
- [Confirmtwofactorrequest](https://apis.io/examples/peertube/confirmTwoFactorRequest/)
- [Contactadministrator](https://apis.io/examples/peertube/contactAdministrator/)
- [Createvideotranscoding](https://apis.io/examples/peertube/createVideoTranscoding/)
- [Delcustomconfig](https://apis.io/examples/peertube/delCustomConfig/)
- [Delmirroredvideo](https://apis.io/examples/peertube/delMirroredVideo/)
- [Deluser](https://apis.io/examples/peertube/delUser/)
- [Delvideo](https://apis.io/examples/peertube/delVideo/)
- [Delvideoblock](https://apis.io/examples/peertube/delVideoBlock/)
- [Delvideocaption](https://apis.io/examples/peertube/delVideoCaption/)
- [Delvideochannel](https://apis.io/examples/peertube/delVideoChannel/)
- …and 265 more published on APIs.io

#### Collections (54)

Postman and Open Collection request collections.

- [PeerTube Abuses API](https://apis.io/collections/peertube/open-peertube-abuses-api/)
- [PeerTube Abuses Account Blocklist API](https://apis.io/collections/peertube/open-peertube-account-blocklist-api/)
- [PeerTube Abuses Accounts API](https://apis.io/collections/peertube/open-peertube-accounts-api/)
- [PeerTube Abuses Automatic Tags API](https://apis.io/collections/peertube/open-peertube-automatic-tags-api/)
- [PeerTube Abuses Channels Sync API](https://apis.io/collections/peertube/open-peertube-channels-sync-api/)
- [PeerTube Abuses Client Config API](https://apis.io/collections/peertube/open-peertube-client-config-api/)
- [PeerTube Abuses Config API](https://apis.io/collections/peertube/open-peertube-config-api/)
- [PeerTube Abuses Contact API](https://apis.io/collections/peertube/open-peertube-contact-api/)
- [PeerTube Abuses Debug API](https://apis.io/collections/peertube/open-peertube-debug-api/)
- [PeerTube Abuses Homepage API](https://apis.io/collections/peertube/open-peertube-homepage-api/)
- [PeerTube Abuses Instance Follows API](https://apis.io/collections/peertube/open-peertube-instance-follows-api/)
- [PeerTube Abuses Instance Redundancy API](https://apis.io/collections/peertube/open-peertube-instance-redundancy-api/)
- [PeerTube Abuses Job API](https://apis.io/collections/peertube/open-peertube-job-api/)
- [PeerTube Abuses Live Videos API](https://apis.io/collections/peertube/open-peertube-live-videos-api/)
- [PeerTube Abuses Logs API](https://apis.io/collections/peertube/open-peertube-logs-api/)
- [PeerTube Abuses My History API](https://apis.io/collections/peertube/open-peertube-my-history-api/)
- [PeerTube Abuses My Notifications API](https://apis.io/collections/peertube/open-peertube-my-notifications-api/)
- [PeerTube Abuses My Subscriptions API](https://apis.io/collections/peertube/open-peertube-my-subscriptions-api/)
- [PeerTube Abuses My User API](https://apis.io/collections/peertube/open-peertube-my-user-api/)
- [PeerTube Abuses Ownership Change API](https://apis.io/collections/peertube/open-peertube-ownership-change-api/)
- [PeerTube Abuses Player Settings API](https://apis.io/collections/peertube/open-peertube-player-settings-api/)
- [PeerTube Abuses Plugins API](https://apis.io/collections/peertube/open-peertube-plugins-api/)
- [PeerTube Abuses Register API](https://apis.io/collections/peertube/open-peertube-register-api/)
- [PeerTube Abuses Runner Jobs API](https://apis.io/collections/peertube/open-peertube-runner-jobs-api/)
- [PeerTube Abuses Runner Registration Token API](https://apis.io/collections/peertube/open-peertube-runner-registration-token-api/)
- …and 29 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [PeerTube — jsonschema rules](https://apis.io/rules/peertube/peertube-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Peertube Authentication](https://apis.io/security/peertube/peertube-authentication/)
- [Peertube Domain Security](https://apis.io/security/peertube/peertube-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Peertube Scopes](https://apis.io/scopes/peertube/peertube-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/peertube/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/peertube/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/peertube/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://joinpeertube.org/)
- [Documentation](https://docs.joinpeertube.org/)
- [Blog](https://framablog.org/)
- [Privacy policy](https://joinpeertube.org/privacy)

## API Evangelist rating

**Kin Score 30.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 52.5 |
| Contract governance | 9.8 |
| Operational transparency | 5.3 |
| Developer ergonomics | 35.7 |
| Access clarity | 5.3 |

**Agent readiness 32.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/peertube/](https://apis.io/providers/peertube/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for PeerTube: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/peertube/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
