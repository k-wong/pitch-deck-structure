# Layout And Data-Viz Patterns

Use layouts to support the narrative claim. A polished deck can use many visual styles, but the structural job of each slide should remain clear.

## Layout Rules

- Put the slide's conclusion in the headline. Do not make the viewer infer the message from the chart.
- Use one dominant proof object per slide: a chart, product flow, customer quote, map, matrix, or metric stack.
- Keep secondary proof visibly subordinate.
- Prefer large numbers with labels over dense paragraphs.
- Use annotations to direct attention to the inflection point, wedge, customer outcome, or strategic contrast.
- Use appendix slides for anything that requires close reading.

## Common Layouts

| Layout | Use For | Structure |
|---|---|---|
| Hero Metric | Traction teaser, outcome, unit economics | Large metric, short label, one supporting chart or source note |
| KPI Strip | Snapshot or traction overview | 3-5 metric cards in one row, consistent units, no mixed time periods without labels |
| Claim + Chart | Revenue, usage, market growth, funnel | Headline states conclusion; chart proves it; annotation marks key change |
| Before/After | Problem, ROI, workflow improvement | Left current pain, right improved state, bottom quantified delta |
| Workflow Strip | Product how-it-works | 3-5 steps with icons/screens; show actors and handoffs |
| System Diagram | Technical/platform solution | Inputs -> core engine/platform -> outputs; avoid internal implementation clutter |
| Competitive Matrix | Feature differentiation | Rows are buyer-relevant criteria; columns are solution categories; highlight the basis for winning |
| 2x2 Map | Category positioning | Axes must be investor/customer meaningful; label why the chosen quadrant matters |
| Wedge-To-Market | TAM and expansion | Initial ICP/wedge visibly nested inside larger expansion opportunities |
| Flywheel | Network, data, marketplace, payments | Each loop step should produce the next; include the monetization or data compounding point |
| Timeline | Roadmap, milestones, progress | Separate accomplished proof from future plan; mark funding-dependent milestones |
| Funnel | GTM, sales, onboarding, conversion | Stages with conversion or timing; highlight bottleneck and improvement lever |
| Map | Geographic/territory/coverage story | Use only when location matters to adoption, regulation, logistics, or market depth |
| Logo Wall | Social proof | Group by customer type or segment; do not use as a substitute for outcome proof |
| Case Card Grid | Customer results | 2-3 cards with problem, deployment, outcome, and metric |
| Capital Allocation | Use of funds | Allocation blocks tied to milestones, not generic departments |

## Data-Viz Guidance

- Growth: use line or bar charts with consistent time intervals. Annotate launches, channel changes, or market events only if they explain growth.
- Revenue plan: show historical actuals separately from forecast. Do not visually blend actual and projected data.
- Unit economics: use a simple equation, waterfall, or margin stack. Avoid spreadsheet screenshots in the main deck.
- Market size: use bottoms-up assumptions when possible. If using TAM/SAM/SOM, make the near-term serviceable market explicit.
- Retention: use cohort curves or NRR/GRR metric cards when retention is central to quality.
- Pipeline: show stage, conversion, and expected timing. A raw logo list is weaker than a pipeline shape.
- Competition: compare categories first when named competitors would distract; name competitors when investors will expect direct awareness.

## Presentation Tool Handoff

When handing off to a Presentation, Slides, PowerPoint, or Canva tool, provide:

- `layout`: name one of the layout patterns above.
- `visual`: describe the primary visual object and rough placement.
- `content_blocks`: give concise labels and bullets, not prose paragraphs.
- `data_or_assets_needed`: list missing numbers, logos, screenshots, charts, product images, or source tables.
- `notes`: explain why the slide appears at that point in the story.

Example anonymized slide spec:

```yaml
- number: 6
  title: "Customers see measurable value within the first month"
  objective: "Turn product interest into economic proof."
  layout: "Case Card Grid"
  visual: "Three customer cards with segment, deployment trigger, and quantified outcome."
  content_blocks:
    - "Segment A: operational time saved"
    - "Segment B: revenue lift"
    - "Segment C: cost reduction"
  data_or_assets_needed:
    - "Approved customer names or anonymized customer descriptors"
    - "Outcome metrics and time period"
  notes: "Place after product workflow so the audience sees the product before the proof of value."
```
