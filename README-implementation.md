# AURA/UPWARD Third Draft - Implementation Notes

This package is a multi-page static-site draft for the AURA/UPWARD public web presence. It preserves the Limina-style visual language from the previous draft while implementing the deeper ClickUp source review.

## Files

- `index.html` - main AURA/UPWARD landing page
- `architecture.html` - dedicated Architecture of Discovery explainer page
- `submission-guidelines.html` - public proposal submission guide for PIs
- `review-process.html` - simplified public review-process page
- `style.css` - shared Limina-style design system
- `zak-build-sheet.md` - implementation checklist for website/editor handoff
- `source-notes.md` - source-based rationale and public/private boundary notes

## Deployment

Upload all four HTML files and `style.css` to the same GitHub Pages directory. The pages use relative links and will work from the repository root.

The submission CTA points to the ClickUp form supplied by Michael:

https://forms.clickup.com/90151026989/f/2kypq09d-3535/GQ9VUSO96NBS3LF061

## Core public-state changes implemented

1. Visible initiative explainer on the main page.
2. Dedicated Architecture of Discovery page rather than modal/lightbox content.
3. Dedicated Proposal Submission Guidelines page.
4. Dedicated Proposal Review Process page.
5. Public lifecycle changed to the 5-phase model:
   - Phase 0: Conceptual Design
   - Phase 1: Preliminary Design
   - Phase 2: Final Design
   - Phase 3: Research Execution
   - Phase 4: Final Synthesis and Integration
6. Public references to Research Readiness Levels removed from the website pages.
7. Public review explanation kept high-level. Internal weights, thresholds, donor-visibility rules, and unresolved governance details are not published.
8. AURA/UPWARD distinction kept crisp: AURA is operational; UPWARD is integrative.

## Optional next step

If the GitHub Pages repo only supports one public page for the initial release, deploy `index.html` first and link the other three pages from the nav once ready. The copy is written so the main page can stand alone, but the full intent is multi-page.
