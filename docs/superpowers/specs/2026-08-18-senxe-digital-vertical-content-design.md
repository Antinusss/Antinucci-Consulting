# Senxe Digital — Vertical repositioning (content-only)

## Context

Senxe Digital currently mixes sourcing-from-China content with digital-marketing services. Sourcing will live on a separate future site sharing the same design/brand/ToV. This site becomes 100% digital-vertical: web, e-commerce, paid acquisition, UX/CRO, retention, AI advisory.

**Out of scope:** design, layout, CSS, palette, typography, component structure. This is a content/IA change only — reuse existing templates and classes as-is.

## Pages removed from navigation (files kept, unlinked)

- `servizi/scouting-sourcing-cina.html` — future sourcing site material.
- `servizi/social-media-strategy-management.html` — not part of the digital vertical for now.

Both remain in the repo, unlinked from `index.html` nav/services/marquee, for possible future reuse.

## Homepage (`index.html`)

**Meta:**
- Title: `Senxe Digital — Il tuo business online. Senza intoppi.`
- Description: `Senxe Digital: agenzia verticale su website design & development, e-commerce, Google Ads, Meta Ads, UX/CRO ed email marketing.`

**Hero:**
- Eyebrow unchanged (`Senxe Digital`)
- H1: `Il tuo business online.<br>Senza intoppi.`
- Lead: `Agenzia verticale sul digital: sito, e-commerce, campagne e retention sotto un'unica regia strategica.`
- Buttons unchanged.

**Marquee:** `Website * E-Commerce * Google Ads * Meta Ads * UX & CRO * Email Marketing * AI Advisory` (repeated twice, same pattern as now).

**Services section:**
- Eyebrow unchanged (`I nostri servizi`)
- Section title: `Dal primo click al cliente che torna.`
- New intro paragraph (reuse `.about-lead` class, no new CSS) positioning services as one integrated ecosystem: `Sito, e-commerce, campagne e retention non sono pezzi separati: li gestiamo come un unico ecosistema, dove ogni servizio rafforza gli altri. Un solo team, una sola regia strategica, zero passaggi persi tra un fornitore e l'altro.`

**Service cards, in order:**

| # | Card | Links to |
|---|------|----------|
| 01 | Website Design & Development | `servizi/website-set-up-management.html` |
| 02 | E-Commerce Set Up & Management (Shopify & WooCommerce) | `servizi/ecommerce-set-up-management.html` |
| 03 | Google Ads | `servizi/google-ads.html` |
| 04 | Meta Ads | `servizi/meta-ads.html` |
| 05 | UX Audit & Usability Review | `servizi/ux-audit-cro.html` (new) |
| 06 | Email Marketing | `servizi/email-marketing.html` |
| 07 | AI Advisory | `servizi/ai-advisory.html` |

Card copy/tags follow each page's own hero copy/tags (see below) — homepage cards are the short-form version already in the existing template pattern.

**About section:**
- H2 unchanged (`Competenze verticali. Visione orizzontale.`)
- About-lead: `Siamo un'agenzia verticale specializzata nel digital: ogni ambito seguito da chi lo conosce a fondo, coordinato da un'unica regia strategica. Il risultato è un servizio che copre l'intero funnel — dal sito al cliente che compra, e torna a comprare.`

## Site-wide (every HTML file, including the two unlinked ones)

Footer payoff line replaced: `Il tuo business online. Senza intoppi.`

## Service page content changes

**Website Design & Development** (`servizi/website-set-up-management.html`)
- `service-num`: `01 · Web`
- H1: `Website Design &amp; Development`
- Tags: `UX/UI`, `SEO tecnico`, `Manutenzione`, `CRO`
- Intro para 2 gets one added sentence: `E dove serve, affianchiamo il lavoro con audit UX e attività di CRO per migliorare le conversioni, non solo l'estetica.`
- Framework name/phases unchanged.
- Title tag: `Website Design & Development — Senxe Digital`

**E-Commerce Set Up & Management** (`servizi/ecommerce-set-up-management.html`)
- `service-num`: `02 · E-Commerce`
- H1: `E-Commerce Set Up &amp; Management (Shopify &amp; WooCommerce)` — plain text, no markup change, same `<h1>` element as today.
- Tags: `Shopify`, `WooCommerce`, `CRO`
- Intro para 2 gets one added sentence: `Affianchiamo il lavoro, quando utile, con audit UX e attività di CRO mirate a migliorare il tasso di conversione dello store.`
- Framework unchanged.

**Google Ads** (`servizi/google-ads.html`)
- `service-num`: `05 · Advertising` → `03 · Advertising`. No other content changes.

**Meta Ads** (`servizi/meta-ads.html`)
- `service-num` stays `04 · Advertising`. No other content changes.

**UX Audit & Usability Review** (new file `servizi/ux-audit-cro.html`, cloned from the existing service-page template)
- `service-num`: `05 · UX & CRO`
- H1: `UX Audit &amp; Usability Review`
- Lead: `Il traffico arriva, ma non converte? Analizziamo dove il tuo sito perde utenti e ti diamo un piano concreto per recuperarli.`
- Tags: `Usability Audit`, `Heatmap & Behavior`, `Report CRO`
- Intro para 1: `Un sito che riceve visite ma non vende ha quasi sempre un problema di percorso, non di traffico. Bottoni che non si notano, checkout troppo lunghi, informazioni che mancano nel momento sbagliato.`
- Intro para 2: `Analizziamo l'esperienza utente end-to-end e trasformiamo quello che troviamo in un report di attività CRO: priorità chiare, non un elenco di osservazioni generiche.`
- Framework name: `Senxe UX Audit Framework`
- Framework intro: `Dall'analisi al piano d'azione, in un ciclo ripetibile.`
- Phases:
  1. Audit — `Revisione euristica di ogni pagina chiave: homepage, prodotto, checkout.`
  2. Comportamento — `Heatmap, scroll e session recording per vedere cosa fanno davvero gli utenti.`
  3. Report CRO — `Priorità di intervento ordinate per impatto stimato sulle conversioni.`
  4. Iterazione — `Test delle modifiche e misurazione dell'effetto reale sui numeri.`
- CTA band: `Il tuo sito ha traffico ma poche conversioni? Parliamone.`
- Title tag: `UX Audit & Usability Review — Senxe Digital`
- Meta description: `Analizziamo dove il tuo sito perde conversioni. Audit di usabilità e report attività CRO. Scopri il Senxe UX Audit Framework.`

**Email Marketing** (`servizi/email-marketing.html`)
- `service-num` stays `06 · Retention`
- Tags: `Automazioni`, `Segmentazione`, `Copy`, `Klaviyo`
- Lead copy updated to mention the tool: `La lista clienti è un asset, non un file dimenticato. Flussi automatici su Klaviyo e campagne che trasformano chi ti conosce già in chi compra di nuovo.`
- Framework unchanged (`Senxe Lifecycle Framework`).

**AI Advisory** (`servizi/ai-advisory.html`)
- `service-num` stays `07 · Advisory`. No other content changes.

## Verification

- Local server (`python3 -m http.server`), visually confirm homepage service order/copy and the new UX Audit page, before pushing.
- Grep repo for any remaining "Sourcing", "freelance", "agenzia tradizionale", "fornitore in Cina" strings outside the two unlinked/kept files to confirm no stray copy survived.
- Confirm `scouting-sourcing-cina.html` and `social-media-strategy-management.html` still exist but are unreferenced from `index.html`.
