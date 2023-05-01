﻿# Konfiguration

## Lua

Es gibt eine `Config`-Eigenschaft an jedem Knoten.

todo: Beschreibung key vs. idx Zugriff

## Actions

Es gibt zwei *actions*, die die Konfiguration anzeigen.

`config`
: Formatierter Inhalt mit inclusive Defaultwerte.

`configRaw`
: Xml-Präsentation des Knotens


## Fehlersuche

Im Fehlerfall wird die erzeugte Konfiguration unter `%temp%\des.xml` abgelegt.

Damit die Konfiguration immer geschrieben wird, die Eigenschaft `OutputTemp` in der Kommandozeile auf `true` setzen.

```cmd
DEServer.exe run -c cfg\Kunde.xml -v OutputTemp=true
```