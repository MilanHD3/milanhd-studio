# MilanHD's Studio – Website

Website von MilanHD's Studio, einem unabhängigen Roblox Game Development Studio.
Enthält: Spiele, Studio-Infos, Team, News, Countdown, Roadmap, Galerie, Wiki und Bewerbung.

## Ordner

- `index.html` – die komplette Website (HTML, CSS und JavaScript in einer Datei)
- `.nojekyll` – sorgt dafür, dass GitHub Pages die Datei unverändert ausliefert
- `.github/workflows/pages.yml` – veröffentlicht die Seite automatisch bei jedem Push auf `main`

## Auf GitHub veröffentlichen

1. Neues Repository auf GitHub anlegen und alle Dateien hochladen (auch den versteckten Ordner `.github`).
2. Im Repository: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Auf `main` pushen. Nach ca. einer Minute ist die Seite erreichbar unter
   `https://<dein-name>.github.io/<repo-name>/`.

## Inhalte ändern (in `index.html`, ganz unten im Skript)

| Variable | Inhalt |
|----------|--------|
| `TEAM`   | Team-Rollen und Mitglieder |
| `NEWS`   | Ankündigungen |
| `ROAD`   | Roadmap |
| `CD`     | Countdown (Titel und Datum) |
| `GAL`    | Galerie-Platzhalter |
| `WIKI`   | Wiki-Einträge |

## Wichtig: Bewerbung, Admin-Bereich und Live-Zahlen

Diese drei Funktionen nutzen die Datenbank der claude.ai-Veröffentlichung und laufen
**nicht auf GitHub Pages**. Dort zeigt das Formular einen Hinweis auf Discord, und der
Admin-Bereich ist nicht verfügbar. Alles andere funktioniert normal.
Für eine Bewerbung auf GitHub Pages wird ein eigenes Backend benötigt
(z. B. Server, Discord-Bot oder Formular-Dienst).
