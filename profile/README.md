# DataSportsAPI

A real-time sports data API for developers: live scores, fixtures, lineups,
statistics and standings for **25 sports** in one JSON contract, keyed by stable
ids, over REST, a WebSocket and webhooks.

> **Live.** The API answers today. Get a free key (1,000 requests a day, no card)
> at [datasportsapi.com](https://datasportsapi.com/signup/).

| | |
|---|---|
| Website | [datasportsapi.com](https://datasportsapi.com) |
| Docs | [datasportsapi.com/docs](https://datasportsapi.com/docs/) |
| OpenAPI 3.1 | [openapi.json](https://datasportsapi.com/openapi.json) ([repo](https://github.com/datasportsapi/openapi)) |
| For AI assistants | [llms.txt](https://datasportsapi.com/llms.txt) |
| Live demo | [Matchboard](https://demo.datasportsapi.com), built on nothing but the API |
| Pricing | [Free to Enterprise](https://datasportsapi.com/pricing/) |
| Community | [Developer Discord](https://datasportsapi.com/discord): help, API feedback, showcase |

## Clients

| Language | Package | Status |
|---|---|---|
| TypeScript / JavaScript | [`datasportsapi` on npm](https://www.npmjs.com/package/datasportsapi) ([source](https://github.com/datasportsapi/datasportsapi-js)) | 0.0.x minimal client (one authenticated `get()`); the typed SDK comes with 0.1 |
| Python | [`datasportsapi` on PyPI](https://pypi.org/project/datasportsapi/) ([source](https://github.com/datasportsapi/datasportsapi-python)) | 0.0.x minimal client (one authenticated `get()`); the typed SDK comes with 0.1 |
| Go | [`github.com/datasportsapi/datasportsapi-go`](https://github.com/datasportsapi/datasportsapi-go) | in development, with 0.1 |
| Command line | `dsa` | in development, with 0.1 |

Until the typed SDKs land, any HTTP client works: send `Authorization: Bearer <your key>`
to `https://api.datasportsapi.com/v2/...` and read the `{ data, meta }` envelope.

## Contact

[hello@datasportsapi.com](mailto:hello@datasportsapi.com) · [Discord](https://datasportsapi.com/discord) · DataSportsAPI is a product of
[Noventra Software Ltd](https://noventra.dev), London (company 17373060).
