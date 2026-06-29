# YHDESSÄ – landing page · design spec

**Date:** 2026-06-28
**For:** Sara Kaikkonen (opinnäytetyö / thesis deliverable), built by the user for her
**Location:** `C:\Users\Ensio\sarpansivu` (own git repo, no remote yet)
**Source of truth for content:** `Vuosikellon suunnittelua.pdf` (Sara's brief)

## Purpose & audience

A free, public, single-page landing site presenting the **YHDESSÄ toimintamalli** — a home–school
model for supporting children's everyday physical activity (arkiaktiivisuus). Primary audience:
**alakoulun henkilöstö** (primary-school staff); also shown to **huoltajat** (guardians) and
**oppilaskunta/oppilastoimikunta** (student council).

Brief requirements (from PDF): maksuttomasti ylläpidettävä, mobiili + selain, landing-page-tyylinen,
selkeä, "raikas, sensitiivinen" värimaailma, nuolipainikkeet (per ukkinstituutti.fi reference).

## Tech

Single self-contained `index.html` (HTML + CSS + JS inline). No build step, no dependencies.
Photos in `kuvia/`, extracted from Sara's `.pptx` and web-optimised (<300 KB each).
Target hosting: **GitHub Pages** (free).

## Design system — chosen direction: **C "Pohjoinen selkeys"**

Picked 2026-06-28 from three explored directions (A Raikas / B Lämmin opinnäyte / C Pohjoinen selkeys;
previews kept in `tyylit/`).

- **Type:** Schibsted Grotesk (display, 700) + Hanken Grotesk (body). Sans-only = maximum clarity.
- **Palette (CSS tokens):** paper `#FBFAF4`, paper-2 `#EEEEE5`, ink `#222E27`, ink-soft `#586259`,
  sage `#3F5C49`, sage-soft `#9DB0A0`, gold `#B59A60`, gold-deep `#8C753F`, gold-soft `#D7C28C`.
- **Seasonal tints** (vuosikello only): autumn `#C5803A`, winter `#6E8AA0`, spring `#7FA055`, summer `#D9AE4C`.
- **Signature:** SVG **four-phase wheel** (Yhdistetään → Osallistetaan → Mahdollistetaan → Kehitetään),
  clickable, clockwise arrows — Sara's dia-14 cycle elevated.
- **Secondary device:** arrow-button **vuosikello slider** (her "slaidaamalla sivulle"), scroll-snap, 4 seasonal cards.

## Page structure (Sara's dia-11 order)

1. Sticky nav + hero (one emphasised CTA "Näin otat mallin käyttöön" + quiet secondary link)
2. Three-tile quick-entry row (Vaiheet · Vuosikello · Materiaalit) — from ukkinstituutti reference
3. Periaatteet (5 cards)
4. Vaiheet — the wheel signature
5. Yhdistetään → Lupaus band → Osallistetaan → Mahdollistetaan (+ vuosikello slider) → Kehitetään
6. Materiaalipankki (placeholder "Tulossa" buttons, open new tab)
7. Linkkivinkit (3 real external links)
8. Käyttöönotto (5 numbered steps + toivotus)
9. Tausta & yhteystiedot + footer

Quality floor: responsive to mobile, keyboard focus, `prefers-reduced-motion` respected, scroll-reveal.

## Open items — pending Sara's input (visiting 2026-06-29)

1. **Material links** — Materiaalipankki + lupaus/aloitusviesti etc. are placeholders until Sara provides URLs.
2. **Vuosikello as a circle first?** Sara's note "Ensin vuosikello [kellona] ja sen jälkeen vaiheet."
   Currently slider only — decide whether to add a circular year-clock graphic before the cards.
3. **"Raikas" check** — confirm C's calm palette reads fresh enough for her, or warm/brighten.
4. **Photo→section assignments** — chosen by Claude; easy to reassign.
5. **Detail depth** — full agendas (suunnitteluilta, ideaseinä, per-season vastuut) are summarised on-page,
   full versions intended to live behind material-bank links.

## Next steps

After Sara's review: finalise content + links → commit initial version → publish on GitHub Pages.
