# Winterdienst Süd V4.1 – PC + Tablet Live-GPS

Neu gegenüber V4.0:
- Live-GPS mit navigator.geolocation.
- Fahrzeugmarker folgt der echten GPS-Position.
- Navi-Karte folgt dem Fahrzeug automatisch.
- Tatsächlich gefahrene GPS-Spur wird grün aufgezeichnet.
- Distanz im Navi wird anhand der aktuellen Position bis zum Ende des aktuellen Schritts aktualisiert.
- Automatischer Wechsel zum nächsten Navi-Schritt, wenn das Ende des Abschnitts erreicht wurde.
- Warnung bei deutlicher Abweichung von der geplanten Route.
- GPS-Genauigkeit und Geschwindigkeit werden angezeigt.
- „Fahrzeug folgen“ kann ein/aus geschaltet werden.
- PC-Simulation über Weiter/Zurück bleibt vollständig erhalten.
- „Zur Kartenansicht“ beendet das Navi nicht; beim erneuten Öffnen bleibt der aktuelle Stand erhalten.

Wichtig für Tablet-Test:
- Live-GPS im Browser sollte über HTTPS laufen.
- GitHub Pages ist dafür geeignet.
- Lokal am PC bleibt der Simulationsmodus der zuverlässigste Testweg.

Test am PC:
1. ZIP entpacken.
2. START-WINTERDIENST.bat öffnen.
3. Route berechnen.
4. FZ-Navi starten.
5. Weiter/Zurück verwenden.

Tablet:
1. Version über GitHub Pages öffnen.
2. Standortfreigabe erlauben.
3. FZ-Navi öffnen.
4. Live-GPS starten.
