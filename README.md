# Winterdienst Süd V4.2 – optimierter Praxistest

Diese Version ist für den ersten möglichst realistischen Routentest gedacht.

Verbessert gegenüber V4.1.3:
- globale Optimierung der gesamten Tour statt nur "nächste günstige Straße"
- mehrere Startvarianten + lokale Verbesserungsschritte
- flexible Fahrtrichtung bei normalen Räumstraßen
- breite Straßen bleiben zwei getrennte gerichtete Räumgänge
- Gegenrichtung breiter Straßen wird wirtschaftlich in die Gesamttour eingeordnet
- Einbahnstraßen aus OSM werden beim internen Routing berücksichtigt
- echte kürzeste Verbindungswege über das Straßennetz
- Start und Rückkehr Werkhof Gaswerkstrasse 2
- Vergleich mit einer einfachen Schnellroute: Leerfahrt-Ersparnis wird angezeigt
- Live-GPS, automatisches Mitfahren, Abweichungswarnung, Kartenansicht und FZ-Navi aus V4.1.3 bleiben erhalten
- akzeptierter Süd-Sektor bleibt unverändert

Datengrundlage:
- 142 Räumabschnitte im aktuellen Süd-Sektor
- 1065 routbare OSM-Wege im Ausschnitt
- 201 relevante End-/Startknoten für die globale Optimierung
- Distanzmatrix einmalig vorab berechnet, damit die Optimierung auch auf dem Tablet schnell bleibt

Wichtig:
Die App kann die wirtschaftlichste Route nur für die Straßen optimieren, die als "räumen" bzw. "beide Richtungen" markiert sind.
Vor dem echten Wintereinsatz müssen die tatsächlichen Räumprofile (breit / nur Überfahrt / nicht räumen) einmal fachlich bestätigt werden.

GitHub:
Für den Test genügt die neue index.html.
