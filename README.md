# AI Adoption Scorecard
A small portfolio project by Aayan Khan exploring how to assess business tasks before an AI pilot.

## Run
Open `dist/index.html` in a browser. No dependencies, API keys or account required.

## Features
Eight task inputs; opportunity index; independent control gates; three synthetic examples; downloadable JSON assessment. Responsive layout and labelled controls. User-entered content is rendered as text, not HTML. Inputs remain in the browser.

## Method
Opportunity = rounded 100 × (frequency + repeatability + verifiability + readiness) / 12. Each dimension is 0–3. Control gates override the recommendation: impact >=2 or reversibility >=2 => specialist review; sensitive data >=2 or human review <2 => safeguards first. Otherwise opportunity >=67 => supervised pilot, >=34 => assistive use, else process clarification. Weights and thresholds are illustrative author choices, not validated research. This is a rules-based prototype, not an AI-powered product or compliance certification.

## Learning goals
Separate potential usefulness from risk, make assumptions visible, and design a simple interface people can challenge. The refund example deliberately has a high opportunity score but still requires specialist review.

## Limitations
No legal assessment, cost model, integration feasibility analysis or empirical validation. Self-reported inputs may be inaccurate. Recommendations do not authorise real deployments.

## Next steps
Test with five users, compare disagreements, refine wording and document revisions. Add cost and review-time estimates only once assumptions are explicit.

## Authorship
Developed by Aayan Khan with AI assistance for implementation and documentation. Review and understand the code before presenting it as your portfolio work.

## Upload to GitHub
Create a public repository named `ai-adoption-scorecard`. Upload README.md and the dist folder, preserving its structure. For GitHub Pages, copy the contents of dist to the repository root and enable Pages from the main branch/root. Do not upload private credentials or hosting configuration.
