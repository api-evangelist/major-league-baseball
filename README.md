# Major League Baseball (major-league-baseball)

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
