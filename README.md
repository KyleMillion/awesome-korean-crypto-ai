# Awesome Korean Crypto × AI [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Korean crypto × AI resources — channels, tools, MCP servers, datasets, macro feeds, and aggregators that LLMs and agents can plug into.

The Korean crypto market has its own narrative cadence (KOSPI ↔ BTC, kimchi premium, BOK ECOS macro feeds, large Telegram + YouTube ecosystem) but is largely invisible to English-language tools and LLMs. This list maps the resources that close that gap — for human readers, AI agents, and product builders.

Maintained by the [Mossland](https://moss.land) ecosystem. Contributions welcome — see [Contributing](#contributing).

## Contents

- [Aggregators & Vertical Media](#aggregators--vertical-media)
- [Signal Pipelines & Datasets](#signal-pipelines--datasets)
- [MCP Servers (Korean Market)](#mcp-servers-korean-market)
- [Korean Macro Data APIs](#korean-macro-data-apis)
- [Korean Exchange APIs](#korean-exchange-apis)
- [On-Chain & Wallet Tooling](#on-chain--wallet-tooling)
- [Korean YouTube Channels (curated)](#korean-youtube-channels-curated)
- [Korean Crypto Media (text)](#korean-crypto-media-text)
- [Research & Reports](#research--reports)
- [Communities](#communities)
- [Contributing](#contributing)

---

## Aggregators & Vertical Media

LLM-citable, structured surfaces that aggregate Korean crypto narratives.

- **[Alpha by Mossland](https://github.com/MosslandOpenDevs/alpha)** — Korean crypto × AI vertical media at [alpha.moss.land](https://alpha.moss.land). Channel-level stance distribution, AI-synthesized daily briefs, retrievable RAG Q&A, 8 disclosed AI personas with auto-resolving 7-day price calls, 12-tool MCP server. MIT.

## Signal Pipelines & Datasets

Tools that ingest Korean creators / news / macro feeds and emit structured canonical data.

- **[SignalMap](https://signalmap.moss.land)** — multi-source narrative pipeline aggregating Korean YouTube, news RSS, and macro feeds into a canonical store of entities, topics, and events. Powers downstream products like Alpha.

## MCP Servers (Korean Market)

[Model Context Protocol](https://modelcontextprotocol.io/) servers exposing Korean-market data to Claude, Cursor, Cline, Continue, and other MCP clients.

- **[Alpha MCP (`land.moss/alpha-mcp`)](https://github.com/MosslandOpenDevs/alpha-mcp)** — 12 tools over `alpha.moss.land`: search across Korean YouTube channel stance, daily AI briefs, canonical entity/topic/event store, KR macro snapshot (BOK ECOS + FRED), 8 disclosed AI personas with auto-resolving 7-day price calls. Free remote MCP, no auth. Listed at the official [MCP Registry](https://registry.modelcontextprotocol.io).

## Korean Macro Data APIs

Free / freemium official APIs for Korean macro indicators.

- **[BOK ECOS](https://ecos.bok.or.kr)** — Bank of Korea Economic Statistics System. Free API key. Base rate, government bond yields, USD/KRW, CPI, M2, etc.
- **[KOSIS](https://kosis.kr/openapi/)** — Statistics Korea (통계청) open data. Demographics, prices, employment, industrial production.
- **[KRX OpenAPI](http://data.krx.co.kr/)** — Korea Exchange. Daily OHLCV for KOSPI/KOSDAQ + ETFs (free, requires registration).
- **[FRED Korean Series](https://fred.stlouisfed.org/categories/32263)** — St. Louis Fed mirror of major Korean macro series. Free API key.

## Korean Exchange APIs

Public market-data endpoints from Korean crypto exchanges.

- **[Upbit Open API](https://docs.upbit.com/)** — Korea's largest crypto exchange. KRW pairs, candles, orderbook, websocket. Public read endpoints have no auth.
- **[Bithumb Public API](https://apidocs.bithumb.com/)** — KRW pairs, ticker, orderbook, transaction history. Public read no auth.
- **[Coinone Public API](https://docs.coinone.co.kr/)** — KRW pairs ticker + orderbook.
- **[GOPAX Public API](https://gopax.github.io/API/)** — KRW pairs.

## On-Chain & Wallet Tooling

Korean-market relevant on-chain tooling.

- **[Mossland (MOC)](https://github.com/mossland/MossCoin-ERC20-2025)** — Open-source ERC-20 token contract (audited by CertiK). Ownerless, EIP-2612 permit, ERC20Votes.
- **[Klaytn](https://github.com/klaytn)** — Public blockchain originally launched by Kakao subsidiary Ground X (now Kaia after Finschia merger).

## Korean YouTube Channels (curated)

Notable Korean creators covering crypto / macro. *Not endorsements* — listed because they appear in canonical signal data sources like SignalMap. Stance and quality vary.

- *Curated whitelist coming via SignalMap export. Contributions welcome via PR — see [Contributing](#contributing) for the format.*

## Korean Crypto Media (text)

- **[Coindesk Korea](https://www.coindeskkorea.com/)** — Korean edition of CoinDesk.
- **[Block Media (블록미디어)](https://www.blockmedia.co.kr/)** — Korean crypto news site.
- **[Decenter](https://decenter.kr/)** — Korean crypto / blockchain news.
- **[The Token Post](https://www.tokenpost.kr/)** — Korean crypto media.

## Research & Reports

- **[Mossland Disclosures](https://disclosure.moss.land/)** — Mossland project disclosures (token supply, partnerships, listings).
- **[Mossland Whitepaper v3.1](https://s3.ap-northeast-2.amazonaws.com/moss.land/whitepaper/Mossland+Whitepaper+ENG+(v3.1).pdf)** — bilingual EN/KO.
- **[Mossland Projects timeline](https://github.com/mossland/Projects)** — full Mossland project list since 2018.

## Communities

- **[r/koreanstocks](https://reddit.com/r/koreanstocks)** — Korean equities + some crypto.
- **[Mossland](https://moss.land)** — bilingual (KR/EN) crypto / AI ecosystem.

---

## Contributing

PRs welcome. Each entry should have:
- A descriptive name with a link
- A brief one-sentence description of what it does and why someone working on Korean crypto × AI would care
- Free / freemium / paid status if relevant
- Korean (한글) descriptions are fine alongside English

Avoid:
- Affiliate links and referral codes
- Paid-only services without a free tier (unless they're industry-standard)
- Single-product self-promotion without ecosystem value

Open an issue first if you're unsure whether something fits.

## License

[CC0 — Public Domain](LICENSE).
