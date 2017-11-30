# Uhrzeit-In-Worten
Zeigt die aktuelle Uhrzeit menschlich lesbar in Wörtern da auf dem Desktop dar.

*Interested in an english version? Check out the original version from [raphaelhanneken](https://github.com/raphaelhanneken/time-in-words)*

![Uhrzeit in Worten Screenshot](https://raw.githubusercontent.com/xremix/Uhrzeit-In-Worten/master/screenshot_detail.png)

## Installation

1. [Übersicht](http://tracesof.net/uebersicht/) herunterladen und installieren
2. [Download](https://github.com/xremix/Uhrzeit-In-Worten/releases/) des Widgets
3. Kopiere den `uhrzeitinworten.widget` Ordner in deinen Widget Ordner. Du findest eine Anleitung dazu auch auf der [Übersicht Webseite](http://tracesof.net/uebersicht-widgets/)
4. Fertig!

## Notizen

Aktuell ist das Widget so ausgerichtet, dass es immer neben dem Dock angezeigt wird, so dass Fenster das Widget nicht verdecken.
Dies kann in der `index.coffee`-Datei aber auch über die Position angepasst werden:

```coffee
  position:
    top:    "auto"
    bottom: "1%"
    left:   "1%"
    right:  "auto"
```

![Uhrzeit in Worten Übersicht Screenshot](https://raw.githubusercontent.com/xremix/Uhrzeit-In-Worten/master/screenshot_overview.png)