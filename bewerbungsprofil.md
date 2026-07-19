# Agent Skill: Bewerberprofil Design & Architecture

## Core Tech Constraints
- **Platform:** Pure HTML5 and vanilla CSS3 only. Zero frameworks (no Bootstrap, no Tailwind, no PHP). Must run flawlessly on GitHub Pages.
- **Hierarchy:** Strictly single-page layout or flat tab-structure. Max 1 level of navigation. No deep sub-menus.
- **Usability:** Instant loading speeds. No heavy JS animations, video backgrounds, or parallax junk.

## Visual Identity & Color System
- **Dominant Base:** Deep Teal (`#0D5152`) for headers, hero areas, and structural sections.
- **Accent Elements:** Vibrant Orange (`#F68826`) exclusively for Call-to-Action (CTA) elements and primary buttons[cite: 2].
- **Surfaces:** Pure White (`#FFFFFF`) or light Off-White (`#F2FAFA`) for content card structures[cite: 2].
- **Typography Canvas:** Clean, professional sans-serif system stack (`system-ui`, `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `Roboto`, `sans-serif`) targeting a modern layout[cite: 2].
- **Readability:** Body text uses Charcoal (`#666666`) at 15px with an expansive `line-height: 40.8px` for maximum reading comfort and accessibility[cite: 2]. Headings use Dark Charcoal (`#2B2B2B`)[cite: 2].

## Spacing & Component Standards
- **Grid:** Max-width content container of `1296px`[cite: 2]. Centered execution (`margin: 0 auto`)[cite: 2].
- **Spacing Scale:** Rigid 4px grid system[cite: 2]. Base section padding = `40px` to `52px`[cite: 2]. Card interior padding = `24px`[cite: 2].
- **Primary Buttons:** Orange background (`#F68826`), bold white text, padding `14px 41px`, border-radius `25px`, accompanied by the distinctive glowing focus shadow (`rgba(254, 195, 0, 0.455) 0px 0px 0px 3.54px`)[cite: 2].
- **Cards:** White background, 8px border-radius, subtle elevation shadow (`rgba(0, 0, 0, 0.08) 0px 2px 8px`)[cite: 2]. On hover, shift background to `#F2FAFA` and slightly intensify the shadow[cite: 2].

## Structural Blueprint (Aufbau)
1. **Hero (Startseite):** Minimalist introduction with full name, core job target, and designated profile image area[cite: 1].
2. **Kurzprofil (Über mich):** Compelling, high-impact overview balancing massive technical expertise with general versatility[cite: 1].
3. **Werdegang (Lebenslauf):** Clean, structured chronological timeline covering IT infrastructure, administration, and technical milestones[cite: 1]. Includes dedicated high-contrast sub-sections for Hard Skills and Competencies[cite: 1].
4. **Downloadbereich (CTA):** Highly distinct, prominent action area featuring the master application bundle link: `https://1drv.ms/f/c/5277166773def518/IgAKEDSyV4KVQ5mLOdQ_6CK8Afhcjr294D3zv1TYQAk4vag` labeled as "Komplette Bewerbungsmappe als PDF herunterladen"[cite: 1].
5. **Kontakt & Impressum:** Unobstructed footer displaying active contact details (Name, Address, Email, Phone) without hiding behind generic contact forms[cite: 1].