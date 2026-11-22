# Rock Wood Interior Design — implementation plan


## Product and implementation
Build a fast, responsive, single-page marketing site for Rock Wood Interior Design in Bengaluru. The approved Blueprint is the project plan. The site uses semantic HTML, CSS, and lightweight browser JavaScript with a dependency-free Node static server for Preview. No account, database, or backend is needed. Seven purpose-created interior photography assets are displayed from Manus Storage URLs: one wide hero and six portfolio/service photographs, including two dedicated pooja-room examples. The enquiry form prepares a WhatsApp message locally; phone, email, Instagram, address and map links are direct actions. Add a persistent visitor-selectable language mode for English, Tamil, Kannada and Hindi, including localized page copy, accessible labels, image descriptions and WhatsApp enquiry text. Keep the language selector in the page's top utility bar, ordered Tamil, English, Kannada and Hindi.

## Structure
- `index.html` — accessible landing page, brand/service/project/contact content and metadata.
- `styles.css` — design system, responsive layouts, focus states and reduced-motion behavior.
- `script.js` — responsive navigation, four-language copy, persistent language selection and localized WhatsApp enquiry behavior.
- `server.js`, `package.json` — no-dependency Preview server and static build command.
- `public/manus-routes.json`, `public/favicon.svg` — route manifest and site icon.
- `public/rockwood-mark.svg` — custom logo artwork, also used for platform project-logo metadata.
- `plan.md`, `TODO.md` — approved direction and outcome criteria.

## Visual direction

**Chosen style: Warm contemporary craftsmanship** — a calm, premium interpretation of Bengaluru homes, pairing natural wood with pale mineral finishes. The experience should feel tactile and personal rather than like a generic catalogue.

- **Design movement:** contemporary Indian residential interiors with restrained Japandi influence and an architectural-editorial sensibility.
- **Core principles:** materials lead; generous breathing room; clear, friendly service information; purposeful, low-friction contact.
- **Color philosophy:** parchment and soft limestone create daylight; walnut and charcoal bring depth; muted olive signals natural craft; a restrained copper/clay accent warms key actions.
- **Layout paradigm:** editorial, asymmetrical image-led sections, shifting from a spacious hero to staggered service photography and a compact information-rich contact close.
- **Signature elements:** a custom interlocking “R/W” wood-mark; fine grain-like rules and small section markers; rounded, framed photography with subtle copper labels.
- **Interaction philosophy:** direct paths to call, WhatsApp, Instagram and map. Navigation remains simple; enquiry form turns visitor details into a ready-to-send WhatsApp message without pretending to submit to a server.
- **Animation:** restrained fades and small image lifts on reveal/hover; respect `prefers-reduced-motion`; avoid motion essential to content.
- **Typography system:** `Cormorant Garamond` for expressive English headlines, paired with `Manrope` for English navigation, body copy and controls. Use Google `Noto Sans` and `Noto Serif` families for Tamil, Kannada and Devanagari, with system fallbacks.
- **Brand essence:** thoughtful, made-to-measure interiors for Bengaluru homeowners, designed to make everyday living feel considered. Personality: grounded, warm, assured.
- **Brand voice:** personable and design-led, with concrete language rather than generic luxury claims. Example lines: “Dream design. Live better.” and “Made around the way you live.”
- **Wordmark & logo:** custom geometric RW monogram inspired by joined timber profiles, paired with a spaced all-caps ROCK WOOD wordmark and small INTERIOR DESIGN descriptor.
- **Signature brand color:** deep walnut-olive `#3b4032`.

A 0.06 probability direction is industrial-urban graphite, steel and concrete; a 0.05 direction is bright, playful maximalist color blocking; a 0.04 direction is ornate heritage palace detailing. The selected warm contemporary craftsmanship direction is the approved Blueprint visual choice.
