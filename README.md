# rstrobl.com

Statische Website — kein Build-Schritt, kein Framework. Nur HTML, CSS und Assets.

## Lokal starten

Die Seite braucht einen lokalen Webserver (Doppelklick auf `index.html` funktioniert nicht, weil Verzeichnis-Links wie `impressum/` nur über einen Server zu `impressum/index.html` aufgelöst werden):

```bash
python3 -m http.server 8000
```

Dann im Browser öffnen: <http://localhost:8000>

Beenden mit `Ctrl+C`. Änderungen an HTML/CSS sind nach einem Browser-Reload sichtbar, ohne den Server neu zu starten.

## Struktur

- `index.html` — Startseite (Deutsch)
- `en/index.html` — englische Version
- `impressum/`, `datenschutz/` — Rechtsseiten (nur Deutsch)
- `style.css` — gesamtes Styling
- `fonts/`, `brands/`, `*.jpg` — Assets
