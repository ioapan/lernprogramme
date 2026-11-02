# Lernprogramme Dentalassistenz

Statische Website mit zwei eigenständigen Lernprogrammen (je eine HTML-Datei):

- `mundanatomie/` – Mundanatomie interaktiv
- `test3/` – Test 3 Trainer (Kap. 7–10)

Gehostet mit **GitHub Pages**. Kein Login, keine Cookies, kein Tracking. Der Lernfortschritt wird nur lokal im Browser (localStorage) gespeichert.

## Aktualisieren

Im Arbeitsordner (eine Ebene über diesem Repo):

```bash
./publish.sh            # baut neu, committet, pusht (Version bleibt)
./publish.sh patch      # Version 1.0.0 -> 1.0.1
./publish.sh minor      # 1.0.0 -> 1.1.0
./publish.sh major      # 1.0.0 -> 2.0.0
```

`publish.sh` baut beide Programme aus ihren Quellen, kopiert sie hierher, aktualisiert Version/Datum auf der Startseite, legt Commit und Git-Tag an und pusht.

## Struktur

```
index.html              Startseite
mundanatomie/index.html Lernprogramm 1
test3/index.html        Lernprogramm 2
img/                    Screenshots
icon-*.png             App-Icons (Home-Bildschirm)
manifest.webmanifest   Web-App-Manifest
CHANGELOG.md            Versionshistorie
```

## Lizenzen

- Illustrationen Mundanatomie: Patrick J. Lynch (CC BY 2.5), Servier Medical Art (CC BY-SA 3.0), via Wikimedia Commons.
- Test-3-Abbildungen: aus dem Unterrichtsmaterial, nur für den persönlichen Lerngebrauch.
