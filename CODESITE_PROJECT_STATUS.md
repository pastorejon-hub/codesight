# CODESITE Project Status
Updated: 2026-11-03
Repository: pastorejon-hub/codesight

## Source of truth
- Production: main
- Snapshot before University: backup-before-university
- University development: feature/codesite-university
- Never modify main without review and explicit approval.
- Keep Douglas County repositories separate.

## Verified repository inventory
- index.html — 568,982 bytes, production entry point
- index (1).html — identical blob to index.html
- index.html.html — identical blob to index.html
- README.md — describes existing features and deployment
The three HTML copies are not to be deleted without review.

## Existing features (documented in README; implementation not yet audited)
- Uniform dashboard and navigation
- Residential and commercial electric/solar-ready references
- Commercial EV-ready references and calculator
- Code definitions and inspection topics
- Correction Writer
- Code Library framework; some features incomplete
- Static HTML/CSS/JavaScript, no backend or account sync
- Browser-local storage for some drafts/checklists

## Product direction
CODESITE Field: inspector-facing reference workflow with expandable code cards, section search, Copy Citation and Copy Correction.
CODESITE University: responsive interactive training, starting with 2026 NEC Article 706 Energy Storage Systems.
Preserve existing branding, reticle, dark/light themes, navigation and code-reference functionality.

## University prototype requirements
1. Add University button to existing homepage.
2. Create University dashboard and Article 706 course.
3. Desktop, iPad, phone navigation with responsive controls.
4. Display existing 16:9 artwork fully, without cropping or distortion.
5. Lessons, instructor explanations, code navigation exercises, and knowledge checks.
6. Original educational summaries; 2026 NEC exclusively. Verify section references before publication.

## Next steps
1. Audit current index.html structure, navigation, styles and scripts.
2. Design minimal-risk University integration on feature branch.
3. Test existing Field functionality for regressions.
4. Review prototype before merging to main.
5. Plan user testing and commercial validation.

## Release safeguards
- No direct edits to main during prototyping.
- Backup branch is a snapshot, not a continuously updated backup.
- Test desktop, tablet and phone before release.
- Keep copyrighted code text out of the public website unless appropriately licensed.
- Public GitHub repository exposes source content; consider commercial security and IP requirements.
