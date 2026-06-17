# Attio: example company repo (TripleDart webinar)

> This is the demo repo for the live session "Become a better performance marketer on product marketing foundations" (Press X to Market x TripleDart, 2026-06-23). It is a worked example, not a real client engagement. All facts are from Attio's public website and public sources as of June 2026. Verify before quoting any number on stage.

## What this repo is

A pre-built context repo for one company (Attio), so an AI agent can run the three foundation skills (ICP, positioning, messaging) and produce defensible output without anyone pasting context mid-call. Same shape as the take-home template attendees fork.

## How the live demo runs

1. **Open the repo.** The agent reads `context/` automatically (this CLAUDE.md is the entry point).
2. **Show the ads.** Pull up `examples/` (Attio's real ads) so the room sees what they run today.
3. **Run the three skills, in order** (share screen + terminal):
   - `icp-definition` -> writes to `outputs/icp.md`
   - `positioning-audit` -> writes to `outputs/positioning.md`
   - `messaging-hierarchy` -> writes to `outputs/messaging.md`
4. **Compare.** Read the outputs against the real ads in `examples/`. Where do today's ads drift from the foundations?
5. **Ship the deck.** Run the `playground` skill on the outputs to produce a shareable visual.

## What's in here

| Path | Holds |
|---|---|
| `context/profile.md` | Company overview, product, traction, pricing |
| `context/market.md` | Category, audience, where they play |
| `context/competitors.md` | The alternatives Attio positions against |
| `context/voice.md` | How Attio talks (tone, vocabulary) |
| `skills/` | Pointers to the three pmm-skillset skills + how to install |
| `examples/` | Attio's real ads (drop in before the session) |
| `outputs/` | Where the skill runs land (empty until run) |

## Demo-safety notes (for Gab)

- **Pre-run the skills once** before the session and keep the outputs, so if the live run stalls you can fall back to the saved artifacts and keep narrating.
- The positioning audit will surface debt and white space. Keep the tone analytical and respectful. Attio is a strong brand; the point is "even good brands inherit drift," not "Attio is bad."
- Confirm Attio's current pricing and any logos live before stating them. Public numbers move.
