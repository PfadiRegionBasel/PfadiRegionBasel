# Grundlagen-Dokumente der Pfadi Region Basel

- Logo als `.svg`
- `.css` für Web-Projekte
  - Schriftart lokal ([Quelle](https://www.latofonts.com/lato-free-fonts/))

## Verwendung
Gesamtes Repo herunterladen und an gewünschtem Zielort entpacken, dabei die Ordnerstruktur nicht verändern. Anschliessend die Datei `prb.css` einbinden.

Somit wird die Schriftart [Lato](https://www.latofonts.com) (Gewicht 300) als Standardschrift gesetzt. Zudem werden die PRB-spezifischen Farben als CSS-Variablen definiert:
```css
:root {
  /* Hauptfarben - für guten Inhalt */
  --prb-schwarz: #252525;
  --prb-dunkelgrau: #5C5C5C;
  --prb-hellgrau: #D9D9D9;
  --prb-eierschale: #E5E2CC;
  --prb-rot: #C62828;

  /* Zusatzfarben - für Spezielles */
  --prb-blau: #006098;
  --prb-gruen: #006E3A;
  --prb-braun: #644438;
  --prb-gelb: #FFCC00;
  --prb-pink: #F10081;
}
```
