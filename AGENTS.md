# Prototype Instructions

Run the local server yourself and open the preview in the browser available to this environment. Do not give the user server-start instructions when you can run it.

Before making substantial visual changes, use the Product Design plugin's `get-context` skill when the visual source is unclear or no longer matches the current goal. When the user gives durable prototype-specific design feedback, preferences, or decisions, record them in `AGENTS.md`.

When implementing from a selected generated mock, treat that image as the source of truth for layout, component anatomy, density, spacing, color, typography, visible content, and hierarchy.

Build app UI in `src/`. Keep `.openai/hosting.json`, `worker/index.js`, `scripts/prepare-sites-build.mjs`, and `tests/sites-worker.test.mjs` intact so the same local prototype can be handed to Sites. Before a Sites handoff, run `npm run build` and `npm run test:sites`; the build must leave `dist/client/index.html`, `dist/server/index.js`, and `dist/.openai/hosting.json`.

## Approved design
Reference: /workspace/scratch/65589f70c392/generated_images/exec-c41d413d-3778-4970-bd83-a1b934d6ae3b.png
Cream peach background, coral/mint/butter/lavender palette. Left title/list and right large wheel. Header Produced by Li Jiajun in fancy cursive; main title 刘佳琳今天吃什么. Public sharing through Sites authorized. Nearby candidate shops: Jiaxing Nanhu Wanda and Harbin Fuli Jiangwan. Never claim Ctrip scores are delivery scores or delivery is verified. The wheel canvas is functional data visualization of actual selected entries/probabilities.

## Signature animation decision
The entrance writes the exact Great Vibes header font with visible, substantial pen strokes over the transparent page. The "Produced by" label stays in place; the name is blank until the completed signature lands there. The reference is the user's 4.8-second signature video supplied on 2026-11-26.
The signature should follow normal cursive writing order, with connected letters traced as flowing strokes rather than revealing disconnected segments by x-position.
