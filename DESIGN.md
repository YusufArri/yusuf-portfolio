---
name: "Yusuf A. Portfolio"
description: "A warm, welcoming executive portfolio for a full-stack freelancer."
colors:
  warm-navy: "#14213d"
  deep-navy: "#101c34"
  soft-navy: "#1d2a45"
  paper: "#fbfaf7"
  white: "#ffffff"
  electric-blue: "#315efb"
  radial-blue: "#5578ff"
  blue-light: "#dce5ff"
  slate: "#61708a"
  fine-line: "#d7deea"
typography:
  display:
    fontFamily: "Trebuchet MS, Segoe UI, Arial, sans-serif"
    fontSize: "clamp(3rem, 5.4vw, 5.4rem)"
    fontWeight: 800
    lineHeight: 1.01
    letterSpacing: "-0.045em"
  headline:
    fontFamily: "Trebuchet MS, Segoe UI, Arial, sans-serif"
    fontSize: "clamp(2.2rem, 4vw, 4rem)"
    fontWeight: 800
    lineHeight: 1.04
    letterSpacing: "-0.045em"
  title:
    fontFamily: "Trebuchet MS, Segoe UI, Arial, sans-serif"
    fontSize: "clamp(1.35rem, 2vw, 1.75rem)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.03em"
  body:
    fontFamily: "Trebuchet MS, Segoe UI, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Trebuchet MS, Segoe UI, Arial, sans-serif"
    fontSize: "0.76rem"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0.04em"
rounded:
  sm: "0.2rem"
  md: "0.25rem"
  lg: "0.35rem"
spacing:
  xs: "0.38rem"
  sm: "0.75rem"
  md: "1.35rem"
  lg: "2rem"
  xl: "3rem"
  section: "clamp(4.5rem, 8vw, 7rem)"
components:
  navigation:
    backgroundColor: "{colors.warm-navy}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    height: "80px"
  button-primary:
    backgroundColor: "{colors.electric-blue}"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0.75rem 1.05rem"
    height: "53.6px"
  button-primary-hover:
    backgroundColor: "#234be1"
    textColor: "{colors.white}"
  button-outline:
    backgroundColor: "rgb(255 255 255 / 3%)"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0.75rem 1.05rem"
  button-paper:
    backgroundColor: "{colors.white}"
    textColor: "{colors.warm-navy}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0.75rem 1.05rem"
  capability-card:
    backgroundColor: "rgb(255 255 255 / 5%)"
    textColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: "1.15rem 1.25rem"
  service-tag:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.warm-navy}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "0.42rem 0.65rem"
  project-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.warm-navy}"
    rounded: "{rounded.lg}"
    padding: "1.35rem"
  skill-label:
    backgroundColor: "rgb(255 255 255 / 6%)"
    textColor: "{colors.white}"
    rounded: "{rounded.sm}"
    padding: "0.42rem 0.65rem"
---

# Design System: Yusuf A. Portfolio

## Overview

**Creative North Star: "The Welcoming Executive Portfolio"**

The system presents Yusuf A. as a composed, credible, and approachable full-stack freelancer. Warm navy establishes authority, warm paper keeps the page human, and electric blue supplies precise moments of action and wayfinding. Subtle radial blue warmth behind the opening prevents the corporate structure from feeling stark, while strong editorial hierarchy, fine borders, measured depth, and short explanatory copy keep it professional.

The portfolio puts proven skills and completed job types immediately in view. The hero lead is paired with visible HTML/CSS, JavaScript, React, and Python/FastAPI chips and a structured capability panel. The portfolio uses a staged reveal and subtle horizontal or vertical lifts to maintain momentum without turning the interface into a playful display. Imagery remains typographic and symbolic because suitable project screenshots are not available; project status and caveats stay explicit.

**Key Characteristics:**
- Warm-navy editorial hero with subtle blue radial warmth and warm-white content areas
- Hero skills and completed capability types visible in the first viewport
- Electric-blue action, links, and focused wayfinding
- Fine 1px borders and restrained 0.2–0.35rem radii
- Elevated cards and hover lift that communicate interaction
- Evidence-first project records and a direct Freelancer-profile path

## Colors

