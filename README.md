# Winterdienst V4.4.2 – breite Straßen / Seitenwechsel korrigiert

Grund für das bisher gleiche Verhalten:
V4.4 hatte zwar die neue Trennlogik, aber breite Straßen wurden nicht automatisch auf 2× gesetzt. Zusätzlich konnte eine opportunistisch mitgenommene erste Straßenseite unmittelbar vor der zweiten Seite landen.

V4.4.2 behebt beides:
- breite Straßen automatisch 2×, wenn OSM 2+ Fahrspuren oder mindestens 5.0 m Breite enthält
- Süd: 11, Nord: 17, West: 1 automatisch erkannte breite Abschnitte
- alte gespeicherte V4.3/V4.4-Modi werden für diesen Teststand nicht übernommen
- direkte Gegenfahrt auf derselben breiten Teilstrecke wird auch bei produktiver Mitnahme verhindert
- Ziel: möglichst Räumen statt Leerfahrt, Gegenrichtung erst später
- manuelle Korrektur bleibt jederzeit möglich
