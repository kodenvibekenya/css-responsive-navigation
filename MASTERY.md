# Mastery check — CSS Project 2 — Responsive navigation

“Nailed it” is a three-gate decision. You must pass **all three** gates; a green automated run alone is not mastery.

## Gate 1 — Automated project checks

From the repository root, run:

```sh
node --test test/mastery.test.mjs
```

Every check must pass without skipping, deleting, or weakening a check.

- [ ] Universal border-box sizing covers pseudo-elements, and the skip link has a focus-reveal rule.
- [ ] The semantic list becomes a wrapping flex row with reset markers and comfortable link targets.
- [ ] The header starts stacked, switches to a row in a content-driven media query, and preserves focus and current-page cues.

These checks cover selected functional and structural criteria. They do **not** claim to judge visual quality, usability, or accessibility conformance.

## Gate 2 — Applicable manual browser and accessibility checks

- [ ] From the address bar, press Tab and confirm the skip link becomes visible and moves focus to main content.
- [ ] Test continuously from 320 CSS pixels to a wide window at 200% zoom; links wrap without page-level horizontal scrolling.
- [ ] Replace one label with a much longer phrase and confirm focus, current-page indication, and layout still work.

Record the browser, viewport/zoom, input method, and any assistive technology used.

## Gate 3 — Explain back

Answer all three prompts in your own words. Each answer passes when it is accurate, points to concrete evidence in this project, and explains the reason or trade-off—not merely what a line says. A peer, mentor, or reviewer should ask one follow-up where an answer is unclear and record pass/revise for every prompt.

1. Why does the navigation wrap, and which boxes are allowed to grow or shrink?
2. What content condition motivated your media-query breakpoint?
3. How is the current page communicated without depending on color alone?

## Evidence record

Keep this short record in an issue, pull request, or learning log:

- Commit checked:
- Automated command, date/time, and result:
- Manual check environment and result for each item (or the documented not-applicable reason):
- Explain-back reviewer and pass/revise result for prompts 1–3:
- Help, tools, examples, or references used:
- Remaining limitation or next improvement:

## Honest boundary

This is formative practice, not a certification or proof of independent authorship. The repository owner can edit both code and visible checks, so CI records evidence about one revision rather than guaranteeing mastery. Manual observations and explain-back review remain necessary, and no single project demonstrates complete accessibility or professional readiness.
