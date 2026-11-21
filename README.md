# What wins in Europe (2026): Facebook and Instagram ads by EU reach

Aggregate statistics on Facebook and Instagram ads shown in the European Union, built from the reach Meta publishes in its Ad Library under the EU Digital Services Act (DSA). Measured on 20 November 2026 by [EU Winners](https://euwinners.com).

Full study with charts and explanations: https://euwinners.com/research/what-wins-in-europe-2026

## What is in it

One CSV in long format: `table, row, column, value`. Each `table` is one breakdown:

| table | what it holds |
|---|---|
| totals | ads tracked, ads past 1,000 / 10,000 / 100,000 / 1,000,000 EU reach, advertisers, landing page domains, collection dates |
| country | per country: winning ads with reach there and summed reach |
| gender, age | summed reach by gender and age band |
| female_share_by_niche | share of reach seen by women, per niche |
| niche | winning ads per niche, share, median reach, ads past 100,000 reach |
| niche_7d_reach_gain | reach gained in 7 days per niche (active ads) |
| top_niches_by_country | top 2 niches per country by number of winning ads |
| format | ad format (video, dynamic creative, image, catalog, carousel) |
| days_running | median and 90th percentile days running by reach band |
| versions | share of ads with several versions, by reach band |
| store_platform | store platform behind winning ads (Shopify, WooCommerce and 12 more) |
| shopify_apps, shopify_themes | apps and themes on Shopify stores behind winning ads |
| call_to_action | call to action buttons |
| language | detected language of the ad text |

## Method

- **Source:** the public Meta Ad Library, read every day across all 27 EU countries and the UK. EU reach is Meta's own figure: the number of Meta accounts in the EU that saw the ad at least once (Meta notes it is estimated).
- **Winning set:** ads with at least 1,000 EU reach. 210,801 of 533,731 ads tracked on 20 November 2026.
- **Period:** collection started on 7 November 2026, so this is a first, two-week edition.
- **Niche:** automated classification; about 26% of winning ads were tagged on this date, so niche figures describe the tagged sample.
- **Store platform:** detected from the ad's landing page. "other" means a website that is not one of the 14 detected platforms; "unknown" means it could not be read.
- **Summed reach** counts the same person once per ad, so it measures distribution, not unique people.
- **Country** includes EU outermost regions and Åland, which Meta reports separately.

## License and citation

CC BY 4.0. Please cite:

> EU Winners, "What wins in Europe (2026)", 20 November 2026, https://euwinners.com/research/what-wins-in-europe-2026

EU Winners is not affiliated with Meta. Questions or corrections: support@euwinners.com
