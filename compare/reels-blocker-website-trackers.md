# Which Reels blocker websites track you? We checked 17

*Updated 8 November 2026*

**Of 17 Reels blocker websites we opened on 8 November 2026 from the Netherlands, without accepting any cookies, two loaded advertising trackers with no cookie banner at all: SocialLite (Meta, Google Ads and Snapchat pixels) and Opal (Meta Pixel, Google Ads audiences and DoubleClick).** Eleven more loaded third-party scripts, mostly analytics, four of them cookieless. stilltabs.com loaded no third-party requests at all: no trackers, no analytics, nothing.

## The results

| Website | What loaded before any choice | Cookie banner |
|---|---|---|
| **stilltabs.com** | **Nothing. Zero third-party requests** | **Not needed** |
| sociallite.app | **Advertising:** Meta Pixel (two pixel IDs), Google Ads conversion tag, Snapchat Pixel | None (switched off in its code since 7 October 2026) |
| opal.so | **Advertising:** Meta Pixel, Google Ads audiences, DoubleClick; plus Google Analytics, Google Optimize, Amplitude | None |
| socialalien.tech (LoomWeb) | Microsoft Clarity (session recording), Google Analytics via Firebase | None seen |
| freedom.to | Google Tag Manager, VWO (A/B testing), Wisepops (pop-ups), FirstPromoter (affiliate tracking) | None seen |
| getclearspace.com | Google Analytics, PostHog | Yes |
| getdull.app | Mixpanel | None seen |
| minulo.app | PostHog | None seen |
| fluidfriction.app | Google tag | None seen |
| appblock.app | Google Tag Manager | None seen |
| one-sec.app | Plausible (cookieless analytics) | Not needed |
| scroll-less.com, scrollguard.app, snowscroll.com | Cloudflare Web Analytics (cookieless) | Not needed |
| nope-app.com, sociano.app, undoomed.app | Nothing | Not needed |

*Chrome on macOS, Dutch IP address, a fresh visit to each homepage with no cookies accepted, 8 November 2026. We recorded every resource each page loaded from another domain. Sites change; this is what they did on that day.*

## SocialLite: "Nothing is tracked unless you accept"

**SocialLite's cookie banner tells visitors "Nothing is tracked unless you accept." Its own public consent script, sociallite.app/consent.js, shows the banner has been switched off since 7 October 2026, and the advertising trackers load for every visitor.** The note in the file reads: "BANNER TEMPORARILY DISABLED (operator decision, 2026-10-07): trackers load for all regions by default while the ad setup is adjusted."

- **What loads for everyone:** two Meta Pixel IDs, a Google Ads conversion tag and the Snapchat Pixel, each sending a page view.

- **When the banner is on:** the script records your page views and download clicks in your browser before you choose. If you then accept, it sends them to Meta and Google after the fact, including a custom Meta event called "RecoveredPageViews". If you choose "Essential only", the stored events are deleted.

- **Its homepage says** "No ads. No data sales. Ever." The pixels measure SocialLite's own advertising; they don't put ads in the app.

Under EU rules, websites need your consent before loading non-essential trackers such as advertising pixels. SocialLite's own banner code limits the consent flow to visitors in European time zones, and that flow is currently off.

## Opal: advertising trackers, no banner

**Opal's homepage loaded the Meta Pixel, Google Ads audience tags and DoubleClick on our visit from the Netherlands, along with Google Analytics, Google Optimize and Amplitude, and showed no cookie banner.** Opal's app also carries Apple's "Data Used to Track You" label.

## Why a website tells you something about the app

A company's website is the one place you can see its habits for yourself. If it sends your visit to Meta, Google and Snapchat before you've agreed to anything, that tells you how it thinks about your data. **StillTabs' website sends nothing anywhere**, and the app's App Store label is "Data Not Linked to You", with analytics off unless you turn them on.

**StillTabs does not track you.** Its App Store privacy label is "Data Not Linked to You", with nothing under "Data Used to Track You" or "Data Linked to You". Usage analytics are off by default and only start if you switch them on; even then they are tied to a random ID on your phone, never to your name or accounts, and never include what you watch, search or write. There are no ads and nothing is sold. Pages load straight from each platform: StillTabs runs no proxy, so it never sees your passwords, messages or what you browse. The [privacy policy](https://stilltabs.com/privacy) lists every event in full.

## Common questions

### Does the SocialLite website track you?

On 8 November 2026 it loaded the Meta Pixel, a Google Ads conversion tag and the Snapchat Pixel for a visitor from the Netherlands, with no cookie banner. Its consent script says the banner has been disabled since 7 October 2026.

### Does stilltabs.com use cookies or trackers?

No. stilltabs.com makes no third-party requests: no analytics, no advertising pixels, no cookie banner because there is nothing to consent to.

### Which Reels blocker websites load no trackers?

stilltabs.com, nope-app.com, sociano.app and undoomed.app loaded nothing from third parties. one sec, Scroll Less, ScrollGuard and snowscroll used cookieless analytics only.

## Related

- [What "free" Reels blockers and screen-time apps really cost](hidden-costs-of-reels-blockers.md)
- [The free SocialLite alternative: StillTabs](sociallite-alternative.md)
- [9 checks before you trust a Reels blocker or screen-time app](../guides/how-to-check-a-screen-time-app.md)

## Sources

Facts about other apps come from their App Store listings, help pages and websites, checked 8 November 2026.

1. SocialLite consent script (banner and tracker loading): https://sociallite.app/consent.js
2. SocialLite homepage: https://sociallite.app/
3. Opal homepage: https://opal.so/
4. Opal on the App Store: https://apps.apple.com/us/app/id1497465230
5. StillTabs on the App Store (price, privacy label): https://apps.apple.com/us/app/stilltabs-block-reels-shorts/id6761367777
6. StillTabs privacy policy: https://stilltabs.com/privacy

---

**[StillTabs on the App Store](https://apps.apple.com/app/id6761367777)** · free, no in-app purchases · [stilltabs.com](https://stilltabs.com)

*Written by the makers of StillTabs. Also published at https://stilltabs.com/compare/reels-blocker-website-trackers. Corrections welcome: [open an issue](https://github.com/albertmajor/stilltabs-app/issues).*
