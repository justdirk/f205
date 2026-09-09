# F205 — anteprima del negozio

Anteprima navigabile del tema Shopify F205: home, collezione, scheda prodotto,
carrello e selettore IT/EN. Due file, nessuna build.

| | |
|---|---|
| `index.html` | la pagina intera (CSS, JS e disegni dei capi dentro) |
| `assets/photos.js` | le fotografie, in data URI |

## Pubblicare

Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)` → Save.
Dopo un minuto il sito risponde su `https://justdirk.github.io/f205/`.

## Non è il negozio

È l'anteprima del design, da far vedere ai titolari. Il negozio vero gira su
Shopify con il tema `f205-shopify-theme.zip`.

Qui dentro sono segnaposto:

- **le foto** — mockup generati per il prototipo Lovable, non i capi veri
- **i prezzi** — F205 non pubblica listini online
- **le recensioni** — quelle di Palocap sono di un'altra attività
- **spedizioni, orari, P.IVA** — marcati in rosso nella pagina

La pagina è `noindex` e `robots.txt` blocca tutti i crawler: finché è una bozza
non finisce su Google.
