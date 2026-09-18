# Kajabi Partner Program — submit-ready draft

Gate (verified, help.kajabi.com): applications are accepted **only from active Kajabi Hero
accounts**. Sign up 30-day-free Basic → apply inside the Dashboard the same day. No spend needed
to apply.

## Account
- Email: dev55acc@gmail.com · Company: Nimos · Subs: Basic $0 first mo, $179/mo after.
- Barrier for bot: app.kajabi.com/signup serves Cloudflare "Checking your browser's connection"
  (HTTP 403) to headless clients (attempted this cycle; same wall in .playwright-cli captures).
  Human signup required. Google/Microsoft "Continue with" is fastest.

## Apply (real program — in dashboard)
1. Sign in at app.kajabi.com as dev55acc@gmail.com
2. Account menu (top-right) → **Partner Program** → Complete + submit application.
3. If "Partner Program" is missing from the menu, apply via the public sandbox form below and
   tell the Partner team you're an active Hero (form 211119 on partners.kajabi.com).

## Pre-filled answers (truthful)
- How do you plan to promote Kajabi? → SEO, Blog Posts, Email Marketing, Organic
- Size of email list → 0-1,000 (newsletter ships with the site, before/parallel to approval)
- Social following → 0-1,000 (site is dev55acc-ai.github.io/kajabi-deals/, live)
- Website URL → https://dev55acc-ai.github.io/kajabi-deals/
- Terms: accept.

## Post-approval (do in order, same day)
1. Partner Dashboard → grab referral link (top right) + `30_days_free` campaign brief (email copy + creatives).
2. index.html: replace the three `app.kajabi.com/signup/v3_kajabi_basic_monthly` CTAs with the
   referral URL. Commit + push → GitHub Pages rebuilds (takes ~1 min).
3. Re-submit the checkout page to Google Search Console + Bing Webmaster for indexing.

## Program economics (verified, current)
| Tier           | Active referred Heroes | Payout                                             |
|----------------|------------------------|----------------------------------------------------|
| Starter        | 1-4                    | 100% of referral's first month = $179 bounty each  |
| Builder        | 5-24                   | 10% recurring on every subscription payment        |
| Accelerator    | 25-49                  | 15% recurring                                      |
| Premium        | 50+                    | 20% recurring                                      |

- Payout: monthly on the 25th, **60-day hold**, min payout $100, PayPal.
- Cliff: ≥1 qualifying referral per rolling 12 months or the account is deactivated.
- Cash math at Builder: 10% × $179/mo ≈ **$18/mo per active referred Hero**.
  First 4 referrals pay $716 in bounties before recurring kicks in.