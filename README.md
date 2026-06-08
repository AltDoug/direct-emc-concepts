# Direct EMC — Landing Page Concepts

Five landing pages for Direct EMC (Florida telehealth EMC evaluations for auto-accident
patients), each built on a **different design strategy** so they can be compared side by side.
All are self-contained: open the `index.html` in any folder, no build step.

Audiences across all five: personal injury attorneys, chiropractors, accident victims.
Conversion spine across all five: the Florida PIP **$2,500 → $10,000** unlock and the
**14-day** clock. CTAs: *Schedule an EMC Evaluation*, *Refer a Patient*, *Contact Us Today*.

| | Theme | Strategy / feel | Motion | Type |
|---|---|---|---|---|
| **v1 · Clarity** (`v1-clarity/`) | Light, cool blue/white/gray | Corporate, reassuring, broad trust. Cards + bento | Subtle scroll-reveal | Outfit |
| **v2 · Authority** (`v2-authority/`) | **Dark** navy + bright blue | Premium, bold, high-energy. Glass cards, big kinetic type | **Motion-forward**: parallax, count-up stats, marquee, pulse | Space Grotesk |
| **v3 · Brief** (`v3-brief/`) | Light, warm editorial mono | Calm, authoritative, white-paper. Hairline dividers, no cards | Near-static, gentle fades | Newsreader (serif) |
| **v4 · Precision** (`v4-precision/`) | Stark white + **hard black grid** + electric blue | Swiss/brutalist. Compliance-grade, exact, no-fluff. Monospace data, **sharp corners** | Hard clip-path wipe reveal | Archivo + IBM Plex Mono |
| **v5 · Care** (`v5-care/`) | Warm, soft, calm blue | Patient-first, empathetic, reassuring. **Big rounded shapes**, soft shadows | Gentle spring + floating accents | Plus Jakarta Sans |

## Quick read on when each fits

- **v1 Clarity** — safest all-rounder; broad professional trust.
- **v2 Authority** — when you want to feel modern, premium, and impressive.
- **v3 Brief** — quiet, credible, editorial; good for an attorney/clinical audience that values restraint.
- **v4 Precision** — bold and distinctive; signals exactness and compliance rigor. Highest design risk, highest memorability.
- **v5 Care** — warmest and most patient-facing; leads with empathy for the accident victim.

## How to view

```
open v1-clarity/index.html
open v2-authority/index.html
open v3-brief/index.html
open v4-precision/index.html
open v5-care/index.html
```

(Your default browser is Arc, which can hide new tabs. `open -a Safari <file>` forces a visible tab.)

## Notes

- **Static HTML/CSS**, single file each. No framework, no dependencies. Responsive
  (desktop / tablet / mobile), accessible (labeled forms, focus states, reduced-motion honored).
- **Forms are front-end demos** — they confirm on submit but do not send data anywhere yet.
  Wiring them to a real scheduler / CRM / email is the next step.
- **Hero image** was AI-generated. Each version treats it to fit its theme (color, navy duotone in v2,
  grayscale in v4, rounded warm framing in v5).
- **Copy is placeholder-real**: phone, email, names, and testimonials are illustrative and should be
  replaced with the real practice details before going live.
- Built with the `landing-page-copywriter` + taste-skill design skills.
