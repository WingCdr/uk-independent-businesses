# Independent businesses in the UK, by town

How many independent businesses there are in each UK postal town, and what kinds: shops and salons, food and drink, trades, professional firms, and places to stay. Plus how many have no website at all.

From [Independents Only](https://independentsonly.com), the UK search engine that lists only independent businesses. No chains, no franchises, and nobody can pay to rank higher.

**Coverage:** Hertfordshire and Cambridgeshire (November 2026). More counties are added from January 2027, and this dataset is updated as they go live.

## The data

[`data/independents-by-town.csv`](data/independents-by-town.csv). One row per postal town with five or more independent businesses.

| Column | Meaning |
|---|---|
| `town`, `county` | Postal town, and the county it's listed under |
| `independent_businesses` | All independent businesses listed in and around the town |
| `shops_and_salons` | Shops, hairdressers, beauty salons and similar |
| `food_and_drink` | Cafés, pubs, restaurants and takeaways |
| `trades_and_home` | Builders, plumbers, electricians, gardeners and other trades |
| `professional_services` | Accountants, solicitors, agencies and other firms |
| `travel_and_stays` | B&Bs, guest houses and other places to stay |
| `no_website` | How many have no website of their own |
| `page` | The town's page on Independents Only |

## Method

- **Counted by postal town.** Nearby villages that share a town's postal address are included in its total.
- **Independents only.** Every business is checked against a list of more than 21,000 chain and franchise brands. Chains are left out, and so are directories and lead-generation sites.
- **Where the listings come from.** Open business data, checked and updated weekly, plus listings that owners add or claim themselves.
- **Live figures.** The latest numbers are always at [independentsonly.com/figures](https://independentsonly.com/figures). This copy is updated when they change materially.

## Licence and credit

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Free to use, share and adapt, including commercially, with credit:

> Figures: Independents Only (independentsonly.com/figures)

Journalists: for a quote, a particular town or a figure not shown here, email hello@independentsonly.com.
