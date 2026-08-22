# Major League Baseball (major-league-baseball)

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

Major League Baseball (MLB) is the professional baseball organization of the United States and Canada, operating the National League and American League with 30 teams. MLB Advanced Media (now part of MLB) provides public stats and game data through the MLB Stats API and the legacy MLB Data (lookup service) API, used by teams, broadcasters, analysts, and a wide community of developers building stats sites, fantasy applications, and analytical tools. MLB also exposes Statcast data through Baseball Savant. There is no general-purpose self-service developer portal with terms or signup; the APIs are widely consumed but are formally intended for partner use.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/major-league-baseball/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/major-league-baseball/refs/heads/main/apis.yml)

## Tags

- Analytics
- Baseball
- Entertainment
- Media
- Sports
- Sports Data
- Statistics

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-16

## APIs

### MLB Stats API

The MLB Stats API is the modern statistics and game-data service operated by Major League Baseball. It powers official scoreboards, gameday feeds, and downstream applications with endpoints for schedule, live game state, box scores, play-by-play, players, teams, standings, venues, divisions, and statistical splits. Documentation is hosted at docs.statsapi.mlb.com and access is gated through MLB's identity provider for partners.

- **Human URL:** [https://statsapi.mlb.com/](https://statsapi.mlb.com/)

#### Tags

- Game Data
- Live Scores
- REST API
- Sports Statistics

#### Properties

- [Documentation](https://docs.statsapi.mlb.com/)
- [API Reference](https://statsapi.mlb.com/)
- [Postman Collection](collections/major-league-baseball.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/major-league-baseball.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MLB Data Lookup Service API

The MLB Data Lookup Service is the legacy public data service exposing player search and details, hitting and pitching statistics, projections, team lists and rosters, game type information, date ranges, transactions, broadcast schedules, injury reports, and statistical leaderboards. The base endpoint is lookup-service-prod.mlb.com, with requests formatted as `/json/named.[endpoint].bam`.

- **Human URL:** [https://appac.github.io/mlb-data-api-docs/](https://appac.github.io/mlb-data-api-docs/)

#### Tags

- Legacy API
- Player Data
- Sports Statistics
- Team Data

#### Properties

- [Documentation](https://appac.github.io/mlb-data-api-docs/)
- [API Reference](http://lookup-service-prod.mlb.com/)
- [Postman Collection](collections/major-league-baseball.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/major-league-baseball.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MLB Statcast (Baseball Savant)

Baseball Savant is MLB's public Statcast platform, surfacing pitch- and tracking-level data captured by Statcast cameras and radar in every MLB ballpark. It exposes leaderboards, search tools, visualizations, and pitch-by-pitch detail for hitters, pitchers, and fielders, and is widely scraped or queried for analytical workflows.

- **Human URL:** [https://baseballsavant.mlb.com/](https://baseballsavant.mlb.com/)

#### Tags

- Pitch Tracking
- Sports Analytics
- Statcast

#### Properties

- [Documentation](https://baseballsavant.mlb.com/)
- [Leaderboard](https://baseballsavant.mlb.com/statcast_leaderboard)
- [Postman Collection](collections/major-league-baseball.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/major-league-baseball.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/major-league-baseball)
- [Website](https://www.mlb.com/)
- [News](https://www.mlb.com/news)
- [Stats](https://www.mlb.com/stats)
- [Standings](https://www.mlb.com/standings)
- [Schedule](https://www.mlb.com/schedule)
- [Teams](https://www.mlb.com/team)
- [Players](https://www.mlb.com/players)
- [Careers](https://www.mlb.com/careers)
- [Press](https://www.mlb.com/press)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