The palette is a professional navy, paper, and electric-blue system with cool neutral dividers.

### Primary
- **Warm Navy** (`#14213d`): hero, about field, navigation text, primary headlines, and footer surfaces.
- **Electric Blue** (`#315efb`): primary actions, project categories, active links, hover accents, and focused wayfinding.

### Secondary
- **Radial Blue** (`#5578ff`): low-key blue warmth behind the hero rather than a decorative flat banner.
- **Blue Light** (`#dce5ff`): pale blue CTA hover and cool tonal field.

### Neutral
- **Warm Paper** (`#fbfaf7`): default warm page surface and service tags.
- **White** (`#ffffff`): project cards, contact area, and reversed text surfaces.
- **Deep Navy** (`#101c34`): hero depth and the dark footer.
- **Slate** (`#61708a`): secondary copy and project metadata.
- **Fine Line** (`#d7deea`): navigation, card, service-row, and caveat borders.

**The Evidence-First Color Rule.** Color must organize hierarchy and action; it must not imply a project outcome, review, integration, or unverified status.

## Typography

**Display Font:** Trebuchet MS, followed by Segoe UI and Arial
**Body Font:** Trebuchet MS, followed by Segoe UI and Arial
**Label Font:** Trebuchet MS, bold and compact

**Character:** The family is direct, warm, and highly scannable. Large weights establish executive confidence, while moderate body leading keeps project caveats and service explanations readable.

### Hierarchy
- **Display** (800, 3–5.4rem clamp, 1.01 line-height): hero promise and the largest opening statement.
- **Headline** (800, 2.2–4rem clamp, 1.04 line-height): section, about, and contact headings.
- **Title** (800, 1.35–1.75rem clamp, 1.15 line-height): service and project titles.
- **Body** (400, 1rem, 1.6 line-height): paragraphs and utility copy.
- **Label** (800, 0.72–0.78rem, 1.2 line-height, 0.04em tracking): tags, metadata, capability labels, and navigation utility copy.

**The Readable Authority Rule.** Headlines remain bold and spacious, but never become oversized decoration. Skills and completed job types stay visible in the opening, while explanatory copy remains compact, practical, and limited to clear line lengths.

## Layout

The page is a centered Bootstrap container with a warm-navy opening, then warm-paper, cool-work, dark-about, and white-contact fields. The hero uses a `1.25fr` copy column and `0.75fr` capability panel at desktop. Section padding is `clamp(4.5rem, 8vw, 7rem)`.

Desktop project cards use three columns. At `991.98px` and below they become two columns with the final card spanning both. Below `767.98px` they become one column. The two-column section-heading and about layouts collapse to one column at the mobile breakpoint. At `380px` and below the hero title is fixed at `2.5rem`, capability-card columns tighten, and hero actions stack full-width.

**The Proof-Then-Action Rule.** The narrative moves from the offer, to service categories, to three honest project records, to Yusuf's profile and skills, and finally to a direct Freelancer conversation.

## Elevation & Depth

Depth is hybrid: open surfaces rely on warm tonal shifts, subtle blue radial atmosphere, and fine borders, while controls and cards use measured shadows only for lift and state. The fixed navigation uses a translucent cool-paper field with `backdrop-filter: blur(10px)`.

### Shadow Vocabulary
- **Nav Shrunk** (`0 8px 24px rgb(16 27 51 / 8%)`): compact fixed navigation separation.
- **Primary Action** (`0 10px 24px rgb(49 94 251 / 20%)`): blue primary-button confidence.
- **Primary Hover** (`0 13px 28px rgb(49 94 251 / 30%)`): stronger directional response on action.
- **Card Rest** (`0 10px 28px rgb(16 27 51 / 6%)`): restrained project-card separation.
- **Card Hover** (`0 18px 38px rgb(16 27 51 / 12%)`): pointer and keyboard-focus emphasis.

**The Lift-Only Rule.** Shadows appear only on controls, cards, and the compact navigation state; neutral containers remain flat.

## Shapes

The system uses restrained, small-radius forms rather than fully square or pill-shaped surfaces. Buttons use `0.25rem`, tags and caveats `0.2rem`, and cards or capability panels `0.35rem`. Borders are consistently `1px`, and project or service areas use border-backed separation rather than decorative outlines.

