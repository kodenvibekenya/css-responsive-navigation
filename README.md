# CSS Project 2 — Responsive navigation

Turn a semantic link list into a navigation bar that wraps comfortably instead of overflowing.

Companion notes: [CSS notes](https://kodenvibe.tech/notes/css/).

## Start your own copy

On GitHub, select **Use this template** → **Create a new repository**, choose whether it will be public or private, then clone your new repository and edit that copy.

**Time-box:** 60 minutes<br>
**Prerequisite:** CSS Foundations Lesson 2 and CSS Project 1<br>
**After-lesson milestone:** you can combine the box model, flexible spacing, text rhythm, and usable target sizes.

## Start

Open `index.html` and edit only `styles.css`. Resize continuously from 320px to a wide window; do not target a phone brand.

## Acceptance checklist

- [ ] Universal `border-box` sizing includes pseudo-elements.
- [ ] The skip link becomes visible when keyboard-focused.
- [ ] Navigation list markers and default padding are removed without changing semantics.
- [ ] Links wrap rather than cause page-level horizontal scrolling.
- [ ] Every navigation link has a comfortable minimum height and visible focus ring.
- [ ] The brand and navigation stack at narrow widths.
- [ ] One content-driven media query places them in a row when space permits.
- [ ] The current-page style is understandable without color alone.

## Finish

Test 320px, 200% zoom, a long translated link label, and keyboard focus.

<!-- mastery-kit:start -->
## How to know you nailed it

[![Mastery checks](https://github.com/kodenvibekenya/css-responsive-navigation/actions/workflows/mastery.yml/badge.svg)](https://github.com/kodenvibekenya/css-responsive-navigation/actions/workflows/mastery.yml)

Open [MASTERY.md](MASTERY.md), then run:

```sh
node --test test/mastery.test.mjs
```

The untouched challenge is expected to start red. Keep the failures visible while you work; make the implementation satisfy the checks instead of deleting, skipping, or weakening them.

A project is complete only when the automated checks, real-use/manual checks, and all three explain-back prompts pass. The [free KODE Ń VIBE mastery guide](https://kodenvibe.tech/notes/mastery/) explains why a green check alone is not enough.
<!-- mastery-kit:end -->
