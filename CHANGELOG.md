# Änderungen

## v2.2.0 – 03.11.2026

- **Scan-Ansicht:** Muskeln und Drüsen lassen sich jetzt auch über den Schädel-Scan legen – der Scan wird dabei transparent (Röntgenblick), die Weichteile sind schematisch ausgerichtet.
- **Ebenen im Scan:** Knochen (Scan), Muskeln und Drüsen einzeln schaltbar; «Zähne» ist im Scan enthalten und deshalb ausgegraut.
- **AR mit Tisch-Erkennung:** Auf AR-fähigen Geräten erscheint ein Ring auf der erkannten Oberfläche; antippen setzt den Schädel dort ab (WebXR Hit-Test).

## v2.1.0 – 03.11.2026

- **Echter 3D-Schädel-Scan** (BodyParts3D, CC BY-SA 2.1 JP) statt nur Schema-Modell.
  - Umschalter «Scan / Schema»: Scan zeigt den anatomischen Schädel mit Ober- und Unterkiefer und Zähnen; Schema zeigt Kiefer, Muskeln und Drüsen als farbiges Lehrmodell.
  - Klick auf Scan-Strukturen (Schädel, Oberkiefer, Unterkiefer) zeigt die Erklärung.
  - Scan wird gzip-komprimiert geladen (DecompressionStream), bleibt offline nutzbar.

## v2.0.1 – 03.11.2026

- 3D-Modell: Kamera passt sich automatisch an Bildschirmgrösse an (auch Hochformat/Handy).
- 3D-Modell: Link zur Startseite, kompakter Kopfbereich auf dem Handy.
- Mundanatomie: Link zum 3D-Modell im Fussbereich.

## v2.0.0 – 03.11.2026

- **Neu: Mundanatomie 3D** – drehbares, zoombares und verschiebbares 3D-Modell von Kiefer, Zähnen, Kaumuskeln und Speicheldrüsen.
  - Ebenen einzeln ein-/ausblenden, Strukturen anklicken, Ansicht zurücksetzen, Auto-Drehen.
  - **AR-vorbereitet:** WebXR-Start auf kompatiblen Geräten, sonst GLB-Export für AR-Apps.
  - Eigene Seite `/3d/`, auch als Einzeldatei herunterladbar.
- **Mehrsprachig:** Deutsch, English, Ελληνικά mit Sprachwahl in der App (bleibt gespeichert).
  - Anatomische Bezeichnungen und Kurzbeschreibungen in allen drei Sprachen, Latein bleibt.
  - Geprüfte Terminologie (z. B. κροταφίτης μυς, μασητήρας, αδαμαντίνη, φατνιακό οστό).
- Landingpage mit drei Programmen und 3D-Karte.
- Test 3 Trainer bleibt bewusst auf Deutsch (Prüfungssprache).

## v1.1.0 – 02.11.2026

- **Zum Home-Bildschirm:** Beide Programme und die Startseite haben jetzt ein eigenes App-Icon und ein Web-App-Manifest.
- Beim Start vom Home-Bildschirm öffnen sie ohne Browserleiste (Standalone), mit passender Titelleiste und Theme-Farbe.
- Eigene Icons: «M» für Mundanatomie, «3» für den Test-3-Trainer, «L» für die Übersicht.

## v1.0.1 – 02.11.2026

- **Mobil:** Im Mundanatomie-Programm erscheint die Infobox direkt unter dem Bild und scrollt beim Antippen automatisch ins Sichtfeld.
- **Mobil:** Kapitel-Auswahl oben im Test-3-Trainer (die Themenliste muss nicht mehr durchscrollt werden).
- **Mobil:** kleinere Beschriftungen im Schädel-Diagramm, Startseiten-Logo bündig.
- Geprüft auf iPhone-/Android-Grössen und Tablet: kein horizontales Scrollen, Quiz passt ins Fenster.

## v1.0.0 – 02.11.2026

- Erste Veröffentlichung.
- **Mundanatomie interaktiv**: fünf Ansichten, 53 Strukturen, Filter, Namens-Toggle, Quiz mit zwei Modi.
- **Test 3 Trainer**: neun Themen (Kap. 7–10), Abbildungen aus dem Test, 69 leichte Fragen, Prüfungsquiz.
- Im Mundanatomie-Quiz bleibt die gesuchte Struktur sichtbar markiert, bis geantwortet wird.
