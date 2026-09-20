---
mode: agent
description: Improve the existing Graphic Designer microsite while preserving Brianna Dickenson's portfolio architecture, visual identity, gallery behavior, and manual-artwork rule.
---

# Upgrade the existing Graphic Designer microsite

Repository: `breyhanaariel/graphic-designer`

Read and follow `.github/copilot-instructions.md` before making changes.

## Goal
Improve the existing Graphic Designer microsite. Do not rebuild it from scratch.

The microsite should serve:
- employers considering Brianna for full-time remote Graphic Designer, Brand Designer, Marketing Designer, or Visual Designer roles
- freelance clients looking for short-term graphic design services

## Technical constraints
- Keep the site plain HTML, CSS, and JavaScript.
- Preserve the existing `site/` structure.
- Preserve GitHub Pages compatibility.
- Reuse working code and existing components/patterns.
- Do not introduce React, Next.js, a build system, or unnecessary dependencies.

## Required homepage structure
Keep the homepage visually polished and easy to scan in this general order:
1. Hero / positioning
2. Featured Case Studies
3. Design Gallery
4. Core Stack
5. Services / freelance CTA
6. How I Work
7. Portfolio Family
8. Contact / inquiry path

## Featured work
Preserve:
- Peach & Petal
- RibbonHQ
- Cherry Static

Keep their art directions distinct.

## Design Gallery
Preserve the one-page gallery model:
- dropdown selector only
- All Work
- Logo Design
- Mascot Design
- Brand Identity
- Illustration
- Print Design
- 10 images initially per category
- unlimited expansion later
- click thumbnail -> modal/lightbox on the same page
- modal includes project name, Client or Concept Client, category, description, tools, deliverables, and inquiry CTA
- do not create separate gallery detail pages

## Services
Keep `site/services.html` as the dedicated Services & Packages experience.

Make the path from portfolio -> services -> inquiry obvious without overwhelming the homepage.

## Artwork rule
Do not generate or source finished artwork to represent Brianna's work.

Current placeholders must remain obviously placeholders until Brianna replaces them with her manually created artwork.

Do not invent:
- real client relationships
- testimonials
- traffic
- conversion results
- campaign performance
- awards
- business outcomes

## Visual direction
Preserve Brianna's feminine/cozy portfolio wrapper:
- blush pink
- peach
- lavender
- cream
- soft rounded cards
- tasteful shadows
- bows, sparkles, hearts, flowers, and stars where appropriate
- emoji-forward labels
- Georgia-style serif display type + clean sans-serif support type

Keep the experience polished enough for recruiters and clients, not childish or cluttered.

## Accessibility and QA
Check:
- semantic structure
- keyboard navigation
- visible focus
- gallery filtering
- modal focus behavior
- Escape-to-close
- focus restoration
- responsive layouts
- mobile gallery
- form/inquiry links
- GitHub Pages-relative URLs
- reduced motion where relevant

## Deliverable
Make the improvements on a working branch and submit them as a pull request.

In the pull request summary include:
- what changed
- why it improves recruiter/client usability
- files changed
- accessibility checks performed
- any placeholders still waiting for Brianna's final artwork
- anything Brianna should manually verify after merge