The only circular form is the Circle of Friends typographic mark. It is an illustrative geometric asset, not a repeated UI component.

**The Fine-Border Rule.** Use borders to define hierarchy and state; do not compensate with heavy outlines or excessive corner radius.

## Components

### Navigation
- **Character:** A crisp fixed wordmark strip that becomes slightly smaller and more defined after scroll; it stays restrained rather than opaque or decorative.
- **Style:** 80px desktop navigation, cool translucent paper field, fine line border, and `backdrop-filter: blur(10px)`.
- **States:** Navigation links use electric-blue text and a 2px underline on hover or active state; the Hire action is navy-to-blue in state.
- **Mobile:** At `991.98px` and below, links align within the Bootstrap collapse and the Hire action becomes an inline compact button.

### Buttons
- **Shape:** `0.25rem` radius, `1px` border, `53.6px` minimum height, and `0.75rem 1.05rem` padding.
- **Primary:** Electric-blue fill and white text with a measured blue shadow.
- **Outline:** Translucent navy/white field with a 35% white border on the hero; hover flips to white fill and navy text.
- **Paper:** White fill and navy text for the final contact action.
- **Hover / Focus:** Move `-3px` vertically and increase or change shadow/border. Keyboard focus uses the established visible focus ring.
- **Motion:** `180ms ease-out` for transform, shadow, border, and background transitions.

### Capability Cards
- **Style:** Navy hero panel at 5% white transparency, `1px` blue-white line, `0.35rem` radius, and `7.75rem` minimum height.
- **Composition:** Numeric label column plus title and concise support copy.
- **Hover:** Shift `8px` horizontally and strengthen border/background opacity.

### Hero Skill Chips
- **Style:** 6% white fill, 24% pale-blue border, `0.2rem` radius, `0.38rem 0.58rem` padding, and 0.76rem bold text.
- **Placement:** Four compact chips appear directly beneath the hero description and above the actions.
- **Character:** White/pale-blue type makes technical capability immediately readable without competing with the offer.

### Service Rows and Tags
- **Rows:** Grid-separated with fine top/bottom borders and an `8px` horizontal lift on hover.
- **Tags:** Warm-paper fill, navy text, `1px` fine-line border, `0.2rem` radius, and `0.42rem 0.65rem` padding.

### Project Cards
- **Corner Style:** `0.35rem` radius.
- **Structure:** `13rem` typographic illustration, fine divider, then flex-driven copy.
- **Original SVG Imagery:** Project artwork uses original inline SVG compositions: ShopFlix combines a storefront/window motif, Circle uses linked rings, and Pinned! uses a pin-and-grid mark. These are bespoke evidence-safe illustrations rather than claimed screenshots or generic theme assets.
- **Background:** White card with fine line border and card-rest shadow.
- **Hover:** Raise `8px`, strengthen the blue-gray border, and deepen shadow.
- **Evidence:** Status labels and caveats remain explicit text; Pinned! has no repository link.

### Skills
- **Style:** Compact wrapping labels on navy, using 6% white fill and 18% white border.
- **Hover:** Lift `3px` and strengthen the pale-blue border.

## Do's and Don'ts

### Do:
- **Do** lead with a warm-navy hero and a bold, approachable business offer.
- **Do** use electric blue sparingly for actions, active states, categories, and wayfinding.
- **Do** keep borders at `1px`, radii at `0.2–0.35rem`, and shadows restrained.
- **Do** use staged `620ms` reveal motion with the existing 18px translate and honor reduced-motion settings.
- **Do** preserve the verified ShopFlix and Circle repositories and the Freelancer-profile contact route.
- **Do** label ShopFlix as a prototype and Pinned! as a demo.

### Don't:
- **Don't** restore shop-window language, sun-yellow fields, hand-painted signs, or condensed poster typography.
- **Don't** add saturated decorative accents or use color to imply outcomes that are not evidenced.
- **Don't** round surfaces into pills or apply glossy gradients and ambient card depth.
- **Don't** invent reviews, testimonials, platform ratings, production integrations, or project screenshots.
- **Don't** link Pinned! to the unavailable GitHub URL or present it as a production service.
