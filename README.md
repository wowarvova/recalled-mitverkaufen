# Recalled Mitverkaufen

Landing Page für Reseller, die als Partner auf Recalled mitverkaufen möchten.

## Lokal ansehen

```bash
cd recalled-mitverkaufen
python3 -m http.server 8080
```

Dann [http://localhost:8080](http://localhost:8080) öffnen.

## Konfiguration

In `config.js`:

```js
window.RECALLED_MITVERKAUFEN = {
  instagramHandle: "recalled.vintage",
  instagramUrl: "https://www.instagram.com/recalled.vintage/",
};
```

## Auf Render deployen

1. Neues GitHub-Repo erstellen (z. B. `wowarvova/recalled-mitverkaufen`) und diesen Ordner pushen.
2. Render → **New** → **Blueprint** → Repo verbinden.
3. Oder **New** → **Static Site** → Repo wählen, **Publish directory:** `.`
4. Optional eigene Domain unter **Settings → Custom Domains**.

Kosten: Render **Static Site** ist im Free Tier in der Regel kostenlos.

## Verwandte Projekte

- `recalled-landing` — App-Download-Seite für Kunden
