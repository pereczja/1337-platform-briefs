# 1337 Platform — Session Summary
**Date:** 2026-02-08
**Next Topic:** Szervezet a megvalósításhoz

---

## Eldöntött Stratégiai Kérdések

### 1. MVP Stratégia → Opció C: "Vertical Deep"
- Egy vertikál: Hungarian FSI / Lending
- KAVOSZ mint anchor client
- FDE + Platform hybrid modell
- Reference-led GTM

### 2. Termék Architektúra
```
Interface Layer:  Craft Agent fork (1337 branding)
Skills Layer:     Domain-specifikus skills (lending-ops, code-review, stb.)
MCP Layer:        Custom MCP serverek legacy rendszerekhez
LLM Layer:        Claude API (+ on-prem opció Ollama/vLLM)
```

### 3. Legacy Rendszer Stratégia
- **MCP integráció validált** — Oracle, SAP, Google Cloud mind támogatja
- Ügyfelek opciói:
  - A) Újraírás (ritka, drága)
  - B) AI Overlay (fő irány) ★
  - C) Custom UI (dashboard, nem agentic)

### 4. Differenciátor
- **Legacy MCP építés** — Credal/Glean csak SaaS-hoz csatlakozik
- **FDE modell** — helyszíni deployment, nem self-service
- **Lokális piac** — MNB, AI Act, magyar nyelv

---

## Árazás (Value-Based)

### FSI Operations (KAVOSZ típus)
| Tier | Első év | Megújítás | Users | ROI |
|------|---------|-----------|-------|-----|
| Starter | €49k | €49k | 10 | 6.7x |
| Professional ★ | €89k | €65k | 30 | 4.3x |
| Enterprise | €165k | €125k | ∞ | 2.3x |

### Engineering (Dorsum típus)
| Tier | Első év | Megújítás | Devs | ROI |
|------|---------|-----------|------|-----|
| Team | €65k | €65k | 25 | 8.9x |
| Department ★ | €149k | €110k | 75 | 4.7x |
| Enterprise | €349k | €280k | 100+ | 2x |

### MVP Pilot: €29,000 (4 hét, 5 user, 3 skill, 1 MCP)

---

## Létrehozott Dokumentumok

1. **competitor-analysis.html** — Versenytárs elemzés + legacy integráció gap
2. **regulatory-analysis.html** — EU AI Act, MNB, DORA
3. **1337-platform-vision.html** — Platform vízió, FDE modell
4. **mvp-strategy-options.html** — 3 MVP opció (A/B/C)
5. **legacy-systems-strategy.html** — Legacy kezelés, MCP validáció
6. **pricing-strategy.html** — Árazás, tierek, ROI
7. **ui-mockup-interactive.html** — Interaktív demo

**GitHub Pages:** https://pereczja.github.io/1337-platform-briefs/

---

## Létrehozott Skill

`/pricing` — Enterprise B2B pricing expertise, magyar piac context

---

## Következő Téma: Szervezet

Kérdések amikre választ kell adni:
1. Ki kell a csapatba? (FDE-k, engineers, sales?)
2. Milyen kapacitás kell az MVP-hez?
3. Hiring vs. contractor?
4. Partner modell (Dorsum, system integrátorok)?

---

## Prompt Új Chat-hez

```
Folytassuk a 1337 Platform MVP tervezést.

Context:
- 1337 Partners = AI consulting cég, CEO: János
- Platform: Craft Agent fork + custom skills + MCP legacy integráció
- MVP stratégia: "Vertical Deep" — Hungarian FSI/Lending
- Anchor clients: KAVOSZ (ops), Dorsum (engineering)
- Árazás: €29k pilot, €89k Professional (FSI), €149k Department (Engineering)

Előző session dokumentumai: https://pereczja.github.io/1337-platform-briefs/

Most a SZERVEZET a téma:
- Ki kell a csapatba az MVP megvalósításához?
- FDE-k, engineers, sales?
- Milyen kapacitás?
- Hiring vs. contractor vs. partner?
```
