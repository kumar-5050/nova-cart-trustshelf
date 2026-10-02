# TrustShelf – PromptWars Business Rescue Challenge (NOVA CART)

**Problem:** NOVA CART shows items local stores can't reliably confirm. Unavailability drives the top cancellation reason (35% of 11% cancels, ~1,482 orders/month), refunds and support tickets, and silent churn (61% of churned users had rated 4★+). Repeat rate fell 41%→27% while promo spend nearly doubled.

**Solution:** An availability-trust engine.
- **Store console:** one-tap "Still have it" confirmation, ordered by what needs attention first.
- **Confidence score (0–99):** stock, sales velocity and time since last confirmation.
- **Customer view:** honest badges, pre-dispatch store verification, smart same-category substitutes.
- **Impact simulator:** orders recovered, revenue, tickets avoided, budget shifted to retention.

**Business impact (60% of unavailability cancels prevented):** ~889 orders/month, ~₹4.3L extra monthly revenue (+16.5% on ₹26.1L). Sliders are scenario assumptions; baselines come from the case.

## Run
Open `index.html`. No build step, no dependencies.

## Quality
- Tests: 11 in-app unit tests (Tests tab)
- Security: strict CSP, `textContent`-only DOM, validated and clamped input
- Accessibility: skip link, labelled controls, 44px targets, non-colour status, live announcements, dark mode, reduced motion
- Efficiency: single file, zero dependencies
- Google services: Google Fonts (roadmap: Firebase store sync, Gemini catalogue hints)

## Prompt journey
1. "Find contradictions: what grows while quality falls?"
2. "Trace each KPI to a root cause; rank by upstream position."
3. "Design the lowest-effort store input that restores trust."
4. "What evidence would disprove delivery being the root cause?"
