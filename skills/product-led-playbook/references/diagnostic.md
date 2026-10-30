# Diagnostic Intake: Playbook Coach

The book's own True North funnel is the diagnostic instrument. Get the user's numbers for the 6 GTM metrics, find the biggest leak, and that maps to a component. Never guess at the broken component when the funnel can tell you.

## Intake

1. **Context**: what they sell, to whom, price point, free model (trial/freemium/none), rough MRR.
2. **The funnel**: monthly numbers for: unique visits → signups → completed setup → First Strike (first time experiencing core value) → KUI (repeated value) → upgrades. Many users won't know First Strike/KUI numbers. That gap is itself a finding (Data Component problem).
3. **The symptom**: what they think is broken, in their words.

Ask for the funnel in one message, as a fill-in list. If they only have partial numbers, work with what exists and flag the gaps.

## Funnel leak → component map

| Biggest leak | Likely component | But check upstream |
|---|---|---|
| Visits → Signups poor | **4. Offer** (homepage doesn't convert) | Strategy: are they even targeting a winnable segment? User: is the traffic the ideal user at all? |
| Signups → Setup poor | **5. Onboarding** (friction in setup) | Model: does the free model ask too much before showing value? |
| Setup → First Strike poor | **5. Onboarding** (no straight line to value) | User: is First Strike even defined around the ideal user's endgame? |
| First Strike → KUI poor | **5. Onboarding** bumpers / **2. User** (wrong value hypothesis) | Product gap vs. knowledge gap vs. skill gap: diagnose which |
| KUI → Upgrade poor | **6. Pricing** (value metric / ladder mismatch) | Offer: is the upgrade solving something the user wants to upgrade in their life? |
| Can't measure any of this | **7. Data** (build the scorecard first) | None |
| Funnel fine but growth chaotic / founder is the bottleneck | **8. Process** / **9. Team** | None |
| Everything mediocre everywhere | **1. Strategy** (the system has no spine) | Run the Bullseye before touching anything downstream |

Benchmark for severity: 40–60% of signups never return (book's baseline). A leak materially worse than that is the priority.

## Diagnosis output format

1. **Diagnosis**: the broken component, in one sentence, with the funnel evidence.
2. **Upstream check**: one sentence on why the components upstream of it are (or aren't) sound. If upstream is broken, redirect there and say why.
3. **The fix**: which framework you'll run and what artifact it produces (see `templates/`).
4. **What would change my mind**: the one piece of evidence that would point elsewhere.

Then run the framework as an exercise and produce the artifact from the matching template. Check every written artifact against `voice-guide.md` before delivering.
