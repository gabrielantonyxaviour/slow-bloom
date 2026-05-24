# Bloom With Bubble — Captured Guidelines

Source: https://contra.com/community/topic/bloomwithbubble/guidelines
Captured: 2026-05-21T23:48Z via agent-browser (Gabriel profile, session=slow-bloom-h0)
Status code: page state from Relay store (`isAuthenticated: false`, `userAccount: null`)

---

## Prize Pool ($10,000)
- 🥇 1st – $4,000
- 🥈 2nd – $2,500
- 🥉 3rd – $1,500
- 🤖 Best Use of Bubble AI – $1,000  ← Slow Bloom target
- ⭐️ Community Fave – $1,000  ← Slow Bloom target
- 💸 Bonus: Anthropic API credits per winner – $1,000

## Timeline
- Submissions opened: 2026-05-13T16:00Z
- **Submissions deadline: 2026-05-22T06:59Z (~7h from now)**
- Winners announced: 2026-05-27T16:00Z
- Number of winners: 5

## Categories (pick one)
- Business
- **Lifestyle** ← Slow Bloom locked here
- Communication

## Submission Requirements (4 items)
1. **Written explanation** — concept, problem, category, seasonal connection, monetization approach. If extending an existing web app, include link to original + how mobile version extends it.
2. **Demo video < 3 min** — walkthrough of app's core features (INCLUDING any in-app purchasing capabilities) + use case.
3. **Mobile app preview info** — provide mobile app's app name + branch version ID so judges can interact via BubbleGo.
4. **Must be built on Bubble's native mobile editor** — new builds + existing projects (if adding meaningful new features during challenge window) eligible.

## Evaluation Criteria (25 pts total, 5 each)
- **Functionality** — Does it work? Is the core use case fully built out?
- **Creativity** — Is the concept fresh and well-connected to the seasonal theme?
- **Design** — Is the mobile UX intuitive and polished?
- **Category Fit** — Does it clearly belong to Business / Lifestyle / Communication?
- **Monetization Strategy** — Is there a believable, well-integrated path to revenue?

## Bubble $100 Credit
- For NEW Bubble users only (not already on a paid plan)
- Distributed via automated challenge sign-up email
- Must submit at: https://bubble.io/perk-application
- Monthly plans only, one per org, expires 3 months after redemption
- Cannot combine with other Bubble coupons

## Bubble In-App Purchases (NEW)
> "Bubble now supports in-app purchases for mobile apps — meaning the app you build this week could be generating real revenue by the time submissions close."

Implication for Slow Bloom:
- Native IAP works in TestFlight builds, NOT in BubbleGo preview
- 7h window can't get us to TestFlight review
- Honest plan: configure Bubble IAP schema (proves we did the work) + Stripe web checkout fallback that actually works in BubbleGo + judge bypass code

## Judges (4)
- Jake Moss — Technical Success @ Bubble
- Calypso Leonard — Technical Success Manager / Team Lead @ Bubble
- Lucas Bennington — Founder & CEO @ Codi Technologies
- Ry Magno — Head of Product Design @ Contra

## Current State (Gabriel's account)
- `isAuthenticated: false` in agent-browser snapshot — Contra session not in Gabriel Chrome profile snapshot
- `visitorHasJoinedTopic: false` — Gabriel has NOT joined the topic
- `visitorHasAcceptedTopicGuidelines: false` — Gabriel has NOT accepted guidelines
- `canResubmitSubmission: false` — first submission is final, cannot resubmit
- `createTopLevelPostAccess: NONE` — must join topic first to enable submission

## Action items for Gabriel (manual clicks needed)
1. Verify which Chrome profile he's logged into Contra on (might be a different profile)
2. Click **Join Topic** on the guidelines page
3. Click **Accept Topic Guidelines**
4. Confirm Bubble account email (should be gabrielantony56@gmail.com)
5. Submit Bubble $100 perk form at https://bubble.io/perk-application (do this in parallel with build)
