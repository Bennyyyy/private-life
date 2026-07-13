# Repository Guidelines

## Projektstruktur und Inhalte

Dieses Repository ist kein Softwareprojekt, sondern ein privates, deutschsprachiges Personal Wiki. `index.md` ist der Einstiegspunkt; neue, noch unsortierte Notizen und Dateien gehören zunächst in `00-inbox/`. Thematische Inhalte liegen in den nummerierten Root-Ordnern `01-personality/` bis `06-documents/`. Ziele werden in `goals.md` gepflegt. Lies vor Änderungen an einem Bereich dessen `about.md`, sofern vorhanden. Überholte Inhalte werden nach `99-archive/` verschoben, nicht vorschnell gelöscht.

## Lokale Prüfung

Es gibt keine Build-, Laufzeit-, Lint- oder Testbefehle: Alle redaktionellen Inhalte sind Markdown. Prüfe Änderungen daher direkt im Diff:

```sh
git diff --check
git diff -- '*.md'
```

Der erste Befehl findet typische Whitespace-Fehler; der zweite begrenzt die inhaltliche Kontrolle auf Markdown-Dateien. Prüfe zusätzlich, ob neue relative Links vom jeweiligen Dokument aus funktionieren.

## Schreibstil und Benennung

Schreibe Inhalte, Überschriften und Notizen auf Deutsch. Datei- und Ordnernamen sind englisch, kleingeschrieben und bei mehreren Wörtern mit Bindestrichen getrennt, zum Beispiel `strengths-weaknesses.md`. Root-Ordner tragen zusätzlich zweistellige Präfixe. Verwende klare Markdown-Überschriften, kurze Absätze und vorhandene Listen- oder Tabellenstile. Erhalte den persönlichen, direkten Ton und ändere nur den betroffenen Bereich.

## Inhaltliche Validierung

Automatisierte Tests und Coverage-Vorgaben existieren nicht. Kontrolliere vor dem Abschluss Überschriftenhierarchie, Rechtschreibung, relative Links und die Einträge in `index.md`, falls ein neuer Bereich hinzukommt. Neue Notizen und Dateien werden zuerst in `00-inbox/` erfasst und erst beim Sortieren in dauerhafte Themenbereiche verschoben.

## Commits und Pull Requests

Die jüngere Historie verwendet kurze, imperative Betreffzeilen, häufig mit deutschem Bereich oder Conventional-Commit-Präfix, etwa `docs: aktualisiere README auf die neue Struktur`. Erstelle standardmäßig weder Commit noch Push: Änderungen bleiben zur Begutachtung im Arbeitsverzeichnis, bis der Eigentümer ausdrücklich etwas anderes verlangt. Halte angeforderte Commits thematisch geschlossen und nenne den betroffenen Bereich. Pull Requests sollen Zweck, geänderte Dateien und mögliche strukturelle Folgen knapp erklären.

## Datenschutz

Behandle sämtliche Inhalte als vertraulich. Veröffentliche oder übertrage keine persönlichen, medizinischen oder dokumentbezogenen Daten an externe Dienste. Gib sensible Inhalte weder in Logs noch in Commit-Nachrichten oder Beispielen wieder. Bearbeite Dateien unter `02-health/` und `06-documents/` nur bei ausdrücklichem Auftrag.
