# Liveadvertise and LA Rank: Technical Reference for Announcing a Platform

A structured reference for developers and site owners who want to announce a platform on [Liveadvertise](https://liveadvertise.com/), verify ownership, install the tracking pixel and understand how LA Rank scores listings.

## Contents

1. Overview
2. Announce Platform submission spec
3. Ownership verification
4. Tracking pixel
5. LA Rank scoring signals
6. Discovery boards
7. Owner features
8. Fair-play rules
9. FAQ

## 1. Overview

| Field | Detail |
|---|---|
| Platform | Liveadvertise (LA Rank) |
| Purpose | Announce and discover new websites and platforms |
| Cost to list | Free; no subscription, no card on file |
| Ranking | LA Rank, driven mainly by real traffic |
| Recalculation | Weekly |
| Review | Human review before a listing goes live |

## 2. Announce Platform Submission Spec

| Field | Requirement |
|---|---|
| URL | Root-domain homepage only; subdomains and deep links rejected |
| Title | Up to 60 characters |
| Pitch | Up to 250 characters |
| Category | One of the categories below |
| Banner | Up to 2 MB; 1200 x 600 suggested |

### Categories

| Category |
|---|
| Traffic Exchanges |
| PTC & GPT Sites |
| Crypto Faucets |
| Freelance Sites |
| Ad Networks |
| Crypto Exchanges |
| Crypto Data & Tools |
| Communication Tools |

## 3. Ownership Verification

```
1. Copy the token shown in the Announce Platform wizard
2. Publish it in a text file at the domain root
   (file name shown in the wizard; currently topbest-verify.txt, a legacy name)
3. Liveadvertise fetches the file server-side
4. Match = verified (meta tags are not accepted)
```

Result: outbound links to the site are followed across the listing page, boards, cards and Featured rail. No upgrade required.

## 4. Tracking Pixel

| Property | Detail |
|---|---|
| Format | Invisible 1x1 image |
| Placement | Footer or just before `</body>` |
| Counts | Unique visitors to the owner's site |
| De-duplication | Same IP counted once per 24 hours |
| Required | No |
| Badge | Green Verified badge with pixel; "No pixel" label without |
| Scoring impact | Only when verified visitors is the active signal |

## 5. LA Rank Scoring Signals

| Signal | Rule |
|---|---|
| Outbound clicks | Visit button clicks, once per visitor per 24 hours |
| Verified visitors | Pixel-measured unique visitors (alternative traffic signal) |
| Upvotes | Confirmed-email members only; one per platform |
| Reviews | Members who visited in last 30 days; one each; moderated |
| Engagement | Planned; neutral baseline for all until live |
| Ties | Claimed listings rank first |

Only one traffic signal (clicks or verified visitors) is scored at a time. Weight changes apply to all listings at once.

## 6. Discovery Boards

| Board | Shows |
|---|---|
| Latest Launches / Live Rankings | Newest and currently ranked listings |
| Top 10 This Week | Weekly leaders |
| Rising Fast | 7-day score gains vs each site's own record |
| New Sparks | Newly verified arrivals |
| Hall of Fame | Each month's top ten, permanently |
| Featured rail | Paid Featured Ads placements |

## 7. Owner Features

| Feature | Requires |
|---|---|
| Analytics (clicks out, traffic in, rank history) | Free claim |
| Reviews dashboard and disputes | Free claim |
| Live rank badge (200 x 48 SVG, refreshed every few hours) | Free claim |
| Tie priority | Free claim |
| Featured Ads | Free claim + optional payment |

## 8. Fair-Play Rules

- Buying traffic or votes can lead to suspension
- Fake voting can lead to suspension
- Listing sites the owner does not own can lead to suspension
- Anti-cheat flags suspicious patterns for human review
- Balances on accounts closed for cheating are not refunded

## 9. FAQ

**How is LA Rank calculated?**
Mainly from traffic (clicks or verified visitors), with upvotes and reviews separating close listings. Recalculated weekly.

**Is announcing a platform free?**
Yes.

**Does the badge affect score?**
No. It is display only.

**Note for visitors:** rank reflects interest, not endorsement. Research platforms before signing up or depositing funds.

**Start here:** [How Liveadvertise works](https://liveadvertise.com/how-it-works)

## Tags

Liveadvertise, LA Rank, Announce Platform, announce website free, website directory, platform launch directory, traffic-ranked directory
