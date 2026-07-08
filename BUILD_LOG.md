# BUILD_LOG.md - The Schema Constructor

## 2026-07-07: Project Initialization & Core Specs
- **Goal**: Build an interactive educational game called "The Schema Constructor" illustrating the *Pedagogical Friction* framework's concept of "Unproductive Success" and cognitive schemas in historical writing.
- **Theme**: Reconstruction Era unit design (6 lessons: sourcing, context, corroboration, argumentation, synthesis, transfer).
- **Core Visuals**: 
  - Left panel: Interactive SVG "Schema Net" representing active connections in the student's mind.
  - Right panel: Clipboard paper interface displaying the drafted essay. AI-Bypass creates polished text with glowing gold borders; Manual thinking creates messy handwritten drafts with high schema density.
- **Calibration Limits**:
  - `PRODUCTIVE_CHALLENGE = [55, 80]`
  - `BARRIER_ACCESSIBLE_MAX = 20`
- **Required Footnote**:
  - `*Note: All scores, stats, and achievements are illustrative models of the pedagogical friction framework, not validated learning assessment instruments.`

## 2026-07-07: Remote Deployment & Verification
- **GitHub Repository**: Created public repository `minerclass/schema-constructor`.
- **Default Branch**: Branch `master` renamed to `main`, set as default branch on remote, and remote `master` deleted.
- **GitHub Pages**: Enabled via REST API. Live URL: `https://minerclass.github.io/schema-constructor/`
- **Verification Status**: Verified zero external CDNs or Google Fonts. Responsive layout checked across mobile and desktop viewport profiles. Tested transfer test thresholds (`schemaDensity >= 55` required). Passed local verification.
── QA fixes (2026-07-08): see commit log for the Phase 2 QA-pass fixes; full defect analysis in the session review.
