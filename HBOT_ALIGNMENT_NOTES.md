# HBOT Alignment Notes

## Changelog
- Updated `index.html` copy to align with mild HBOT positioning (1.3-1.4 ATA) and removed medical/clinical cure-style claims.
- Inserted required service language in key sections: adjunct wellness/recovery, results vary by individual, not a substitute for medical care.
- Reworked service cards to pricing-aligned pathways:
  - Single Session (NAD 700)
  - Discovery Trial (3 sessions, NAD 1,950)
  - Recovery Block (10 sessions, NAD 5,000)
  - Progress Block (20 sessions, NAD 9,000)
- Added a new `Conditions / Who it helps` section in `index.html` with links to dedicated pages.
- Created 5 landing pages under `landing/`:
  - `surgery-aftercare.html`
  - `diabetic-support.html`
  - `sports-injuries.html`
  - `autism-families.html`
  - `chronic-pain.html`
- Added shared stylesheet `landing/styles.css` for consistent typography, palette, header/footer, and CTA styling.
- Copied brochure image assets into `landing/images/` and updated paths accordingly.
- Standardized contact phone/WhatsApp to canonical docs number: `+264 81 651 7854`.
- Updated hours to pricing reference: `Mon-Fri 08:00-18:00 | Sat 09:00-14:00 | Sun by arrangement`.
- Removed unsupported email from site where canonical docs did not confirm an official email.
- Softened booking language to avoid unsupported promise of "confirm within 2 hours" and clarified form behavior as localStorage demo.

## Sanity Checks Performed
- Verified all local `href` and `src` references resolve for `index.html` and all `landing/*.html` pages.
- Confirmed copied landing images exist in `landing/images/`.

## Remaining Decisions Needed
- Branding lock: should final public brand be `Afrateq`, `Namib Wellness Center`, or dual-brand (`Afrateq / Namib Wellness Center`)?
- Official contact email: not present in the cited pricing/safety/B2C docs; provide canonical email if website should display one.
- Exact street address: currently kept as Swakopmund + map area + WhatsApp share note; provide final published address if required.
