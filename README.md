# The Schema Constructor

A short browser simulation about unproductive success. You plan a Reconstruction Era unit for one student, Alex, and choose at each lesson between scaffolded thinking and an AI shortcut. The essay looks finished either way. A transfer test at the end shows whether anything was built underneath it.

Allow about ten minutes. Written for grades 9-12 and for teacher professional learning.

Play it at <https://minerclass.github.io/schema-constructor/>.

## How it works

- **Two choices per lesson.** Scaffolded Thinking costs time units and adds connections to Alex's schema net. AI-Bypass Automation costs nothing and returns a polished draft.
- **Three meters.** Schema Density, Friction (Challenge), and Hollow Polish update as you choose. The calibrated challenge range is 55-80%.
- **A prediction before the test.** You forecast whether Alex's essay will hold or shear under an unfamiliar prompt. Keys 1 and 2 select the forecast.
- **A debrief.** The final report compares your forecast with the result and prints a unit evaluation.

## Run it locally

Open `index.html` in a current browser. There is no build step, framework, package manager, or account. The page links one shared stylesheet, `https://minerclass.github.io/tokens.css`, and falls back to its own colours when that file is unavailable.

## Conceptual grounding

Pedagogical friction, productive and exclusionary friction, and unproductive success as used here come from the framework Micah Miner is developing in his dissertation research. They are presented as proposals in progress, not as established terms or completed findings.

## What this does not claim

- All scores, stats, and achievements are illustrative models of the pedagogical friction framework, not validated learning assessment instruments.
- The students in the game are fictional design profiles. They are not participants and do not represent real learners.
- Nothing here calls an AI service. The "AI" choices are scripted teaching examples.
- The game does not measure learning, does not evidence any dissertation claim, and reports no findings.
- No participant, student, or staff data is used, collected, stored, or transmitted.

## Accessibility

The layout adapts to phone widths under 480px. Animation respects the system reduced-motion setting. A contrast check on September 1, 2026 found no failures, with the tightest pair at 5.14. Keyboard support beyond the prediction keys has not been audited.

## Implementation

Everything lives in one file, `index.html`, with inline CSS and JavaScript. GitHub Pages publishes from `main` through `.github/workflows/pages.yml`.

## Logs

`BUILD_LOG.md` records how the game was built and what was verified. `AGENT_LOG.md` is an append-only record of agent-assisted changes. Neither file holds participant data, credentials, or tokens.

## Related

- Games hub: <https://minerclass.github.io/games-hub/>
- Dissertation overview: <https://minerclass.github.io/dissertation-overview/>
