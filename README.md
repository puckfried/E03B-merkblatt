# Übersicht HTML und CSS Befehle

Hier findet ihr eine fortlaufende Übersicht über unsere bislang kennengelernten Elemente in HTML und die CSS Eigenschaften. Die Übersicht wird in den nächsten Tagen immer um die neuen Werte ergänzt.
<br><br>

## Übersicht
1. [HTML-Elemente](#html-elemente)
   - [Grundstruktur](#0-grundstruktur-einer-html-seite)
   - [Head-Elemente](#1-head-elemente-erscheinen-nicht-auf-der-seite-sondern-nur-infos-für-den-browser-und-google)
   - [Body-Elemente](#2-body-elemente-der-sichtbare-bereich-eurer-webseite)
       - [Block Elemente](#21-block-elemente-nehmen-die-gesamte-breite-des-bildschirms-ein)
2. [Nützliche Tastenkombinationen](#nützliche-tastenkombinationen-windows)

<br><br><br>

## HTML-Elemente

**HTML** steht für ***Hypertext Markup Language*** und ist eine Auszeichnungssprache, die verwendet wird, um den Inhalt einer Webseite zu strukturieren und zu kennzeichnen. Mit HTML können verschiedene Elemente wie Überschriften, Absätze, Bilder und Links definiert werden. Diese Elemente können dann mit CSS gestaltet werden, um eine ansprechende Webseite zu erstellen. <br>
Folgende Elemente haben wir bislang kennengelernt: 

### 0. Grundstruktur einer HTML-Seite

| HTML-Element    | Beschreibung                                    | Beispiel                              |
|:---------------:|:-----------------------------------------------:|:-------------------------------------:|
| `<!DOCTYPE html>`| Definiert den Dokumenttyp und die HTML-Version  | `<!DOCTYPE html>`                     |
| `<html>`        | Wurzelelement einer HTML-Seite                  | `<html>...</html>`                    |
| `<head>`        | Enthält Metadaten und Links zu Stylesheets etc. | `<head>...</head>`                    |
| `<body>`        | Enthält den sichtbaren Inhalt der Webseite      | `<body>...</body>`                    |
<br>

***Beispiel***

```
<!DOCTYPE html>
<html>
    <head>...</head>
    <body>...</body>
</html>
```

<br>

### 1. Head-Elemente (erscheinen nicht auf der Seite, sondern nur Infos für den Browser und Google)

| HTML-Element | Beschreibung                                           | Beispiel                                 |
|:------------:|:------------------------------------------------------:|:----------------------------------------:|
| `<title>`    | Titel der Webseite, erscheint in der Browser-Tab-Leiste | `<title>Meine Webseite</title>`          |
| `<meta>`     | Metainformationen, z.B. Zeichensatz oder Keywords       | `<meta charset="UTF-8">`                 |
| `<link>`     | Verknüpfung mit externen Dateien, z.B. CSS-Stylesheets  | `<link rel="stylesheet" href="style.css">`|

### 2. Body-Elemente (der sichtbare Bereich eurer Webseite)
    
#### 2.1 Block-Elemente (nehmen die gesamte Breite des Elternelements ein)

| HTML-Element  | Beschreibung                               | Beispiel                             |
|:-------------:|:------------------------------------------:|:------------------------------------:|
| `<h1>`...`<h6>` | Überschriften                            | `<h1>Überschrift</h1>`               |
| `<p>`          | Textabsatz                                | `<p>Textabsatz</p>`                  |

#### 2.2 Inline Elemente (nehmen nur die Breite ihres Inhalts)

| HTML-Element | Beschreibung                    | Beispiel                              |
|:------------:|:-------------------------------:|:-------------------------------------:|
| `<a>`        | Hyperlink (intern, extern)      | `<a href="url">Linktext</a>`          |

### Allgemeine Tastenkombinationen

Tastenkombinationen, die in **VS Code** und anderen Programmen funktionieren:

- Fenster wechseln --> `Alt` + `Tab`
- Kopieren        --> `STRG` + `c`
- Ausschneiden    --> `STRG` + `x`
- Einfügen        --> `STRG` + `v`
- Suchen          --> `STRG` + `f`
- Speichern       --> `STRG` + `s`
- alles markieren --> `STRG` + `a`


### VS-Code

Diese praktischen Kombinationen funktionieren nur in VS Code:
- `Alt` + `Pfeiltaste`  --> Zeilen verschieben, hoch/runter
- `Alt` + `z`           --> Zeilenumbruch anschalten/ausschalten
- `STRG`+ `#`           --> erzeugt einen Kommentar 
- `STRG`+ `l`           --> Zeile markieren


#### Emmet Abkürzungen in VS Code

Emmet sind Kurzformen, die VS Code zu Code umschreibt, hier einige kurze Beispiele für ***HTML***:
- `!`               --> erzeugt in einen Boilerplate-Code (Grundstruktur)