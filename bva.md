# Datenmodell BVA

## Teile

### Tabelle teiTeil

|Name|Typ|Beschreibung|
|-------:|--------|:-------:|
|Teil |Text   | Bezeichnung des Teils  |
|Beschreibung   |Text|beschreibender Text  |
|min|Zahl|Mindestbestand|
|max|Zahl|Maximalbestand|
|Familie|Text|Zuordnung zu teiFamilie|
|Bild|Text|Text|Zuordnung zu Bild|
|Geloescht|Flag|Kennzeichen, ob Datensatz deaktiviert wurde|

Beziehungen:
1-n Beziehung zu teiFamilie

### Tabelle teiFamilie

|Name|Typ|Beschreibung|
|-------:|--------|:-------:|
|Familie |Text   | Bezeichnung der Familie  |
|Geloescht|Flag|Kennzeichen, ob Datensatz deaktiviert wurde|

Beziehungen:
n-1 Beziehung zu teiTeil

## Auftrag