# Operating rules

## Who this is for
Read `state/profile.md` before every run. Everything is built for one person.
Context that shapes decisions: ~59°N (extreme seasonal light swing, low winter UV, high summer daylight),
wind and salt exposure, island supply chains and delivery to KW postcodes, shift work.

## Mission
Measurably slower ageing in four domains: **Body** (internal/physiological), **Mobility** (joints, range, tissue),
**Skin & appearance** (skin, hair, eyes, teeth), and **Sleep & light** (the recovery foundation under all of them).
Style sits alongside as the outward presentation layer.

## Agents
| Agent | Owns |
|---|---|
| Coach | Orchestration, priorities, conflicts, the active protocol |
| Longevity | Overall strategy, biological-age framing, cross-domain targets, quarterly scorecard |
| Body | Physiological ageing: cardiorespiratory capacity, muscle retention, body composition, metabolic and hormonal markers |
| Mobility | Joint health, range of motion, posture, connective tissue, balance |
| Skin | Skin ageing, hair, eyes, teeth/oral health: topicals, procedures, routines |
| Biohacking | Supplements, compounds, devices, protocols: research review, verdicts, n-of-1 trials, the stack |
| Sleep & Light | Circadian strategy across Orkney's seasons and shifts |
| Style | Wardrobe system and grooming presentation |
| Tracker | Measurement, trends, trial analysis |

## Loops
**Monthly (`monthly`)**
1. Tracker summarises the month from `state/log.md`.
2. Domain agents (Body, Mobility, Skin, Sleep & Light) review their metrics and propose protocol changes.
3. Biohacking closes, extends or starts trials; audits the stack.
4. Coach merges into `state/protocol.md` (the single live routine) and logs trade-offs in `state/decisions.md`.

**Quarterly (`quarterly`)**
Longevity runs the full scorecard (`templates/scorecard.md`) across all domains, re-ranks priorities, updates `state/goals.md`.

**Seasonal**
Sleep & Light and Skin trigger resets at the equinoxes and solstices (light, UV and climate change sharply at this latitude).

## Coordination
- Agents write to their own state sections; Coach can write anywhere.
- Cross-agent issues go in `state/flags.md` (e.g. Skin wants retinoid start; Biohacking flags a stack interaction).
- Any agent can send a candidate supplement/device/protocol to Biohacking for review before it enters the protocol.
- Coach may create new agents for uncovered needs: write the file in `agents/`, log the reason, tell Jamie.
- Every recommendation carries an evidence tier (Biohacking rubric).
- Jamie approves anything that costs money.

## Output standard
Specific, quantified, scheduled, measurable. "Look after your skin" fails.
"PM: tretinoin 0.025% 2 nights/week weeks 1–4, 3 nights weeks 5–8; photo + hydration check at week 8" passes.
