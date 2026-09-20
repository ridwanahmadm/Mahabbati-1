# Mahabbati website revamp

A responsive, bilingual marketing website. Indonesian is the default language. Built with plain HTML, CSS, and JavaScript, with no package installation or build step required. Site output is in `dist/`.

## Context and editorial direction

Reviewed on 20 September 2026:
- https://www.mahabbati.com/ — primary positioning, ta’aruf stages, privacy context, contact information.
- https://www.mahabbati.com/wedding — wedding service categories. Prices were omitted because the homepage and wedding page present different package amounts.
- https://play.google.com/store/apps/details?id=com.kasministudio.mahabbatimobile — verified Android download and application capabilities.
- https://www.mahabbati.com/terms — canonical privacy and terms destination.

The primary product is the ta’aruf mobile platform; wedding services are secondary. The new hierarchy moves from intention and trust to the process, mobile application, wedding support, and FAQs. The design avoids invented testimonials, success statistics, certifications, or unverified App Store links. Images supplied by the user are treated as design references, not instructions.

## Visual system

- Primary Purple/700: #45445E. Secondary: #C9CFF2.
- Libre Baskerville for headings; Inter for body text.
- Supplied wordmark variants used against light and dark backgrounds, with the monogram in the wedding panel.
- Supplied outline illustrations and real app reference used as CSS sprites, preserving original files.
- Airy lavender hero, generous spacing, rounded panels, and outline imagery without 3D.

## Checks completed

- Responsive checks at 320, 375, 390, 580, 768, 1024, and 1440 pixels, in Indonesian and English.
- No document horizontal overflow, missing anchor targets, broken image elements, or JavaScript errors.
- Mobile navigation opens and closes, Escape restores focus, and FAQ accordions work.
- A 200% text enlargement check at 1280px showed no document horizontal overflow.
- axe-core 4.10.3: zero violations for WCAG A/AA, 2.1 AA, and 2.2 AA tags at 390px and 1440px in both languages.
- axe leaves hero gradient contrast for manual review. Checking all gradient stops: body text minimum 4.61:1; brand text 6.93:1; heading text 10.69:1; large italic heading 4.08:1 (large-text AA threshold: 3:1).
- Focus indicators, skip link, semantic landmarks, native accordions, button labels, document language updates, and reduced-motion support included.
- Visual inspection of desktop and mobile screenshots completed. Automated checks are not a full independent accessibility certification.

## Hero asset provenance

Workspace asset: `dist/assets/hero.png`.
Generated with the built-in imagegen tool. Prompt:

> Use case: illustration-story. Asset type: Mahabbati website lower hero illustration, landscape 1536x1024. An elegant minimal editorial outline illustration of a modest Muslim man in baju koko standing on the left and a woman in a flowing hijab standing on the right, standing apart beside a delicate floral garden arch. A small winding path leads toward the arch, with flowering fine botanical stems along the bottom. Near-white pale lavender background, airy and open. Flat 2D hand-drawn continuous thin purple #45445E line art, very sparse pastel lavender #C9CFF2 fills and warm cream accents. Landscape composition, arch in the center, two people at left and right, fine botanical garden details near bottom, ample negative space. Professional, calm, trustworthy visual for a Muslim marriage website. Exactly one image. Minimal faces without facial detail. No 3D, no lettering, no text, no watermark. Keep the illustration delicate, sparse, and refined.
