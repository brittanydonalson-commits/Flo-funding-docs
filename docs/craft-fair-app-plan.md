# Online Craft Fair — Marketplace Platform

## The Concept
A multi-vendor marketplace where independent sellers (not businesses) can list and sell handmade items, art, crafts, etc. Seller-friendly policies, fair fees, community feel.

## It's NOT:
- A single artist shop (that's just a store)
- A reseller platform (like OfferUp getting overrun with businesses)

## It IS:
- Like a digital version of a local craft fair
- Etsy, but without the horror stories and corporate policies
- A space for real people selling what they make

## Key Roles
1. **You (the platform owner)** — Run the marketplace, set rules, handle onboarding
2. **Sellers** — Independent creators listing their items
3. **Buyers** — People browsing and purchasing

## Core Features Needed
1. **Seller onboarding** — Sign up, create profile, verify they're a real person (not a business)
2. **Seller dashboard** — Add/edit/delete listings, see orders, track earnings
3. **Product listings** — Photo, title, description, price, shipping info
4. **Buyer experience** — Browse, search, filter, add to cart, checkout
5. **Checkout / Payments** — Stripe Connect is the standard here (takes a cut, handles payouts to sellers)
6. **Messaging** — Buyer-seller chat
7. **Seller verification** — This is your differentiator: real humans only, no resellers

## Technical Path
**No-code is HARDER here** — building a multi-vendor marketplace with payments, seller dashboards, and checkout is complex. Glide can do basic versions but payments are tricky.

**Better options:**
- **Bubble + Stripe Connect** — Can handle multi-vendor, payments, dashboards. $50-130/month. 1-3 months to build.
- **WordPress + WooCommerce + Dokan plugin** — There's a "Dokan" plugin that turns WooCommerce into a multi-vendor marketplace. $150-300 one-time for plugin. More control, still manageable.
- **Hire a developer** — $10k-30k+ for something decent

## Estimated Costs
| Option | Cost | Time |
|--------|------|------|
| Bubble | $50-130/month | 1-3 months |
| WooCommerce + Dokan | ~$300 one-time + hosting | 2-4 weeks |
| Hire out | $10k-30k+ | 2-4 months |

## The Challenge
Multi-vendor marketplaces are harder to build than single shops because:
- You need payments to split between platform and sellers
- Need separate seller dashboards
- Need trust/verification systems
- Need to attract both sellers AND buyers (chicken and egg problem)

## Your Competitive Edge
- **No businesses allowed** — Verification keeps it real
- **Seller-friendly policies** — No random account holds
- **Lower fees** — 5-10% instead of Etsy's 15%+
- **Community feel** — Personal, not corporate

---

## Next Steps
1. Validate the idea — Would sellers actually join? (Talk to a few people)
2. Decide on tech path
3. Build the MVP
4. Get a few sellers (friends, local artists)
5. Get buyers