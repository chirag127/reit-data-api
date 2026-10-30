# Indian REITs

> Listed REITs with NAV, distribution yield, and portfolio info

**Category:** finance · **Data:** SEBI/BSE public · **License:** CC-BY-4.0 · **Updates:** quarterly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/reits.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/reit-data/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/reit-data/data.json');
const data = await res.json();
```

## Data

- Source: SEBI/BSE public
- License: CC-BY-4.0
- Last updated: `2026-08-25T03:10:22.248Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/reit-data/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

CC-BY-4.0
