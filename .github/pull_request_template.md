<!--
Frontend PR Template
Keep titles Conventional Commit style, e.g. "feat(ui): add payment card"
-->

## Summary
<!-- What & why in 1–3 lines. Link designs/specs if any. -->

## Type
- [ ] feat
- [ ] fix
- [ ] refactor
- [ ] chore/build
- [ ] docs
- [ ] perf
- [ ] test

## Linked Work
Issue/Task: #  
Design/Spec:  

## Screenshots / Recordings
<!-- Prefer before/after. For interactions, attach a short Loom/GIF. -->
**Before:**  
**After:**  

## Demo / Storybook
- [ ] New/updated Storybook stories
- Local run steps: `pnpm storybook` / `npm run storybook`

## How to Test
1. …
2. …
3. …

## Technical Notes
<!-- Key implementation details, tradeoffs, notable patterns introduced. -->

## Checklist
**Quality**
- [ ] Builds locally (`npm run build`) and lints clean (`npm run lint`)
- [ ] Types pass (`npm run typecheck`)
- [ ] Unit tests added/updated (`npm run test -u`) and pass
- [ ] E2E/visual tests added/updated (if applicable)

**UI/UX**
- [ ] Matches design (spacing, colors, typography, states)
- [ ] Responsive across breakpoints
- [ ] Cross-browser (Chrome, Safari, Firefox) sanity check
- [ ] Dark mode supported (if app has it)

**Accessibility**
- [ ] Semantic HTML, proper roles/labels
- [ ] Keyboard navigation & focus order
- [ ] Color contrast ≥ 4.5:1 (text) / 3:1 (UI elements)
- [ ] ARIA where needed; no redundant ARIA

**Performance**
- [ ] No large bundle regressions (analyze if +>20KB gzip)
- [ ] Code-split/lazy-load where sensible
- [ ] Images optimized (next/image, srcset, SVG when possible)

**i18n & Content**
- [ ] All user strings externalized (i18n keys)
- [ ] RTL safe (if supported)
- [ ] Copy reviewed (typos, grammar)

**Analytics / Telemetry**
- [ ] Events added/updated with clear names & properties
- [ ] PII safe; behind consent where required

**Security**
- [ ] No unsafe HTML/`dangerouslySetInnerHTML` (or sanitized)
- [ ] Inputs validated; no secret keys in code
- [ ] Dependency risks reviewed (if adding libs)

**Env / Config / Flags**
- [ ] New env vars documented with defaults
- [ ] Feature flags added & documented
- [ ] Migrations/backfills (if data shape changed)

**Docs**
- [ ] README/MDX/Storybook docs updated
- [ ] Release notes / Changelog entry prepared

## Rollout / Risk
- Risk level: Low / Medium / High
- Rollback plan: …
- Owner on-call for release: …

## Breaking Changes
- [ ] None
- Details: …

