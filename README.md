AalenVorlagePraesi - Beamer Template

Dieses Verzeichnis enthält eine wiederverwendbare Beamer-Vorlage für Präsentationen.

Datei
- `AalenVorlagePraesi.tex` — Beamer-Vorlage (mit Platzhaltern für Titel, Autor, Institut, Datum und Logo).

Schnellstart
1. Kopiere `AalenVorlagePraesi.tex` in dein Projekt oder editiere die Datei direkt.
2. Ersetze die Platzhalter
   - `\title{...}` — Präsentationstitel
   - `\subtitle{...}` — Untertitel / Kontext
   - `\author{...}` — Autor
   - `\institute{...}` — Institut / Zugehörigkeit
   - `\date{...}` — Datum
3. Lege optional ein Logo in der Arbeitsmappe ab. Die Vorlage sucht standardmäßig nach `Hochschule-aalen.svg.png` oder `hs-aalen-logo.png`. Du kannst die Macro-Definition `\hsaaLogo` anpassen, um andere Dateinamen zu verwenden.

Kompilieren (macOS, zsh)
- Mit pdflatex (mehrfach laufen, um Inhaltsverzeichnisse zu erzeugen):

```bash
pdflatex AalenVorlagePraesi.tex
pdflatex AalenVorlagePraesi.tex
```

- Mit xelatex (falls du Unicode-Fonts bevorzugst):

```bash
xelatex AalenVorlagePraesi.tex
```

Tipps
- Wenn du Bilder (z. B. `UML-Klasse.pdf`) verwendest, lege sie in dasselbe Verzeichnis wie die `.tex`-Datei.
- Für eine saubere Ausgabe kannst du `latexmk -pdf AalenVorlagePraesi.tex` verwenden, falls installiert.

Support
- Wenn du möchtest, passe ich die Vorlage weiter an (Logo, Farben, Fußzeile, Titelseite) oder erstelle eine „minimal“ Version ohne Aalen-Hinweise.
