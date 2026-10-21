# RFIP Newsletter · Issue 01

## Developer handoff

**Design prototype:** `index.html`  
**Artwork and photo assets:** `assets/`  
**Content source:** `RFIP_Newsletter_Issue01_Edited.docx`

The prototype is an editorial web newsletter for **Vision for Rwanda, Window to the Continent**, Issue 01 (October 2026). It is structured as one scrollable page with anchored navigation, a strong opening, six numbered content sections, and a clear contact close. Use the prototype as the visual and content reference when integrating it into the production site.

## Visual direction

- Follow the supplied RFIP artwork: deep teal, bright blue, orange, lime green, and a subtle connected-node motif. Keep blue and green as accents and use orange sparingly for rules and emphasis.
- The working color tokens sampled from the supplied banner are: deep teal `#183F50`, blue `#0093D3`, orange `#F5AD00`, and lime `#83C412`. The source images are compressed JPEGs, so confirm these values against the official RFIP brand guide before final production.
- Retain generous white space, strong editorial headlines, short section labels, restrained rules, and clear content hierarchy. Avoid decorative crops that interfere with partner marks or faces.
- Use the official RFIP logo as a logo asset if a vector or transparent logo is available. The included banner is an image containing the logo and tagline, suitable for the prototype masthead but less flexible than a standalone logo in production.
- Keep contrast and keyboard focus visible. Preserve semantic headings, descriptive image text, and responsive behavior at narrow widths.

## Page structure

1. RFIP masthead and section navigation
2. Newsletter title, issue date, and opening field image
3. Secretariat welcome and four key figures
4. In this issue navigation
5. Launch at the Africa Food Systems Forum, minister’s quote, and outcomes
6. Four accelerators and Investment Accelerator spotlight
7. Get to Know RFIP recap and 25 November event card
8. Partners Group, partner list, and JASIRI / SunCulture spotlights
9. Dated milestone timeline
10. Get involved links and RFIP contact

## Included assets

| File | Intended use | Production note |
|---|---|---|
| `assets/rfip-brand-banner.jpg` | Prototype masthead | Contains the RFIP wordmark and tagline in the image. Replace with an approved standalone logo if available. |
| `assets/rfip-issue-cover.jpg` | Issue cover / social preview | Artwork says Issue 01 · October 2026. Used for the Open Graph image. |
| `assets/rfip-gold-rule.png` | Section title accent | Decorative brand rule. |
| `assets/field-innovation-drone.jpg` | Hero visual | Illustrative placeholder from the supplied draft; replace with approved RFIP / launch photography before publication. |
| `assets/minister-portrait.png` | Minister’s launch quote | Confirm image identity, crop, and usage approval with RFIP before publication. |
| `assets/partnership-handshake.jpg` | Partner section visual | Illustrative placeholder from the supplied draft; replace with approved RFIP partner photography before publication. |

## Items needed before release

- The official RFIP brand guide or confirmation of the exact color and typography specifications. No separate guide file was included with the working files; the prototype follows the RFIP artwork embedded in the newsletter document.
- Approved AFSF launch and partner photography, plus image credits and permissions.
- The registration URL for the 25 November virtual call. The draft contained an insert-link note, so the prototype presents the event details without a registration button.
- Approved partner quotes and any confirmed partner-news links if those items are to appear in Issue 01. Editorial placeholders from the source document have been left out.
- Final confirmation of issue release date and approved copy.

## Responsive and implementation notes

- The layout is designed for a centered reading width of about 1,100 px and collapses into a single column below 720 px.
- Keep image files local or move them to the site’s managed media library, then update references under `assets/`.
- The prototype is self-contained HTML and CSS; no JavaScript framework is required. The production developer can translate the sections into the site’s component system.
- Replace temporary imagery before launch, check the newsletter links, and verify desktop and mobile layouts in the target CMS.
