﻿# Personenlisten exakt sortieren

Das Auflisten mehrerer Personen funktioniert in der Regel über sog. _**Listing Grids**_. Beim Listing Grid könnt ihr in den Einstellungen _Posts Query_, entweder _Tax Query_ oder _Posts & Author Parameters_ nutzen. Im Anschluss könnt ihr über _Order & Offset_ die Einträge sortieren.

![Listing Grid als Widget](/static/graphicsregio/2-personenliste1.jpeg)

![Listing Grid auf der Personenseite](/static/graphicsregio/2-personenliste2.jpeg)

**Beispiele** für Listing Grids findet ihr z.B. unter

-   [https://julis.de/personen/](https://julis.de/personen/)
    
-   [https://julis.de/abgeordnete/](https://julis.de/abgeordnete/)
    
-   [https://julis.de/geschaeftsstelle/](https://julis.de/geschaeftsstelle/)
    
-   [https://julis.de/bundesarbeitskreise/](https://julis.de/bundesarbeitskreise/)
    

Damit diese aber richtig gestyled sind, nehmt am besten die Vorlagen auf den entsprechenden Seiten oder [**kopiert ein Listing Grid von der Musterseite**](/Regiosystem/Konfiguration/Neue%20Seite%20anlegen%20&%20Musterseite.md).

## Einbinden von Personen

### Tax Query

Hiermit könnt ihr ganze **Personenkategorien** auflisten. Dazu gebt ihr einfach unter _**Terms**_  die ID der Personenkategorie (erneut in der URL zu finden) ein.

![](/static/graphicsregio/2-personenliste3.jpeg)

### Posts & Author Parameters

Hiermit könnt ihr **eine oder mehrere Personen** auflisten. Dazu gebt ihr einfach unter _Terms_ die IDs (erneut in der URL zu finden) der entsprechenden Personen getrennt durch ein Komma ein. Über die Ergänzung eines _Order&Offset-_Elements unter _Posts Query_ könnt ihr diese sortieren.

![](/static/graphicsregio/2-personenliste4.jpeg)

### Personen-ID oder Kategorie-ID finden

Um Personen oder Personenkategorien bei Beiträgen einzubinden, öffnet das entsprechende Personenprofil im WordPress-Backend. In der URL findet ihr dann eine ID, die ihr zum Einbinden benötigt. Z. B.:

https://regio.julis.de/mallorca/wp-admin/post.php?post=12345&action=edit -> **Hier ist die ID: 12345**

## Sortieren von Personen

Dazu nutzt ihr ein sog. _Order & Offset-Element_.

![](/static/graphicsregio/2-personenliste5.jpeg)

**Die einfachste Sortierung ist das manuelle Einstellen in Kombination mit den Posts & Author Parameters. Dazu gebt ihr schlichtweg die IDs in der richtigen Reihenfolge an und klickt beim Sortieren auf "preserve order...".**

![](/static/graphicsregio/2-personenliste6.jpeg)

Aber es lassen sich auch individuelle Sortierungen anhand des Titels, der Menüreihenfolge, des Datums etc. einstellen. Probiert dafür einfach die Optionen unter Order und Order by aus.

![](/static/graphicsregio/2-personenliste7.jpeg)