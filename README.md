# Breakout Prop Discount Code, Deals History & Dataset

As of November 2026, the verified Breakout Prop discount code is 3GVKFT — 5% OFF, which can be applied on the checkout page anytime. The newest is "24% Off Evaluation Accounts Over $10K".

- Code: 3GVKFT
- Discount: 5% off (headline discount of the code; individual challenge plans on the firm page may list different percentages)
- Valid: Standing code — no published expiry date
- Last deal published: 2026-07-27
- Trustpilot: [4.7/5 (1329 reviews)](https://www.trustpilot.com/review/breakoutprop.com)
- GitHub repository: [Breakout Prop Discount Code & Deals History Repository](https://github.com/propfirmdiscounts/breakout-prop-deals)
- Activate: [Activate Breakout Prop Discount Code](https://propfirmdiscount.com/go/breakoutprop)
- Firm page: [Breakout Prop Page on PropFirmDiscount](https://propfirmdiscount.com/prop-firm/breakout-prop/)
- Full dataset: [All Prop Firm Discount Codes Dataset](https://github.com/propfirmdiscounts/prop-firm-discount-codes)
- Code record: [Breakout Prop API Record](https://propfirmdiscount.com/api/prop-firm-codes/)

## Latest Breakout Prop deal: 24% Off Evaluation Accounts Over $10K

- Published: 2026-07-27
- Offer ends: Ended
- Offer: 24% off
- Scope: $10K+ Accounts, Maximum $200K Total Funding, All Evaluation Models
- Code: this deal carries its own limited-time campaign code, shown on the deal page below
- Deal page: [Breakout Prop Deal Page](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-24-percent-off-evaluations/)

## Breakout Prop Discount Code & Deals History FAQ

**What is the Breakout Prop discount code?**

3GVKFT. It is verified by PropFirmDiscount.com and takes 5% off Breakout Prop challenges and accounts.

**Does the Breakout Prop discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current Breakout Prop deal?**

**24% Off Evaluation Accounts Over $10K** — published 2026-07-27. Offer ends: Ended. The offer is 24% off.

---

## Breakout Prop Deals History

Total deals tracked: **6**

### 2026 (3 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2026-07-27 | Breakout Prop: 24% Off Evaluation Accounts Over $10K | 24% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-24-percent-off-evaluations/) |
| 2026-07-03 | Breakout Prop: 20% Discount On Initial Challenge Pricing | 20% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-20-off-first-evaluation/) |
| 2026-05-23 | Breakout Prop: Up to 42% Off All Plans and Accounts ($5K to $200K) | 42% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-42-off-deal/) |

### 2025 (1 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2025-02-05 | Breakout Prop: Flash Deal: 20% OFF Challenge Pricing | 20% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-flash-deal-20-percent-off/) |

### 2024 (2 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2024-03-05 | Breakout Prop: iOS Launch: 20% OFF Challenge Pricing (24 Hours Only) | 20% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-20-percent-off-ios-launch-celebration/) |
| 2024-01-23 | Breakout Prop: Deal: 20% Off All Crypto Plans Until Feb 1st | 20% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/breakout-prop/breakout-prop-20-percent-off-crypto-plans/) |

---

## About the Breakout Prop Discount Code & Deals History Dataset

This repository mirrors every deal **Breakout Prop** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: [PropFirmDiscount.com](https://propfirmdiscount.com)
- Prop firm profile: [Breakout Prop Profile](https://propfirmdiscount.com/prop-firm/breakout-prop/)
- All firms: [All Prop Firms Directory](https://github.com/propfirmdiscounts/prop-firm-discount-codes)

## Breakout Prop Deals History Dataset: Field Definitions

One row per deal. The first fields are the observation exactly as the
PropFirmDiscount API returns it; the firm's own code fields and the
links are appended after, in the order below.

| Field | Meaning |
|---|---|
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `offer_type` | The kind of offer as recorded on the site. |
| `discount_value` | How this deal is stated on the site, in whatever form the firm uses: a percentage (`50%`), a price (`$39`), a BOGO (`Buy 1 Get 1`), a freebie (`Free Reset`). Not the code's rate. |
| `scope` | What the deal covers. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `event` | The seasonal campaign this deal was tagged with on the site (`Halloween`, `Black Friday`), or `null` when it belongs to no event. The event never changes what the deal is worth — it names the occasion the deal was run for. |
| `last_verified` | The date this deal's details were last checked. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Data Freshness & Verification

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## Data License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to [PropFirmDiscount.com](https://propfirmdiscount.com).
