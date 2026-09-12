# Parnia Eshaghian — Design System
*Derived from her existing portfolio (black / white / dark, classic-minimal style) and applied consistently across the CV and website.*

## Colors
| Token | Hex | Use |
|---|---|---|
| Ink (background) | `#0B0B0A` | Website background |
| Ink Soft | `#161513` | Alternating section background |
| Paper (text) | `#F6F1E6` | Primary text on dark background |
| Paper Dim | `#CFC6B3` | Secondary / body text |
| Gold | `#C9A24A` | Accent — headings, dividers, icons |
| Gold Soft | `#E4CD93` | Highlighted text, hover states |
| CV Ink (print) | `#141414` | Body text on white CV pages |
| CV Gold (print) | `#9C7A2B` | Section headings on white CV pages |

Gold is used only for accents and dividers — never as a large fill — consistent with the "used carefully" direction from the brief.

## Typography
- **Display / Headings (English):** Cormorant Garamond — an elegant serif echoing the script/serif titling in her existing portfolio.
- **Body / UI (English):** Jost — a clean geometric sans for readability.
- **Script accent (English):** Petit Formal Script — used sparingly for one accent phrase (e.g. "together.") in the contact section, mirroring the "Let's Work Together" treatment in her portfolio.
- **Persian (all roles):** Vazirmatn on the website; B Nazanin in the Word documents, for wide compatibility and correct Persian shaping.
- **Print CVs:** Garamond (headings) + Calibri (body) — chosen for maximum ATS and cross-platform compatibility.

## Layout
- Centered content column, max-width ~1180px on the website.
- Generous whitespace, single accent rule under section headings.
- Cards with a 4:3 image, 1px gold-tinted border, subtle lift on hover.
- CVs: single column, ATS-friendly (no tables/text boxes), thin gold rule under each section heading.

## Components
- **Buttons:** solid gold (primary) / outlined hairline (secondary), no rounded-pill shapes except the language toggle.
- **Chips/tags:** hairline gold border, pill-shaped, used for skill keywords.
- **Timeline:** hairline vertical line with small gold dot markers for experience entries.
- **Flow diagram (AI Safa Park):** pill nodes connected by gold arrows — used only because the underlying content is a genuine sequential workflow.

## Portfolio browsing pattern
Portfolio → Category → Individual Projects → Project Detail (modal), matching a professional portfolio's browsing depth rather than one flat grid. Categories are derived only from work verifiably present in the uploaded Portfolio PDF: Logo Design, Business Card Design, Poster Design, Website Banner Design, Social Media Design, Menu Design, Wedding & Event Design — plus Architecture / Competition Projects for the Kashan University gate competition entry (text-only card, no fabricated image, clearly labeled as a competition submission rather than commissioned or built work).

## Responsive behavior
Breakpoints at 880px (tablet: stacked hero, 2-col work grid) and 560px (mobile: 1-col grid, condensed nav). Language switcher and RTL/LTR direction are handled globally via a single `dir` attribute swap on `<html>`.
