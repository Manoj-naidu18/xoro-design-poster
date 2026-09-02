# Task 2 · Poster — “One Story. Every Domain.”

A poster that communicates the value **XORO Story** proposes to different domains.

**Deliverable:** [`poster.html`](poster.html) — a self‑contained, print‑ready A2 portrait poster. Open it in any browser and use **Print → Save as PDF** to export.
**Live version:** https://claude.ai/code/artifact/141f3f62-2e33-4b3c-b2ea-afa87a501a65

---

## 1. The brief, and how I read it

> *Design a poster to communicate the value proposed by XORO Story to different domains.*

The key phrase is **“to different domains.”** The poster’s job isn’t to describe the product — it’s to show, at a glance, that **one thing XORO Story does creates value in several distinct places.** So the whole composition had to visualise *one → many* while staying accurate to what XORO Story actually is.

### What XORO Story is (research)
From [xorostory.com](https://www.xorostory.com):

- **Category:** a *spatial storytelling* platform — XR/AR + AI.
- **Core promise:** *“Your customers don’t want static presentations — they want to experience your product instantly.”*
- **What it turns:** existing sales pitches, marketing content and training lessons → **memorable, interactive 3D experiences.**
- **How it works:** *Fabel* (AI story partner) · a no‑code **3D Editor** · **XR templates** · deploy to **web, mobile AR, and AR/VR headsets**, with engagement & movement **analytics**.
- **The three domains it names itself:** **Sales · Marketing · Training.**

I anchored the poster on those three real domains rather than inventing new ones — accuracy matters when the audience *is* the company.

## 2. The core idea — a prism

XORO Story’s entire identity is about moving **out of the flat screen and into depth.** I turned that into a single, ownable visual metaphor:

> **A prism.** One beam of “static” white light (your existing pitch/content/lesson) enters the **XORO engine** and *refracts* into a spectrum — and each colour of that spectrum resolves into a domain: **Sales, Marketing, Training.**

Why it works:
- It literally shows **one story → value in every domain** (the exact brief).
- **Refraction = the gradient‑line motif** already in XORO’s branding, but now it *means* something.
- It’s **optical / spatial**, echoing the XR product without a clichéd headset drawing.
- **“Feel it → Recall → Retain”** — each domain’s outcome, carried by its own spectrum colour.

## 3. Design system

**Palette** — a deliberate, dark‑first *celestial* ground (XORO uses sparkles/dark UI), with the refraction spectrum as the accent system:

| Role | Hex | |
|---|---|---|
| Ground (violet‑black) | `#0B0713` | not pure black — biased toward the brand violet |
| Incoming beam | `#FFF7E9` | the “static” white light |
| Sales | `#FF5F8B` | rose‑magenta — energy, conversion |
| Marketing | `#8B6BFF` | violet — brand & creativity (the core hue) |
| Training | `#34E3C4` | cyan‑teal — clarity, learning |
| Spark / kicker | `#FFD9A0` | warm gold highlight |

**Type**
- **Syne** — display. Characterful, wide, art‑tech forms that feel spatial without being a default poster face.
- **Hanken Grotesk** — body. Warm, highly legible grotesque.
- **JetBrains Mono** — eyebrows, labels and specs, for an XR/technical texture.

**Layout** — a vertical *flow of light*: header → headline → the single beam → the prism engine (with the four real capabilities as tags) → three refracted beams → three domain value cards → deployment band → tagline. The eye travels the same path the light does.

## 4. Content architecture (the “value to each domain”)

Each domain card is built as a small argument:

| | Sales | Marketing | Training |
|---|---|---|---|
| **The shift** | pitch deck → live demo | flat content → an experience | slide lessons → spatial practice |
| **Value** | self‑discovery in a 3D showroom; voice‑guided; deploy anywhere | gamified spatial stories; engagement & movement analytics; refine in real time | learn by doing in 3D; guided pathways; attention tracking |
| **Outcome** | **Feel it** | **Recall** | **Retain** |

All copy is drawn from XORO Story’s own positioning.

## 5. Craft notes
- **Print‑ready:** `@page { size: A2 portrait }`; layout is built in container units (`cqw`) so screen and print scale identically. Exports cleanly to PDF.
- **Responsive & accessible:** balanced headline wrapping, visible focus state on the print control, and a `prefers-reduced-motion` guard that stills the animated light rays.
- **Self‑contained:** one HTML file — fonts from Google Fonts, all graphics as inline SVG, a lightweight canvas starfield. No build step, no dependencies.

## 6. Run / export
```bash
# open directly
start poster.html        # Windows
# then: Print → Save as PDF  → A2 (or Fit to page for A3/A4)
```

---

*Designed for the XORO Story UI/UX design internship application — Task 2.*
