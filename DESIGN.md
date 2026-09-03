---
name: The Cloud-Pink Workbench
description: A concise, cloud-pink GitHub Profile README connecting perception, robotics, and embedded practice.
colors:
  cloud-pink: "#FE428E"
  soft-cloud-pink: "#D8759B"
typography:
  typing-svg:
    fontFamily: "Fira Code"
    fontSize: "24px"
    fontWeight: 600
---

# Design System: The Cloud-Pink Workbench

## Overview

**Creative North Star: "The Cloud-Pink Workbench / 粉色云端工作台"**

This GitHub Profile README feels like a compact workbench in the cloud: personal enough to remember, technical enough to trust, and organized around four focus areas and current activity. Cloud Pink provides the identity while GitHub-native Markdown keeps the profile direct, familiar, and maintainable.

The system is intentionally restrained. It uses a single reading order, a few purposeful remote graphics, and one service-rendered technology strip instead of an ornamental card wall. This design system governs only the GitHub Profile README and future profile-specific additions; it does not govern the linked Astro website.

**Key Characteristics:**

- One memorable Cloud Pink accent within a GitHub-native surface.
- A mobile-first, single-column narrative from identity to contact.
- Compact badges, one technology icon strip, and one informative activity card.
- Bilingual content that reads as one profile rather than duplicated translations.
- Accessible image alternatives and color-scheme-aware contribution artwork.

## Colors

The palette uses one vivid authored accent and one softer tonal expression; GitHub and the embedded services own every neutral, surface, and text color around it.

### Primary

- **Cloud Pink** (`#FE428E`): identifies the profile-view badge and website touchpoints. Use it as a recognizable thread, not as a full-page fill or a substitute for labels.
- **Soft Cloud Pink** (`#D8759B`): a muted, romantic pink reserved for the typing introduction. Its lower saturation keeps the opening line gentle while retaining large-text contrast on GitHub's light and dark surfaces.

### Named Rules

**The Tonal Pink Rule.** Cloud Pink remains the profile's authored brand accent; Soft Cloud Pink may appear only in the typing introduction as its quieter tonal expression. Do not invent additional supporting palettes or copy service-owned radical-theme colors into the token set.

## Typography

**Display Font:** GitHub-native Markdown typography
**Body Font:** GitHub-native Markdown typography
**Label/Mono Font:** Fira Code, inside the typing SVG only

**Character:** The profile inherits GitHub's familiar reading typography. Fira Code adds a brief technical signal in the animated introduction without becoming a site-wide typeface.

### Hierarchy

- **Profile title** (GitHub-native): The centered HTML heading introduces the person before any data visualization.
- **Section headline** (GitHub-native): Markdown `##` headings use bilingual labels joined by a middle dot.
- **Body** (GitHub-native): Paragraph, list, link, emphasis, inline-code, and blockquote styles inherit from the host.
- **Typing label** (Fira Code, weight 600, 24px): Limited to the introductory typing SVG.

### Named Rules

**The Host Typography Rule.** Let GitHub control Markdown font families, sizes, line heights, and neutral colors; never fabricate CSS typography tokens for values the profile does not own.

## Layout

The profile follows one mobile-first reading order: introduction, about, technology stack, activity, contribution history, and contact. It does not introduce authored breakpoints, grids, or desktop-only columns.

Center alignment is reserved for compact visual moments: the opening identity, technology icon strip, activity card, contribution snake, contact badges, and signature. Explanatory copy stays in normal Markdown flow for scanning. Remote images must remain able to shrink within GitHub's content column; the typing graphic declares a 600-pixel service canvas and the activity card declares a 390-pixel width, but neither establishes a page breakpoint.

### Named Rules

**The One-Column Rule.** Every addition must make sense in the same top-to-bottom order on a narrow screen; do not create parallel columns that require a desktop viewport to understand.

## Elevation & Depth

The profile is flat by default and defines no custom shadows or layered surfaces. Any depth inside the radical-theme activity graphic belongs to that external card's artwork, not to a reusable profile elevation token.

### Named Rules

**The Flat-by-Default Rule.** Use spacing, headings, and content order for hierarchy; do not assemble a wall of decorative cards or add cosmetic shadows around Markdown sections.

## Shapes

The profile defines no radius or border scale. Badges retain the compact silhouettes supplied by their services, while larger SVG artwork remains rectangular and borderless. Do not infer a general component shape language from remote image rendering.

### Named Rules

**The Service-Native Shape Rule.** Preserve the established badge and image forms; do not invent wrappers, frames, or rounded containers around them.

## Components

### Typing Introduction

- **Role:** A centered personal line — “如果你感觉悲伤，我就陪你晒太阳” — that gives the technical profile a warm, memorable voice.
- **Style:** Soft Cloud Pink Fira Code in the typing SVG, with centered horizontal and vertical alignment.
- **Accessibility:** The alternative text repeats the complete sentence without depending on the animation.

### Utility Badges

- **Role:** The opening profile-view and website links provide small pieces of status and navigation without delaying the biography.
- **Style:** Compact, flat service badges. Cloud Pink marks the profile-authored website relationship.
- **Behavior:** Each badge is wrapped in its real destination link and has concise alternative text.

### Technology Strip

- **Role:** A centered summary of the implemented toolset after the written focus areas.
- **Style:** One service-rendered icon strip with fourteen technologies arranged in a seven-icon grid rather than separated into individual cards.
- **Accessibility:** Alternative text names every technology shown.

### Activity Card

- **Role:** One compact summary of GitHub activity.
- **Style:** The external summary-card service uses its `radical` theme and is centered at a declared width of 390 pixels.
- **Constraint:** Add no second statistics card unless it contributes distinct, maintainable information.

### Contribution Snake

- **Role:** A single playful visualization of contribution history after the factual activity summary.
- **Behavior:** A `picture` element selects the dark or light SVG from the generated `output` branch according to the visitor's preferred color scheme, with a light fallback image.
- **Accessibility:** The fallback image carries meaningful alternative text.

### Contact Badges

- **Role:** End-of-profile actions for GitHub and the personal homepage.
- **Style:** Centered service badges with recognizable GitHub and Astro marks; Cloud Pink is reserved for the homepage action.

## Do's and Don'ts

### Do:

- **Do** keep identity and focus areas understandable before any activity visualization.
- **Do** preserve the single mobile-first reading order for every future profile section.
- **Do** use Cloud Pink consistently for authored identity and website touchpoints.
- **Do** give every image meaningful alternative text and keep essential facts available as text.
- **Do** serve contribution artwork through the existing light/dark `picture` pattern.
- **Do** keep the technology strip's alternative text synchronized with every icon shown.

### Don't:

- **Don't** apply this system to the linked Astro website; it is scoped to the GitHub Profile README.
- **Don't** add an ornamental card wall, redundant statistics, or unverified dynamic services.
- **Don't** invent GitHub neutral colors, typography values, spacing scales, radii, or breakpoints.
- **Don't** use Fira Code outside the typing SVG.
- **Don't** rely on Cloud Pink alone to communicate meaning.
- **Don't** let an image failure remove the profile's core identity, focus areas, or contact paths.
