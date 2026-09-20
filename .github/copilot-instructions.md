# GitHub Copilot Instructions — Graphic Designer Portfolio

## Repository purpose
This repository is Brianna Dickenson's Graphic Designer portfolio. It serves two audiences:
1. Employers considering Brianna for full-time remote Graphic Designer, Brand Designer, Marketing Designer, or Visual Designer roles.
2. Freelance clients looking for short-term graphic design services.

## Existing architecture
Work with the existing repository. Do not rebuild the portfolio from scratch unless explicitly instructed.

- Keep the microsite as plain HTML, CSS, and JavaScript.
- Preserve the existing `site/` directory as the GitHub Pages source.
- Preserve the existing GitHub Pages deployment workflow unless there is a concrete reason to change it.
- Keep README and microsite coordinated but distinct:
  - README = quick recruiter/client overview.
  - Microsite = richer visual portfolio and freelance experience.
- Keep `services.html` as the dedicated Services & Packages page.
- Keep the Design Gallery on the main one-page portfolio.

## Visual identity
The portfolio wrapper should remain recognizably Brianna's personal brand:
- feminine, cozy, polished, playful
- blush pink, peach, lavender, cream, and other soft supporting tones
- rounded cards and soft depth
- emoji-forward section naming
- Georgia-style serif display typography paired with a clean sans-serif
- cute branded project names
- tasteful decorative details such as bows, sparkles, flowers, hearts, and stars

Do not force every project into the same art direction. The portfolio wrapper may be feminine/cozy while each case study demonstrates a substantially different visual style.

## Homepage priorities
Preserve this overall content hierarchy unless explicitly changed:
1. Hero / positioning
2. Featured Case Studies
3. Design Gallery
4. Core Stack
5. Services / freelance CTA
6. How I Work
7. Portfolio Family
8. Contact / inquiry path

## Featured case studies
Preserve these three core showcase projects:
- Peach & Petal — consumer brand identity + packaging
- RibbonHQ — B2B / corporate visual communications
- Cherry Static — integrated campaign + social + motion

They should collectively demonstrate:
- brand identity and packaging
- editorial / marketing / corporate communications
- campaign / social / motion design

Never invent real clients, testimonials, performance metrics, conversion rates, traffic, awards, or business results for concept work.

## Design Gallery
The gallery is intentionally simple and one-page.

Required categories:
- All Work
- Logo Design
- Mascot Design
- Brand Identity
- Illustration
- Print Design

Interaction rules:
- The dropdown is the only category selector / organizer.
- Display 10 images initially per selected category.
- The system must allow unlimited expansion later.
- Clicking an image opens a modal/lightbox over the same page.
- Do not navigate to separate project pages from gallery thumbnails.
- Modal information should support:
  - project/design name
  - Client or Concept Client
  - category
  - short description
  - tools used
  - deliverables
  - "Inquire About This Service" CTA
- The inquiry CTA should connect cleanly to the project inquiry flow.
- Keep the desktop gallery easy to scan; the current target is 5 columns x 2 rows where space permits.
- Keep the mobile gallery at 2 columns where practical.

## Artwork rule — critical
Brianna will create the final portfolio artwork manually.

DO NOT:
- generate fake finished artwork for the portfolio
- source random stock or AI artwork to impersonate Brianna's work
- present generated placeholder art as Brianna's finished work
- fabricate client work

DO:
- preserve clearly labeled placeholders until Brianna supplies final artwork
- make placeholder replacement easy
- keep image paths and data structures simple to update
- allow the Design Gallery cover SVG to later be updated with thumbnails of Brianna's real work

## Services & Packages
Keep a dedicated `site/services.html` experience.

The portfolio may support focused freelance services such as:
- logo design
- logo redesign
- mascot design
- brand identity
- illustration
- social media packages
- campaign creative
- presentations / marketing collateral
- print design
- packaging
- basic motion design

Current featured pricing shown in the Services & Packages cover includes:
- Logo Design — from $150
- Social Media Package — from $275
- Brand Identity — from $650
- Community Starter — $50

Treat prices as starting prices, not universal fixed quotes.

## Core Stack
Use "Core Stack" rather than "Core Capabilities" in the public README.

Public-facing skill emphasis:
- Adobe Photoshop
- Adobe Illustrator
- Adobe InDesign
- Adobe After Effects
- Figma
- Canva
- brand and identity systems
- campaign and marketing design
- mascot and illustration
- editorial and print
- presentations and digital design
- basic motion

Do not make "AI-Assisted Workflow" a headline capability.

## Accessibility and interaction quality
For all site changes:
- preserve semantic HTML
- ensure keyboard-accessible controls
- maintain visible focus states
- give images meaningful alt text
- make modals keyboard operable
- support Escape to close modals
- restore focus after modal close
- maintain responsive behavior
- avoid unnecessarily motion-heavy interactions
- respect reduced-motion preferences where motion is added

## Content integrity
- Clearly label fictional work as concept work.
- Clearly distinguish "Client" from "Concept Client."
- Do not invent outcomes, testimonials, endorsements, or metrics.
- Do not imply Brianna worked for a company when she did not.
- Keep recruiter/client copy concise, scannable, and evidence-focused.

## Portfolio family
Preserve links to Brianna's related portfolios:
- UI/UX Designer
- Front-End Developer
- Web Designer
- Graphic Designer

The Graphic Designer portfolio should feel like a sister site to the Web Designer portfolio while remaining discipline-specific.

## Before making architecture changes
Inspect the current repository first.
Reuse existing code and patterns wherever possible.
Do not replace working functionality simply to rewrite it.
Prefer focused improvements over reinvention.

## Verification checklist
Before considering a task complete:
- check internal links
- check GitHub Pages-relative paths
- test dropdown filtering
- test modal open/close behavior
- test keyboard interaction
- test inquiry links/forms
- test desktop and mobile layouts
- confirm placeholders remain clearly labeled
- confirm no fake client claims or fabricated results were introduced
- summarize what changed and why
