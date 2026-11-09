# Data

- **[comparison.csv](comparison.csv)**: StillTabs and 19 other ways to block Reels and Shorts on iPhone, on 29 points, checked 8 November 2026. Every row lists the pages it was checked against in the `sources` column.
- **[stilltabs.json](stilltabs.json)**: StillTabs facts, the reasons it's different (each with a link to the evidence) and its limits.
- **[score-checks.json](score-checks.json)**: the 14 checks behind `pro_consumer_score`.

Written by the makers of StillTabs. "Not found" means we couldn't verify it from the app's own App Store page, website, privacy policy or terms, not that the answer is bad. If a cell is wrong, [open an issue](../../../issues) with a link and we'll fix it.

## Pro-consumer score

One point for each check an app passes. Checks we couldn't verify for an app are left out of its total, so missing information never counts against it (that's why some apps are scored out of 13). iPhone Screen Time is built into iOS and isn't scored.

| # | Check | Why it matters |
|---|---|---|
| 1 | Core blocking is free | The thing you installed it for shouldn't be behind a paywall |
| 2 | The strictest mode is free | People who need the most help shouldn't pay the most |
| 3 | No weekly plan | Weekly billing makes a big yearly price look small |
| 4 | No free trial that turns into a charge | Trials that convert are easy to forget |
| 5 | No ads | An attention app shouldn't sell your attention |
| 6 | No "Data Used to Track You" on the App Store | Your data isn't combined with other companies' data for advertising |
| 7 | Analytics off by default, or none | You choose whether anything is sent |
| 8 | No advertising trackers on its website | Visiting the site shouldn't report you to ad networks |
| 9 | Privacy policy in English | You can read what happens to your data |
| 10 | Its own terms of service | You know your rights and the rules |
| 11 | No arbitration clause or class-action waiver | You keep your right to go to court |
| 12 | No account required | Nothing to sign up for, nothing to leak |
| 13 | Updated on the App Store in the last 90 days | Instagram and YouTube change often; an app that isn't maintained stops working |
| 14 | Runs on iOS 16.0 or earlier | Older iPhones aren't left out |

## Scores, 8 November 2026

| App | Score |
|---|---|
| **StillTabs** | **14/14** |
| FeedOff | 13/14 |
| Slowth | 13/14 |
| Nope | 12/14 |
| UNDOOMED | 11/14 |
| Fluid Friction | 11/14 |
| one sec | 10/13 |
| snowscroll | 10/14 |
| ScrollGuard | 9/14 |
| minulo | 8/14 |
| LoomWeb | 8/14 |
| #blockit | 8/14 |
| ScreenZen | 8/14 |
| Dull | 7/14 |
| Sociano | 6/14 |
| Scroll Less | 6/14 |
| Stillfeed | 5/13 |
| Opal | 5/14 |
| SocialLite | 4/14 |

The score measures how an app treats you, not how well it blocks. StillTabs is the only app that passes all 14. Nope, which passes the first 12, hasn't been updated on the App Store since May 2026 and needs iOS 17; it also covers only Instagram and YouTube, is mainly a Safari extension and has no named Home Screen icons ([StillTabs vs Nope](../compare/stilltabs-vs-nope.md)). It is also the only app in the table that works as its own app with your DMs kept, Home Screen icons named after each platform (no Screen Time needed), every mode free and up to five accounts per platform.

## Columns

`app`, `how_it_works`, `platforms`, `keeps_dms`, `pro_consumer_score`, `account_required`, `core_blocking_free`, `strictest_mode_free`, `free_trial_converts`, `weekly_plan`, `cheapest_and_priciest_plan`, `ads_in_app`, `data_used_to_track_you`, `data_linked_to_you`, `in_app_analytics_default`, `website_ad_trackers`, `privacy_policy_in_english`, `own_terms_of_service`, `arbitration_or_class_waiver`, `refund_terms`, `permissions_needed`, `locks_or_changes_other_apps`, `home_screen_icons_named_after_platform`, `multiple_accounts_per_platform`, `last_app_store_update`, `min_ios`, `us_ratings`, `checked`, `sources`.

License: [CC BY 4.0](../LICENSE).
