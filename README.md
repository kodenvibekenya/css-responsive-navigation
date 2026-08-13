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
## Get your automatic project grade

1. [Create your own copy](https://github.com/kodenvibekenya/css-responsive-navigation/generate) from this template.
2. Read [MASTERY.md](MASTERY.md), then create an attempt branch:

   ```sh
   git switch -c attempt/my-project
   ```

3. Build the project and run the same check GitHub uses:

   ```sh
   node --test test/mastery.test.mjs
   ```

4. Commit and push the attempt branch:

   ```sh
   git add .
   git commit -m "Complete project attempt"
   git push -u origin attempt/my-project
   ```

GitHub Actions grades every pushed attempt automatically. **PASS — NAILED IT** means every required check passed. **REVISE — KEEP BUILDING** means the run shows what to fix before you push again. You do not need the KODE Ń VIBE owner to review or start anything; the template's `main` branch stays quiet on purpose.

The [free grading guide](https://kodenvibe.tech/notes/mastery/) explains the result and its limits.
<!-- mastery-kit:end -->
