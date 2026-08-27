# Dr. Vargas 48-hour preview design notes

## Concept position

This single-page concept demonstrates a faster, clearer upgrade path for an established optometry practice. It is a local preview, not the official practice website. Appointment actions use the published phone number only. Service and insurance language is deliberately qualified pending owner confirmation.

## Visual system

| Role | Treatment |
|---|---|
| Primary title | Georgia, bold, 54 to 78 px desktop and 44 to 62 px phone, 0.98 to 1 line height |
| Section title | Georgia, bold, 38 to 56 px desktop and 36 to 48 px phone |
| Body | Segoe UI system stack, 17 px desktop and 16 px phone, 1.65 line height |
| Eyebrow | Segoe UI, 12 px bold uppercase, teal with 0.18 em tracking |
| Word links | Inherited text color, teal underline, gold underline on hover |
| Buttons | Rounded pill, minimum 52 px height, teal primary and outlined secondary |
| Navigation | Compact sans serif links, gold active underline, full-screen phone menu |
| Cards | White surface, 22 px radius, subtle teal shadow, paired gradient top rule and border glow |
| Graphics | Original CSS and inline SVG optical motifs, decorative items hidden from assistive technology |
| Spacing | 112 px desktop section rhythm and 80 px phone section rhythm |
| Breakpoints | 1040 px tablet, 760 px mobile navigation, 410 px compact phone |

Palette: deep teal `#123e46`, medium teal `#1f6770`, pale teal `#d7edeb`, warm paper `#fffdf8`, gold `#d79d4a`, and dark body ink `#173338`.

## Route and component matrix

| Route | Title | Body | Links | Cards and effects | Graphics | 1440 px | 390 px |
|---|---|---|---|---|---|---|---|
| `/` | Primary hero plus shared section titles | Shared sans serif role | Navigation, word, and button roles | Service, insurance, contact, and visual cards | Inline SVG eye icons and CSS lens/chart motifs | Required | Required |

Intentional exceptions: insurance uses a dark surface and light text; the contact phone uses a larger action treatment; the eye chart uses Arial to mimic optotype geometry without an external asset.

## Content confirmation before final release

- Confirm the exact service list and preferred descriptions.
- Confirm office hours and accessibility details before displaying them.
- Confirm insurance participation and payment information before naming any plan.
- Confirm the preferred appointment workflow and whether online scheduling exists.
- Replace concept-preview notices only after practice approval.
