# Design System Inspired by Bewerbungs-Homepage

## 1. Visual Theme & Atmosphere

The Bewerbungs-Homepage design system embodies professional confidence with a modern, approachable aesthetic designed for career advancement. The palette combines deep teal foundations with vibrant orange accents, creating a dynamic tension between trustworthiness and energy. The atmosphere is clean, digital-first, and optimistic—reflecting the platform's mission to help professionals stand out through personalized application portfolios. Soft shadows, generous whitespace, and carefully calibrated contrast ensure accessibility while maintaining visual sophistication. The design communicates reliability, innovation, and opportunity through restrained elegance paired with strategic color emphasis.

**Key Characteristics**
- Deep teal primary foundation conveying professionalism and stability
- Vibrant orange accents driving engagement and call-to-action prominence
- Light, airy surfaces with subtle depth through selective shadowing
- Generous padding and breathing room supporting content focus
- Modern sans-serif typography balancing warmth with clarity
- Accessible contrast ratios prioritizing readability across all interface states

## 2. Color Palette & Roles

### Primary
- **Deep Teal** (`#0D5152`): Primary brand color for headers, navigation backgrounds, and structural elements; conveys trust and professional authority
- **Teal Accent** (`#1F5F60`): Secondary teal for hover states, depth variations, and secondary interface elements
- **Teal Highlight** (`#179597`): Tertiary teal for interactive element emphasis and accent borders

### Accent Colors
- **Vibrant Orange** (`#F68826`): Primary action button fill, hero call-to-action elements, and visual highlights
- **Orange Secondary** (`#F5821B`): Alternative orange for hover states and secondary action elements
- **Bright Orange** (`#FF8000`): Enhanced orange for prominent CTAs and accent overlays
- **Coral Orange** (`#FF6600`): Extreme accent for special emphasis states

### Interactive
- **Cyan Accent** (`#03A6A6`): Interactive element highlights, link emphasis, and interactive state indicators
- **Teal Interactive** (`#1F5F60`): Hover and focus states for teal-themed interactive elements

### Neutral Scale
- **Charcoal Text** (`#666666`): Primary body text and general content; provides strong readability
- **Mid-Gray** (`#898D96`): Secondary text, placeholder content, and supporting information
- **Dark Charcoal** (`2B2B2B`): High-contrast text for critical information and headings
- **Heavy Charcoal** (`#525254`): Alternative dark text for emphasis
- **Very Dark Gray** (`#333333`): Darkest neutral for maximum contrast scenarios

### Surface & Borders
- **Off-White** (`#F2FAFA`): Light surface background for cards and subtle section separation
- **Soft Teal Tint** (`#D3E6E4`): Light teal surface for accented backgrounds and bordered sections
- **Pure White** (`#FFFFFF`): Primary surface color for main content areas and cards

### Semantic / Status
- **Warning Yellow** (`#EFBC23`): Warning and alert states requiring user attention
- **Alert Amber** (`#FCB900`): Alternative warning indicator for emphasis
- **Error Red** (`#CF2E2E`): Error states, critical messages, and destructive actions

## 3. Typography Rules

### Font Family
**Primary:** Figtree, Segoe UI, Roboto, sans-serif
- Used for all headings and body copy; provides warmth and modern clarity

**Secondary:** Open Sans, Helvetica Neue, Arial, sans-serif
- Used for buttons, navigation, and UI labels; offers consistent technical precision

**Tertiary:** Plus Jakarta Sans, Figtree, sans-serif
- Used for prominent buttons and feature labels; adds contemporary energy

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|-----------------|-------|
| **Display / Hero** | Figtree | 57px | 700 | 72.96px | 0px | Large page headlines; primary visual entry point |
| **H1 / Page Title** | Figtree | 47.52px | 300 | 51.32px | 0px | Main section headlines; prominent emphasis |
| **H2 / Section Head** | Figtree | 23px | 600 | 27.6px | 0px | Subsection titles; strong hierarchy support |
| **H3 / Subsection** | Figtree | 21px | 700 | 25.2px | 0px | Tertiary headings; category labels |
| **Body / Paragraph** | Figtree | 15px | 300 | 40.8px | 0px | Primary reading text; comfortable line height for legibility |
| **Button / Label** | Open Sans | 24px | 500 | 40.8px | 0px | Primary button and navigation text; UI elements |
| **Button Emphasis** | Plus Jakarta Sans | 24px | 700 | 40.8px | 0px | High-priority button text; featured actions |
| **Small List / Meta** | Open Sans | 14px | 500 | 14px | 0px | List items, metadata, and compact information |
| **Span / Inline** | Open Sans | 24px | 500 | 0px | 0px | Inline emphasized text and callouts |

