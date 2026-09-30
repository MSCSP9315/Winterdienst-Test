# Winterdienst Süd – V3.7
Durchgehende straßennetzbasierte Test-Routenlogik.

- 207 Räumabschnitte im aktuellen Süd-Arbeitsbereich.
- V3.5/V3.6 Räumprofile werden übernommen.
- Breite Straßen erzeugen zwei gerichtete Räumgänge.
- Der zweite Durchgang derselben breiten Straße wird bei vorhandenen Alternativen bewusst nicht sofort als U-Turn zurückgefahren.
- Zwischen Räumaufträgen wird auf dem vorhandenen Straßengraph eine kürzeste Verbindungsfahrt berechnet und orange als Überfahrt dargestellt.
- Start und Rückkehr: Werkhof Gaswerkstrasse 2.
- Kantons-/höherklassige Straßen können intern als notwendige Verbindung dienen, werden aber nicht als Räumauftrag angezeigt.
- Explizit private/gesperrte OSM-Wege sind aus dem Routinggraph ausgeschlossen.

Hinweis: Der hochgeladene OSM-Ausschnitt deckt den westlichen Rand des ursprünglichen Süd-Plans nicht vollständig ab.
