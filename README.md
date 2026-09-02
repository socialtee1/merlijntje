# Merlijntje

Website voor Merlijntje — professionele schoonmaak & reiniging aan de Belgische kust.

## Jouw site openen (aanbevolen)

Dit project bevat je **volledige HTML-site** van Claude:

| Bestand | Wat het is |
|---------|------------|
| `landing.html` | Startpagina — kies Merlijntje of Merli camper |
| `merlijntje.html` | Volledige hoofdsite |
| `merli-camper.html` | Camper — binnenkort |

### Met Live Server (in Cursor/VS Code)

1. Rechtsklik op **`landing.html`**
2. Kies **"Open with Live Server"**
3. Browser opent op `http://127.0.0.1:5501/landing.html`

**Niet** `index.html` openen met Live Server — dat is de React/Vite-versie en geeft een wit scherm.

### Direct de hoofdsite

Open **`merlijntje.html`** met Live Server → `http://127.0.0.1:5501/merlijntje.html`

---

## React-versie (optioneel, experimenteel)

Er staat ook een React/Vite-versie in `src/` (scroll-hero, componenten). Alleen nodig als je die verder wilt uitbouwen:

```bash
npm install
npm run start
```

Opent op http://127.0.0.1:5173/

---

## Bestanden

- `merlijntje.html` — productie-site (SEO, FAQ, Google Analytics, voor/na)
- `public/images/` — losse foto's voor de React-versie
- `src/` — React-componenten (experimenteel)
