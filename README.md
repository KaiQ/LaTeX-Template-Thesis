This is a latex template for master/ bachelor thesis or normal reports at FHS.

# Changelog

* Acronym verzeichnis hinzugefügt
* glossar hinzugefügt
* verzeichnisse an den anfang des dokuments geschoben
* hyperref eingebunden -> bessere navigation in pdf version (günstig bei der verteidigung der arbeit)
* srchack eingebunden -> beseitigt inkompartibilitäten anderer packages zu KOMA Script
* pagenum in allen verzeichnissen ist römisch
* ordnerstruktur überarbeitet
* makefile angepasst
* Farben für listings im eclipse style
* Vorlage für Tabellen eingebunden
* **code** Umgebung zur besseren Platzierung von Quellcodelistings
* **Code** Umgebung um Listings wie Bilder und Tabellen zu Platzieren
* floatparameter geändert um Bilder und Tabellen besser zu Platzieren
* hurenkinder & schusterjungen durch floatingparameter verboten
* Buildkommando der Makefile auf einen Befehl reduziert
* Statt BibTeX wird BibLaTeX benutzt
* Beispiel für Zitieren von Onlinequellen

# Dokument erstellen
## Empfohlene Tex Distribution
[TeX Live]

## Variante 1
make

## Variante 2
latexmk -pdf -pdflatex="pdflatex -synctex=1 %O %S" "document"

# Vorschau
[demo here]

# Benutzung
* in der Datei **Document.tex** die eigenen Daten eintragen
* eigene Inhalte werden im Ordner *content* platziert und im hauptdokument mit dem befehl *\input{./content/eigenes-dokument.tex}* eingebunden

[demo here]:https://www.dropbox.com/s/4fu1nx1ynb5adlk/document.pdf
[TeX Live]: https://www.tug.org/texlive/