### Principles
- Generous line height (40.8px base) ensures comfortable reading and reduces cognitive load
- Weight distribution between 300–700 provides clear visual hierarchy without excessive variation
- Figtree primary font adds personality while maintaining professional appearance
- Open Sans secondary provides technical clarity for interactive and structural elements
- Smaller sizes (14–15px) paired with higher line heights maintain accessibility for all users
- Font sizes scale proportionally; jump 4–10px between hierarchy levels for clear distinction

## 4. Component Stylings

### Buttons

#### Primary Action Button
- **Background:** `#F68826`
- **Text Color:** `#FFFFFF`
- **Font:** Open Sans, 24px, weight 700
- **Padding:** `14px 41px`
- **Border Radius:** `25px`
- **Border:** `2px solid #F68826`
- **Box Shadow:** `rgba(254, 195, 0, 0.455) 0px 0px 0px 3.54px`
- **Height:** `72.80px`
- **Hover State:** Background `#F5821B`, shadow intensity +20%
- **Active State:** Background `#FF8000`, text opacity 0.95

#### Secondary Compact Button
- **Background:** `#F68826`
- **Text Color:** `#FFFFFF`
- **Font:** Open Sans, 15px, weight 600
- **Padding:** `4.5px 10.5px 4.5px 30px`
- **Border Radius:** `5px`
- **Border:** `2px solid #F68826`
- **Box Shadow:** `rgba(254, 195, 0, 0.455) 0px 0px 0px 3.54px`
- **Height:** `38.50px`
- **Hover State:** Background `#F5821B`, scale 1.02

#### Ghost Button (Transparent)
- **Background:** `rgba(0, 0, 0, 0)`
- **Text Color:** `#666666`
- **Font:** Open Sans, 24px, weight 500
- **Padding:** `160px 100px`
- **Border Radius:** `40px`
- **Border:** `0px none`
- **Box Shadow:** `none`
- **Height:** Auto (min 50px)
- **Hover State:** Background `#F2FAFA`, text color `#0D5152`

#### Teal Section Button
- **Background:** `#0D5152`
- **Text Color:** `#666666`
- **Font:** Open Sans, 24px, weight 500
- **Padding:** `25px 100px`
- **Border Radius:** `40px`
- **Border:** `0px none`
- **Box Shadow:** `none`
- **Height:** `173.75px`
- **Hover State:** Background `#1F5F60`, text color `#FFFFFF`

### Cards & Containers

#### Feature Card
- **Background:** `#FFFFFF`
- **Border:** `0px none`
- **Border Radius:** `8px`
- **Padding:** `24px 24px`
- **Box Shadow:** `rgba(0, 0, 0, 0.08) 0px 2px 8px`
- **Text Color:** `#666666`
- **Font:** Figtree, 15px, weight 300, line-height 40.8px
- **Hover State:** Shadow `rgba(0, 0, 0, 0.12) 0px 4px 12px`, background `#F2FAFA`

#### Light Teal Surface Card
- **Background:** `#D3E6E4`
- **Border:** `0px none`
- **Border Radius:** `8px`
- **Padding:** `28px 28px`
- **Box Shadow:** `none`
- **Text Color:** `#0D5152`
- **Font:** Figtree, 15px, weight 300
- **Heading Font:** Figtree, 23px, weight 600

#### Content Container
- **Background:** `#FFFFFF` or `#F2FAFA`
- **Max Width:** `1296px`
- **Margin:** `0 auto`
- **Padding:** `40px 52px`
- **Border Radius:** `0px` (full-width sections) or `8px` (contained cards)

### Inputs & Forms

#### Text Input
- **Background:** `#FFFFFF`
- **Border:** `1px solid #D3E6E4`
- **Border Radius:** `5px`
- **Padding:** `12px 16px`
- **Font:** Figtree, 15px, weight 300
- **Text Color:** `#666666`
- **Placeholder Color:** `#898D96`
- **Focus State:** Border `2px solid #03A6A6`, box shadow `rgba(3, 166, 166, 0.1) 0px 0px 0px 3px`
- **Error State:** Border `2px solid #CF2E2E`, background `rgba(207, 46, 46, 0.05)`

#### Form Label
- **Font:** Figtree, 15px, weight 600
- **Color:** `#2B2B2B`
- **Margin Bottom:** `8px`
- **Required Indicator:** Color `#CF2E2E`

