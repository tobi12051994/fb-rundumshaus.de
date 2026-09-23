# FB Rund ums Haus – OnePager

Fertiger statischer Website-Ordner für GitHub + Netlify.

## Enthalten
- `index.html` – SEO-optimierter OnePager
- `impressum.html`
- `datenschutz.html`
- `danke.html` – Zielseite nach Kontaktformular
- `404.html`
- `css/styles.css`
- `js/script.js`
- `robots.txt`
- `sitemap.xml`
- `netlify.toml`
- `assets/images/flyer-original.jpg`

## Vor dem Livegang unbedingt ersetzen/prüfen
1. `DEINE-DOMAIN.DE` in `index.html`, `robots.txt` und `sitemap.xml`
2. Einsatzgebiet / konkrete Orte
3. Impressums-Platzhalter (USt-ID, Register etc., soweit einschlägig)
4. Datenschutzerklärung auf tatsächliches Hosting/Formulardienst prüfen
5. Falls gewünscht: echtes Logo als PNG/SVG und eigene Fotos ergänzen

## Netlify
Repository mit GitHub verbinden. Bei einer reinen statischen Seite ist kein Build-Befehl nötig.
Publish Directory: `.`

Das Kontaktformular ist bereits mit `data-netlify="true"` vorbereitet.
Nach dem ersten Deploy sollte Netlify das Formular erkennen.

## Vorschau für Kunden
Für eine nicht indexierte Vorschau kann vorübergehend in `index.html`
`<meta name="robots" content="noindex,nofollow">` gesetzt werden.
Vor Livegang wieder auf `index,follow` ändern.
