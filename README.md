# Bachelor of Science Vorlage Noah Ruben
Eine Vorlage für Bachelorarbeiten innerhalb der THM als dualer Student.


# How to use

Informationen über das Dokument, wie z.B. Titel, Autor, Matrikelnr. etc werden in der Datei Meta.tex definiert und können danach global verwendet werden.

## Metainformationen die gesetzt werden sollten

```tex
\newcommand{\titel}{<fill>}
\newcommand{\untertitel}{<fill>}
\newcommand{\autor}{<fill>}
\newcommand{\adrStrasse}{<fill>}
\newcommand{\adrOrt}{<fill>}

\newcommand{\matrikelnr}{<fill>}
\newcommand{\hochschulBetreuer}{<fill>}
\newcommand{\fachbetreuer}{<fill>n}
\newcommand{\unternehmen}{<fill>}
```

# Aufbau der Vorlage 
### Packages.tex:
LaTeX-Packages, die benötigt werden, sind in die Datei  "ausgelagert", um diese Vorlage möglichst übersichtlich zu halten.

### Befehle.tex: 
Eigene befehle z.B um zu zitieren, oder die richtige Nummerirung sicherzustellen.

### Seitenstiel.tex:
Definiert Kopf- und Fußzeilen, Seitenränder etc.

### Silbentrennung.tex:
Eigene Definitionen für Silbentrennung mit den "hyphenation"-Package.

Trennvorschläge im Text werden mit \"angegeben
untrennbare Wörter und Ausnahmen von der normalen Trennung können in dieser Datei mittels \hyphenation definiert werden.

### Sperrvermerk.tex:
Sperrvermerk (Vertraulichkeitserklärung) für die Bachelorarbeit.

### Deckblatt.tex:
Deckblatt der Arbeit.

### Abstract.tex:
Abstract der Arbeit.

### Eidesstattliche_Erklaerung.tex:
Eidesstattliche Erklärung über die eigenständige Erstellung der Bachelorarbeit. \
**Muss ggf. für andere Wissenschaftlichearbeiten angepasst werden.**

**Muss unterschreiben werden!** 

### Abkuerzungsverzeichnis.tex:
Alphabetische Liste, die die verwendeten Abkürzungen mit ihrer Bedeutung aufführt. \
Ist selbständig zu ergänzen.

### Einleitung.tex:
Der Einleitungsteil der Arbeit.

### Problemstellung_Ziele_Vorgehensweise.tex:
Der Haupteil der Arbeit, der die Problemstellung, die Ziele, die Vorgehensweise beinhaltet.

### Fazit_Zukunftsausblick_Handlungsempfehlung.tex:
Das Fazit der Arbeit, der auch den Zukunftsausblick und Handlungsempfehlung beinhaltet.
### references.bib
Bibliographiemanagement mit Bibtex.

### Anhang.tex
Der Anhang der Arbeit.