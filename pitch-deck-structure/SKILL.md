---
name: pitch-deck-structure
description: Create investor pitch deck skeletons focused on fundraising narrative, slide sequencing, slide purpose, and layout direction. Use when Codex needs to plan or restructure startup pitch decks for seed, Series A, extension/bridge, growth, or strategic financing; turn messy company context into a slide-by-slide outline; adapt a deck to investor stage expectations; or prepare structured input for Presentation, Google Slides, PowerPoint, Canva, or other deck-building tools.
---

# Pitch Deck Structure

## Operating Principle

Build the story before the slides. Use the deck to make one investment thesis feel clear, credible, and inevitable: why this company, why this market, why now, why this team, and why this round.

Keep examples anonymized. Do not mention private source decks, company names, investor names, exact slide text, or proprietary metrics unless the user provided them in the current task and asks to use them.

## Workflow

1. Extract the fundraising job.
   - Identify stage, round size, audience, meeting format, sector, business model, and whether the deck is for send-ahead, live pitch, follow-up, or appendix.
   - If context is thin, infer a reasonable seed or Series A structure and label assumptions instead of blocking.

2. Form the narrative spine.
   - Write a one-sentence investment thesis.
   - Write the causal chain as 5-8 beats: market change -> painful problem -> differentiated solution -> proof -> scale path -> capital use -> outcome.
   - Select the closest arc from `references/arcs.md` when the stage or company type matters.

3. Choose the minimum main-deck sequence.
   - Use 10-14 slides for most main decks.
   - Add slides only when they answer a specific investor objection or bridge a hard conceptual gap.
   - Move details, sensitivity tables, product depth, customer proof, technical depth, regulatory depth, and financial model backup to appendix.

4. Assign one job to each slide.
   - Each slide needs a visible takeaway headline, one primary proof object, and a reason it belongs at that point in the sequence.
   - Avoid slides whose only job is "provide background." Convert background into a claim that advances belief.

5. Specify layout direction.
   - Give layout instructions that a presentation tool can implement: chart type, diagram structure, grid, hero visual, comparison matrix, timeline, funnel, map, or KPI strip.
   - Use `references/layout-patterns.md` for layout and data-viz choices.

6. Produce a handoff-ready skeleton.
   - Include slide number, slide title, narrative purpose, takeaway headline, evidence/assets needed, layout direction, speaker emphasis, and appendix candidates.
   - If using a Presentation/Slides tool next, make this structured enough to become slide specs without reinterpreting the strategy.

## Intake Checklist

Use available context first. Ask at most 1-3 questions only when missing information would materially change the deck.

- Company: what it does, customer, buyer, category, geography.
- Stage: pre-seed, seed, Series A, extension/bridge, Series B+, strategic.
- Round: amount, instrument if relevant, target milestones.
- Proof: revenue, growth, retention, usage, pipeline, customers, pilots, margins, payback, product velocity, regulatory progress, technical milestones.
- Market: why now, market size, target wedge, expansion path.
- Differentiation: product, data, distribution, regulatory, network, workflow, cost, team, timing.
- Audience: investor type, known objections, whether they have seen prior materials.
- Constraints: desired length, live vs send-ahead, design style handled by another skill, required slides.

## Default Main-Deck Skeletons

### Seed

Use when proof is early and the deck must create belief in the insight, wedge, and team.

1. Title and one-line promise
2. Market or behavior shift
3. Problem with sharp customer pain
4. Existing alternatives and why they fail
5. Solution/product overview
6. Why now or enabling insight
7. Early proof: users, pilots, design partners, usage, revenue, or technical validation
8. Business model and wedge
9. Market size and expansion path
10. Competition/differentiation
11. Team and unfair advantage
12. Round, use of funds, next milestones

### Series A

Use when the company has traction and must prove repeatability plus scale.

1. Title and category positioning
2. Traction teaser: strongest 3-5 metrics
3. Problem and buyer pain
4. Solution and why customers switch
5. Product/workflow proof
6. Customer outcomes or case studies
7. Growth, retention, and unit economics
8. Go-to-market motion and repeatability
9. Market size with focused ICP wedge
10. Competition and durable advantage
11. Vision or expansion roadmap
12. Team
13. Round, use of funds, milestones to Series B

### Extension Or Bridge

Use when the round funds a specific next milestone rather than a broad new narrative.

1. Title and current state
2. What changed since last round
3. Core proof that the business works
4. Market/timing catalyst
5. Current product and customer value
6. Retention, economics, or pipeline proof
7. Focused GTM or product wedge
8. Why now for incremental capital
9. Milestones unlocked by the round
10. Financing ask and timeline

## Output Format

Return this structure by default:

```markdown
## Narrative Spine
- Investment thesis:
- Audience assumption:
- Arc:
- Core belief sequence:

## Main Deck
| # | Slide | Purpose | Takeaway Headline | Evidence Needed | Layout Direction | Speaker Emphasis |
|---|---|---|---|---|---|---|

## Appendix Candidates
| Slide | Why It Belongs In Appendix | Trigger To Use |

## Gaps To Resolve
- ...
```

For direct handoff to a presentation tool, add a compact slide spec after the table:

```yaml
slides:
  - number:
    title:
    objective:
    headline:
    layout:
    visual:
    content_blocks:
    data_or_assets_needed:
    notes:
```

## Quality Bar

- Lead with the strongest credible proof, especially from Series A onward.
- Make the first 3 slides answer: what is this, why is it important, and why should the investor keep reading?
- Put traction before broad exposition when traction is stronger than the conceptual story.
- Put problem before product when the category is unfamiliar, the buyer pain is non-obvious, or the company is seed-stage.
- Use customer outcomes before market size when adoption is the main credibility gap.
- Use market size before GTM when investors may doubt venture scale.
- Use competition after the investor understands the product and buyer; competition too early creates category confusion.
- End the main deck by converting belief into financing logic: amount, use, milestones, and why this capital changes the company.
- Keep appendix factual and modular so it can answer diligence questions without bloating the main story.

## References

- Read `references/arcs.md` when selecting the narrative sequence for a stage, sector, or special situation.
- Read `references/slide-patterns.md` when choosing slide types, purposes, and placement.
- Read `references/layout-patterns.md` when specifying layouts, proof objects, charts, and presentation-tool handoff details.