### Navigation

#### Main Navigation
- **Background:** `#0D5152`
- **Font:** Open Sans, 24px, weight 500
- **Text Color:** `#FFFFFF`
- **Padding:** `16px 24px`
- **Border Bottom:** `2px dotted #D3E6E4`
- **Height:** `30px` (minimum, with padding)

#### Navigation Link
- **Color:** `#FFFFFF`
- **Font:** Open Sans, 24px, weight 500
- **Padding:** `12px 20px`
- **Border Radius:** `0px`
- **Hover State:** Background `rgba(255, 255, 255, 0.1)`, color `#F68826`
- **Active State:** Color `#F68826`, border-bottom `3px solid #F68826`

#### Footer Link
- **Color:** `#D3E6E4`
- **Font:** Figtree, 16px, weight 300
- **Padding:** `0px`
- **Hover State:** Color `#FFFFFF`, text-decoration `underline`

### Links

#### Text Link (Inline)
- **Color:** `#F5821B`
- **Font:** Open Sans, 24px, weight 500
- **Text Decoration:** `none`
- **Hover State:** Color `#F68826`, text-decoration `underline`
- **Active State:** Color `#FF8000`

#### Ghost Link (Subtle)
- **Color:** `#D3E6E4`
- **Font:** Figtree, 16px, weight 300
- **Padding:** `0px`
- **Hover State:** Color `#03A6A6`

### Badges & Status Indicators

#### Warning Badge
- **Background:** `#EFBC23`
- **Text Color:** `#FFFFFF`
- **Font:** Open Sans, 12px, weight 600
- **Padding:** `4px 12px`
- **Border Radius:** `20px`

#### Error Badge
- **Background:** `#CF2E2E`
- **Text Color:** `#FFFFFF`
- **Font:** Open Sans, 12px, weight 600
- **Padding:** `4px 12px`
- **Border Radius:** `20px`

## 5. Layout Principles

### Spacing System

**Base Unit:** `4px`

**Spacing Scale (multiples of 4px):**
- `4px` (xs) – Internal micro-spacing, tight component gaps
- `8px` (sm) – Small component padding, list item spacing
- `12px` (base) – Standard margin between elements
- `16px` (md) – Card padding, section gutters
- `20px` (lg) – Block-level margins, medium gaps
- `24px` (xl) – Card padding, section separation
- `28px` (xxl) – Large container padding
- `32px` (3xl) – Major section margins
- `36px` (4xl) – Section separation, hero spacing
- `40px` (5xl) – Main container padding
- `44px` (6xl) – Large spacing between major sections
- `52px` (7xl) – Content area padding
- `56px` (8xl) – Full-width section padding

**Usage Context:**
- Button padding: `4px`, `12px`, `14px`, `30px` (custom)
- Card padding: `24px`, `28px`
- Section padding: `40px`, `52px`
- Margins between blocks: `20px`, `32px`, `36px`, `44px`

### Grid & Container

- **Max Width:** `1296px` (primary content container)
- **Full Width:** `1440px` (sections, hero areas)
- **Grid Columns:** 12-column implicit grid for responsive layouts
- **Gutter Width:** `16px` to `24px` between columns
- **Section Pattern:** Full-width background color with centered max-width content container
- **Alignment:** Center-aligned content with left/right padding symmetry

### Whitespace Philosophy

Generous whitespace is fundamental to the design system. Content breathes through strategic padding (minimum 16px internal, often 24px–52px for major sections). Sections stack vertically with 36px–44px gaps, creating clear visual separation without overwhelming density. Cards float in negative space, emphasizing content hierarchy. Margins and padding consistently use the 4px scale, ensuring predictable rhythm. This approach reduces cognitive load, improves scanning, and elevates perceived quality.

### Border Radius Scale

- `0px` – Structural elements, full-width sections, edge-to-edge content
- `5px` – Compact buttons, small interactive elements, input fields
- `8px` – Card containers, panels, and moderate-sized components
- `25px` – Large prominent buttons with balanced proportions
- `40px` – Oversized ghost buttons, hero-scale interactive areas

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| **Base** | No shadow | Flat backgrounds, text, semantic surfaces |
| **Sm** | `rgba(10, 10, 10, 0.15) 0px 12px 18px -6px` | Dropdown menus, subtle elevation |
| **Md** | `rgba(0, 0, 0, 0.1) 0px 0px 15px 0px` | Modals, overlays, moderate lift |
| **Lg** | `rgba(254, 195, 0, 0.455) 0px 0px 0px 3.54px` | Primary buttons, high-emphasis CTAs |
| **Hover** | Base shadow +20% opacity | Interactive element elevation on interaction |

