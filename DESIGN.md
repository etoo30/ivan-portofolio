---
name: Ivan Personal Portfolio
description: Editorial portfolio for Ivan Mulyanto, barista enthusiast and service professional.
colors:
  deep-navy: "#172536"
  navy-secondary: "#263747"
  slate-gray: "#66717D"
  slate-ink: "#536170"
  warm-off-white: "#F4F1EB"
  paper-white: "#FBFAF7"
  warm-sand: "#E9E6DF"
  light-gray: "#E5E4E0"
  neutral-rule: "#D2D0CA"
  coffee-accent: "#A77B54"
  coffee-ink: "#775534"
  warm-on-navy: "#D2B08D"
  text-dark: "#202A32"
typography:
  display:
    fontFamily: "Newsreader, Georgia, serif"
    fontSize: "clamp(2.875rem, 5.05vw, 4.375rem)"
    fontWeight: 400
    lineHeight: 0.99
    letterSpacing: "-0.035em"
  body:
    fontFamily: "DM Sans, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
rounded:
  sm: "0px"
spacing:
  xs: "8px"
  section: "clamp(5.625rem, 11vw, 9.75rem)"
components:
  button-primary:
    backgroundColor: "{colors.warm-off-white}"
    textColor: "{colors.deep-navy}"
    rounded: "{rounded.sm}"
    height: "48px"
    padding: "0 20px"
  button-primary-hover:
    backgroundColor: "{colors.paper-white}"
---

# Design System: Ivan Personal Portfolio

## Overview

**Creative North Star: “Editorial coffee portfolio.”**

The site reads like a considered hospitality profile: clean magazine typography, generous paper-colored space, and working coffee photographs. Navy carries the professional identity. Warm coffee brown appears sparingly as a marker for focus and interaction.

The first view pairs Ivan's introduction with an editorial photograph of espresso preparation. Career entries use a ruled timeline rather than repeated cards. No portrait is implied by the coffee photography; the current identity mark uses Ivan's initials until an original portrait is supplied.

**Key Characteristics:**

- Modern editorial composition with an asymmetric split hero.
- Navy and warm off-white as the main surfaces.
- Coffee accent used sparingly.
- Serif headlines with a direct sans-serif reading face.
- Photos illustrate the field, not Ivan's identity or work history.

## Colors

The palette balances the requested navy identity with a warm paper ground and a restrained coffee accent.

### Primary
- **Deep navy** (#172536): Hero and education band, brand mark, primary text.
- **Navy secondary** (#263747): Supporting navy surfaces and secondary emphasis.

### Secondary
- **Coffee accent** (#A77B54): Eyebrow labels, fine markers, and small interaction details only.

### Neutral
- **Warm off-white** (#F4F1EB): Main reading surface.
- **Paper white** (#FBFAF7): Navigation and footer surface.
- **Light gray** (#E5E4E0): Secondary surface family.
- **Slate gray** (#66717D): Supporting copy and metadata.
- **Text dark** (#202A32): Main body text.

## Typography

**Display Font:** Newsreader (with Georgia fallback)  
**Body Font:** DM Sans (with Arial fallback)

**Character:** Newsreader supplies a human editorial voice without turning the profile into a café menu. DM Sans keeps work history and contact details clear at a glance.

### Hierarchy
- **Display** (400, 46–70px, 0.99 line-height): Hero headline.
- **Headline** (400, 40–74px, 1.02 line-height): Section titles.
- **Title** (400, 23–39px, 1.18 line-height): Experience roles and narrative emphasis.
- **Body** (400, 13–16px, 1.62–1.75 line-height): Profile, descriptions, and contact details.
- **Label** (500–600, 9–11px, 1.4 line-height, uppercase): Navigation context and section metadata.

## Layout

The wide layout uses a 1280px content maximum, equal outer gutters, and an asymmetric two-column editorial hero. About and skills pair copy with photography; experience uses a ruled list, while education and organization sit in a quiet two-column record. The contact close returns to a text-and-links split. At narrow widths, columns become a single readable sequence and navigation becomes a button-controlled menu.

Sections use generous vertical spacing. Text remains left-aligned; images keep a clear rectangular crop. At mobile sizes, the hero text precedes its image and career details stack without clipping.

## Elevation & Depth

The system is mostly flat. Contrast comes from paper, sand, and navy surfaces, not floating cards or shadows. Fine rules divide list entries. Photography provides the visual depth.

## Shapes

Buttons, image frames, and marks use square corners. Interaction targets remain at least 44px tall. Thin borders appear only as list dividers and structural edges.

## Components

- **Navigation:** Sticky off-white header; section anchors; mobile menu exposes `aria-expanded` and closes on link, outside click, or Escape.
- **Hero:** Dark navy split composition with factual introductory copy and a coffee-preparation photograph.
- **Experience list:** Three open rows with role, employer, short description, and supplied duration.
- **Contact links:** Three direct links to the approved WhatsApp number, email, and Instagram account.
- **Motion:** A restrained hero entrance and one-time section reveals; content remains visible with reduced motion or without JavaScript.

## Do's and Don'ts

- Keep every career claim anchored to supplied facts.
- Keep coffee photography clearly separate from Ivan's identity.
- Keep the warm paper ground and navy identity dominant.
- Do not add skill percentages, fabricated achievements, certificates, projects, or profile links.
- Do not publish TikTok or public location details.
- Do not repeat identical cards as the page's main structure.
