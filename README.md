# football-match-report

A command-line tool that generates team-level post-match reports from football event data, built for analysts at clubs below the top tier.

## Status

Early development. The roadmap below describes the planned scope.

## Roadmap

- [ ] Data-source agnostic event schema with adapters
- [ ] StatsBomb open data adapter
- [ ] xG timeline and shot map
- [ ] Field tilt and PPDA
- [ ] Pass network with nodes labelled by position
- [ ] Set-piece section: corners and free kicks, delivery zones, shots, xG
- [ ] HTML report via CLI: `match-report <match_id>`
- [ ] PDF export

## Data

The first supported source is [StatsBomb open data](https://github.com/statsbomb/open-data), used under StatsBomb's terms with attribution. Further adapters can be added for other providers.

## Privacy

The tool works at team level only. Player names and player IDs are dropped at ingestion, so no personal data is processed or stored.

## Author

Moritz Philipp Haaf, [itzmore.dev](https://itzmore.dev)

## License

MIT, see LICENSE.

Data provided by StatsBomb.