**Shadow Philosophy:**

Depth is intentionally restrained. The system employs three primary shadow treatments: dropdowns use soft downward shadows for subtle elevation, modals apply diffuse shadows for prominent lift, and buttons feature golden-yellow glow shadows to emphasize primary actions. This selective approach prevents visual clutter while creating clear spatial hierarchy. Hover states intensify shadows by 20% opacity, providing tactile feedback without dramatic shifts. All shadows use neutral dark bases except primary buttons, which employ warm golden accents matching the brand's action color.

## 7. Do's and Don'ts

### Do
- Use deep teal (`#0D5152`, `#1F5F60`) as the structural foundation for headers, backgrounds, and trust-building elements
- Apply vibrant orange (`#F68826`) exclusively to call-to-action buttons and primary interactive elements
- Maintain minimum 16px padding around content; use 24px+ for card and section interiors
- Pair Figtree (headings/body) with Open Sans (buttons/UI) to balance warmth and clarity
- Follow the typography hierarchy strictly: jump 4–10px between heading levels, maintain 40.8px line height for body text
- Use the 4px spacing scale consistently; all margins and padding should be multiples of 4
- Apply soft shadows (sm/md) to cards and dropdowns; reserve golden glow (lg) for primary buttons only
- Ensure text color contrast meets WCAG AA standards (minimum 4.5:1 for body text)
- Use cyan (`#03A6A6`) strategically for interactive focus states and link highlights
- Provide clear visual distinction between component states: default, hover, active, focus, disabled

### Don't
- Mix primary and accent colors on the same button; reserve teal for structural elements, orange for actions
- Use the neutral gray palette (`#666666`) as a background; reserve it for text and secondary elements
- Create padding smaller than 12px for interactive elements; maintain comfortable touch targets (minimum 44px height)
- Nest shadows (avoid multiple box-shadow layers); apply only one shadow per element
- Use the warning colors (`#EFBC23`, `#CF2E2E`) for general emphasis; reserve semantic colors for status states
- Deviate from the Figtree/Open Sans font pairing without design system approval
- Apply border radius inconsistently; use 5px for compact components, 8px for cards, 25px+ only for large buttons
- Place body text on dark backgrounds without adequate light contrast; maintain 4.5:1 minimum ratio
- Scale typography unpredictably; always reference the hierarchy table for size/weight combinations
- Forget generous whitespace; at minimum, maintain 16px gutters between major content sections

## 8. Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|------|-------|------------|
| **Mobile** | < 640px | Single column, 16px padding, 20px margins, nav collapses to hamburger, font size -1–2px for body |
| **Tablet** | 640px – 1024px | Two columns, 24px padding, 28px margins, nav expands, moderate font scale |
| **Desktop** | 1024px – 1440px | Three+ columns, 40px+ padding, full nav, maximum readability |
| **Large Desktop** | > 1440px | Content constraint to 1296px max, centered layout, full spacing scale applied |

### Touch Targets

- **Minimum Height:** `44px` for all interactive elements (buttons, inputs, links)
- **Minimum Width:** `44px` for standalone icons and small buttons
- **Padding Around Targets:** `8px` minimum between adjacent interactive elements
- **Text Link Height:** `40.8px` (line-height) ensures sufficient tap area without explicit height
- **Button Padding Vertical:** `12px` minimum for comfortable thumb/finger interaction

### Collapsing Strategy

**Mobile (< 640px):**
- Stack all layout columns vertically
- Reduce padding from 52px to 20px; margins from 44px to 24px
- Collapse navigation into hamburger menu; display full-height overlay on activation
- Font sizes remain consistent; line heights provide touch-friendly spacing
- Hero sections scale to single image column + stacked text
- Buttons expand to full width within content containers

**Tablet (640px – 1024px):**
- Two-column layouts for cards and feature sections
- Padding reduces to 28px; margins to 32px
- Navigation shows abbreviated labels or icons
- Typography size stable; adjust line-height to 38px for compact displays
- Images and content blocks reflow into two-column grids

**Desktop (1024px+):**
- Three+ column layouts unlock
- Padding and margins reach full scale (40px–52px)
- Full navigation with all labels visible
- Typography at full specified sizes
- Horizontal spacing maximized for breathing room
- Content container constrained to 1296px max-width, centered

## 9. Agent Prompt Guide

### Quick Color Reference

