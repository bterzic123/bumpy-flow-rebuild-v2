# Search to Gold · Bumpy (Growth Audit volume 2: Apple Ads keyword flows)

The five ranked ideas from volume 1, plus two versions of Bumpy's onboarding and Gold paywall side by side: one for people who searched "international dating" on the App Store, one for people who searched "make new friends".

**→ https://bterzic123.github.io/bumpy-flow-rebuild-v2/**

Public, no login. Opens on the Overview. Add `?open=proto` to land on the prototype, and `&step=paywall` (or `welcome`, `goal`, `profile`, `offer`) to open both phones on one screen.

Volume 1: https://bterzic123.github.io/bumpy-flow-rebuild/

## What is new in volume 2

- **Overview:** an Apple Ads card, a screen-by-keyword comparison, all 40 searches with share of voice and the flow each would land in, and what happens next.
- **Prototype:** two phones driven by one step bar. Tap through either phone and the other follows.
- **Keyword picker** beside each phone: "international dating", "global dating app", "international", "bumble", "eurodate" / "make new friends", "foreign", "interpals", "tandem".
- **Ideas panel:** for each step, what differs between the two searches, with a potential outcome for each.
- **30-second walkthrough** plays both flows at once. EN / ES / PT, Light / Dark. On a phone, a toggle switches between the two flows.

## What differs by keyword

| Screen | "international dating" | "make new friends" |
| :-- | :-- | :-- |
| Welcome | "Find your international soulmate", with 35M+ downloads and the 4.6 | "Meet new people & make friends", with chat translated automatically |
| Goal | "Find a relationship" picked, goals in Bumpy's order | "Chat and meet friends" moved to the top and picked |
| Profile preview | 70% looking for a serious relationship, 60% women | 100+ languages translated, people from 150+ countries |
| Paywall | 4.6 from 500k+ reviews, 35M+ downloads, 90% photo-verified | 100+ languages, 150+ countries, 4.6 |

## Grounding

Every price, rating and figure comes from Bumpy's own published material: the US and IE App Store listings, bumpy.app and Bumpy's in-app screens. Prices are the euro prices on the Gold paywall. Keyword data is from public observation of Bumpy's Apple Ads in the US (14 July – 13 October 2026, via AppMagic), not from the account. Impact ranges are Adapty's expected effect from tests across subscription apps, not measured lift for Bumpy.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. No build step and no dependencies.
