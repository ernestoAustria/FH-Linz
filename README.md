# FHLinz – Leadership Learning Hub

Mobile, offlinefähige Lernapp für die Inhalte eines Leadership-Seminars an der FH in Linz.

## Funktionen

- 22 strukturierte Lernmodule mit Vortragspraxis und Reflexionsfragen
- 22 modulbezogene, responsive SVG-Scribbles und zwei ausgewählte Illustrationen
- 22 Quizfragen mit Feedback, Gesamtquiz und 5-Fragen-Test
- Volltextsuche, Kategorien, Favoriten, Notizen und Lernfortschritt
- PWA für iPhone/Safari, offline nach erstem vollständigem Laden
- Kein Login, keine Analytics, kein Backend. Speicherung ausschließlich im Browser (localStorage).

## Veröffentlichung auf GitHub Pages

1. Ein **öffentliches** Repository mit exakt dem Namen `FHLinz` erstellen.
2. **Alle Dateien aus diesem ZIP in das Stammverzeichnis** des Repositories hochladen (nicht den äußeren ZIP-Ordner).
3. In GitHub **Settings → Pages → Build and deployment**: `Deploy from a branch`, Branch `main`, Folder `/(root)` auswählen und speichern.
4. Nach dem Deployment `https://DEIN-GITHUB-NAME.github.io/FHLinz/` aufrufen.
5. Am iPhone in Safari über Teilen → **Zum Home-Bildschirm** hinzufügen.

## Inhaltliche Pflege

In `content.json` lassen sich Module (`modules`) und Fragen (`quiz`) erweitern. Jedes Modul benötigt eine eindeutige `id`. Der Service-Worker-Cache in `sw.js` sollte bei Änderungen eine neue Versionsnummer erhalten.

## Hinweise

Die App ist eine didaktische Zusammenfassung des in diesem Chat enthaltenen Seminars, kein wörtliches Transkript. Historische Stilperioden sind Lernvereinfachungen. Öffentliche Beispiele und harte Interventionen sind keine Aufforderung zur Herabwürdigung. Die App ist keine offizielle Veröffentlichung der FH Oberösterreich. Vor einer öffentlichen Veröffentlichung bitte Bildrechte und personenbezogene Fallbeispiele prüfen.


## Scribbles aus dem Chat
Sieben im Chat erzeugte Illustrationen sind als komprimierte JPGs unter assets/*-original.jpg integriert. Antippen öffnet die große Ansicht.