- **Primary CTA:** Vibrant Orange (`#F68826`) – All primary action buttons and hero highlights
- **Background (Hero/Primary):** Deep Teal (`#0D5152`) – Navigation, headers, major structural sections
- **Background (Secondary):** Teal Accent (`#1F5F60`) – Alternative sections, hover states, depth variation
- **Surface (Light):** Off-White (`#F2FAFA`) – Card backgrounds, subtle section separation
- **Surface (Accent):** Soft Teal Tint (`#D3E6E4`) – Accented backgrounds, bordered sections, light emphasis
- **Body Text:** Charcoal (`#666666`) – Primary paragraph and content text
- **Heading Text:** Dark Charcoal (`#2B2B2B`) – Section titles and prominent labels
- **Supporting Text:** Mid-Gray (`#898D96`) – Secondary information, placeholders, metadata
- **Interactive Accent:** Cyan (`#03A6A6`) – Focus states, link highlights, interactive indicators
- **Warning/Alert:** Warning Yellow (`#EFBC23`) – Warning badges, non-critical alerts
- **Error/Danger:** Error Red (`#CF2E2E`) – Error states, critical messages, destructive actions

### Iteration Guide

1. **Color Foundation:** Deep Teal (`#0D5152`) is the primary brand color appearing in 108+ instances—use it for all navigation backgrounds, page headers, and structural containers. Vibrant Orange (`#F68826`) appears 28 times exclusively for primary CTAs; reserve this color only for primary action buttons.

2. **Typography Consistency:** All body text uses Figtree 15px, weight 300, line-height 40.8px. Headings use Figtree with progressive weight/size: H1 = 47.52px/300, H2 = 57px/700, H3 = 23px/600. Buttons and UI labels use Open Sans 24px, weight 500–700. Never deviate from these values without explicit design approval.

3. **Spacing Discipline:** Every margin and padding must be a multiple of 4px. Base card padding = 24–28px. Section padding = 40–52px. Spacing between major sections = 32–44px. Use the scale provided; custom values create inconsistency and break the rhythm.

4. **Shadow Application:** Apply sm shadow (`rgba(10, 10, 10, 0.15) 0px 12px 18px -6px`) to dropdowns and subtle elevations. Apply golden glow (`rgba(254, 195, 0, 0.455) 0px 0px 0px 3.54px`) exclusively to primary buttons (`#F68826`). Do not layer multiple shadows; cards use md or no shadow.

5. **Component Styling Precision:** Primary buttons = `#F68826` background, `#FFFFFF` text, 24px Open Sans, weight 700, padding `14px 41px`, radius `25px`. Compact secondary buttons = `#F68826` background, `#FFFFFF` text, 15px Open Sans, weight 600, padding `4.5px 10.5px 4.5px 30px`, radius `5px`. Ghost buttons = transparent background, `#666666` text, radius `40px`.

6. **Neutral Hierarchy:** `#2B2B2B` is the darkest text color for maximum contrast and critical information. `#666666` is the standard body text color (appears 381+ times). `#898D96` is for secondary/supporting information. `#D3E6E4` (light teal) is for accented surfaces. Never reverse this hierarchy; it ensures consistent readability.

7. **Interactive States:** Hover states increase shadow opacity by ~20% and shift background color deeper in the palette (e.g., `#F68826` → `#F5821B`). Focus states apply `2px solid` border in accent color (`#03A6A6`) with subtle glow. Active states deepen color further (`#FF8000`) or reduce opacity. Disabled states use `#898D96` text with 50% opacity background.

8. **Responsive Scaling:** Mobile layouts (< 640px) reduce padding to 16–20px and stack all columns vertically. Tablet (640–1024px) uses two-column grids with 24–28px padding. Desktop (1024px+) unlocks three+ columns with full 40–52px padding. Max content width = 1296px on large displays. Always maintain minimum 44px touch targets for buttons and interactive elements.

9. **Accessibility Baseline:** Text contrast must meet WCAG AA standards (4.5:1 minimum for body text, 3:1 for UI components). Body text uses 15px minimum size with 40.8px line-height to ensure readability. Interactive elements require minimum 44px height. Links use color + underline on hover (not color alone). All form inputs include visible focus state and label association.

10. **Brand Voice in Design:** The design system balances professional authority (deep teal, refined typography) with approachable energy (vibrant orange, generous whitespace). Every component should feel confident yet welcoming. Use the full color palette; avoid monotone designs. Ensure high contrast between interactive elements and passive backgrounds. Generous padding and breathing room signal quality and reduce cognitive load—never compromise on whitespace for content density.