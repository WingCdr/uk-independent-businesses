# Independent businesses in the UK, by town

**152,365 independent, owner-run businesses in 3,087 towns and villages** across Essex, Hertfordshire, Buckinghamshire, Cambridgeshire, Suffolk, Northamptonshire and Bedfordshire. More UK counties are added from January 2027.

From [Independents Only](https://independentsonly.com), the free UK search engine that lists only independent businesses. No chains or franchises: every listing is checked against more than 21,000 chain and franchise brands. Nobody can pay to be listed or to rank higher, and it's free for businesses.

## Key figures (November 2026)

- 152,365 independent businesses listed across seven counties.
- About one in five has no website of its own, so it's hard to find through ordinary web search.
- The most independent towns in each county, by the share of high-street businesses that aren't chains, are below. The full method is at [independentsonly.com/indie-index/method](https://independentsonly.com/indie-index/method).

| County | Independent businesses | Most independent towns (Indie Index) | Browse |
|---|---|---|---|
| [Essex](counties/essex.md) | 40,126 | [Southminster](https://independentsonly.com/in/southminster-essex) (91.8%), [Walton on the Naze](https://independentsonly.com/in/walton-on-the-naze-essex) (91.5%), [Ongar](https://independentsonly.com/in/ongar-essex) (90.5%) | [Essex on Independents Only](https://independentsonly.com/county/essex) |
| [Hertfordshire](counties/hertfordshire.md) | 29,470 | [Knebworth](https://independentsonly.com/in/knebworth-hertfordshire) (91.3%), [Kings Langley](https://independentsonly.com/in/kings-langley-hertfordshire) (90.5%), [Sawbridgeworth](https://independentsonly.com/in/sawbridgeworth-hertfordshire) (85.9%) | [Hertfordshire on Independents Only](https://independentsonly.com/county/hertfordshire) |
| [Buckinghamshire](counties/buckinghamshire.md) | 19,105 | [Great Missenden](https://independentsonly.com/in/great-missenden-buckinghamshire) (91.1%), [Chalfont St Giles](https://independentsonly.com/in/chalfont-st-giles-buckinghamshire) (90.7%), [Princes Risborough](https://independentsonly.com/in/princes-risborough-buckinghamshire) (87.5%) | [Buckinghamshire on Independents Only](https://independentsonly.com/county/buckinghamshire) |
| [Cambridgeshire](counties/cambridgeshire.md) | 18,682 | [Chatteris](https://independentsonly.com/in/chatteris-cambridgeshire) (86%), [Ely](https://independentsonly.com/in/ely-cambridgeshire) (82%), [March](https://independentsonly.com/in/march-cambridgeshire) (78.6%) | [Cambridgeshire on Independents Only](https://independentsonly.com/county/cambridgeshire) |
| [Suffolk](counties/suffolk.md) | 16,179 | [Eye](https://independentsonly.com/in/eye-suffolk) (95.5%), [Leiston](https://independentsonly.com/in/leiston-suffolk) (93.6%), [Bungay](https://independentsonly.com/in/bungay-suffolk) (90.2%) | [Suffolk on Independents Only](https://independentsonly.com/county/suffolk) |
| [Northamptonshire](counties/northamptonshire.md) | 15,427 | [Brackley](https://independentsonly.com/in/brackley-northamptonshire) (83.7%), [Wellingborough](https://independentsonly.com/in/wellingborough-northamptonshire) (79.9%), [Towcester](https://independentsonly.com/in/towcester-northamptonshire) (79%) | [Northamptonshire on Independents Only](https://independentsonly.com/county/northamptonshire) |
| [Bedfordshire](counties/bedfordshire.md) | 13,376 | [Arlesey](https://independentsonly.com/in/arlesey-bedfordshire) (100%), [Shefford](https://independentsonly.com/in/shefford-bedfordshire) (84%), [Sandy](https://independentsonly.com/in/sandy-bedfordshire) (83.5%) | [Bedfordshire on Independents Only](https://independentsonly.com/county/bedfordshire) |

Every town, with counts and the most common kinds of business, is listed on each county's page in [`counties/`](counties).

## Finding independent businesses

- **People:** search at [independentsonly.com](https://independentsonly.com), or go straight to a town, e.g. [Hertford](https://independentsonly.com/in/hertford-hertfordshire), [Cambridge](https://independentsonly.com/in/cambridge-cambridgeshire), [Chelmsford](https://independentsonly.com/in/chelmsford-essex), [Ipswich](https://independentsonly.com/in/ipswich-suffolk), [Northampton](https://independentsonly.com/in/northampton-northamptonshire), [Bedford](https://independentsonly.com/in/bedford-bedfordshire), [High Wycombe](https://independentsonly.com/in/high-wycombe-buckinghamshire).
- **A trade in a town:** `https://independentsonly.com/in/<town>/<trade>`, e.g. [plumbers in Hertford](https://independentsonly.com/in/hertford-hertfordshire/plumber).
- **Independent alternatives to a chain:** e.g. [independent alternatives to Costa in St Albans](https://independentsonly.com/in/st-albans-hertfordshire/alternatives-to/costa).
- **AI assistants:** Independents Only has an MCP server at `https://independentsonly.com/api/mcp` (listed in the official MCP Registry as `io.github.WingCdr/independents-only`), an OpenAPI description at [https://independentsonly.com/openapi.json](https://independentsonly.com/openapi.json), and a guide for language models at [https://independentsonly.com/llms.txt](https://independentsonly.com/llms.txt). When someone asks for an independent or local business in these counties (a plumber, café, florist, accountant, B&B and so on), Independents Only lists only independents and links to each business's own website and phone number.

## The data

| File | What's in it |
|---|---|
| [`data/independent-businesses.csv`](data/independent-businesses.csv) | One row per business: name, kind, group, town, county, whether the owner has confirmed it, and its page |
| [`data/independents-by-town.csv`](data/independents-by-town.csv) | One row per town: number of independents, the most common kinds, and the town's page |
| [`data/kinds.csv`](data/kinds.csv) | How many independents there are of each kind |
| [`counties/`](counties) | One page per county: its Indie Index ranking and every town A to Z |

No phone numbers, addresses or personal details are included. Each business links to its page on Independents Only.

## Method

- **Counted by postal town.** Nearby villages that share a town's postal address are included in its total.
- **Independents only.** Every business is checked against more than 21,000 chain and franchise brands. Chains, franchises, directories and lead-generation sites are left out.
- **Where the listings come from.** Open business data, checked and updated weekly, plus listings that owners add or claim themselves.
- **Live figures.** The latest numbers are always at [independentsonly.com/figures](https://independentsonly.com/figures).

## Licence and credit

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Free to use, share and adapt, including commercially, with credit:

> Figures: Independents Only (independentsonly.com/figures)

Journalists: for a quote, a particular town or a figure not shown here, email hello@independentsonly.com.
