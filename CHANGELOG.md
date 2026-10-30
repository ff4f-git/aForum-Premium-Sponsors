# Versionsgeschichte

Zusammenfassung der bisherigen Layout- und Funktionsstände aus der Projektdokumentation. Die vollständige Historie steht in den [Git-Commits](https://github.com/ff4f-git/aForum-Premium-Sponsors/commits/main/).

## Dokumentationsüberarbeitung

- Neue Projektübersicht mit Screenshot des Sponsorbereichs auf aforum.net.
- Vollständige Beschreibung der aktuellen globalen Einstellungen und Partnerfelder.
- Mobile Auswahl, Begrenzung auf drei Partner und unterstützte Pfade anhand des Codes präzisiert.
- Ältere Änderungsnotizen aus der README hier zusammengefasst.

## Version 11 · Hauptreiter

- Sponsorleiste zusätzlich auf Kategorien, Aktuell, Neu und Heiß beziehungsweise Top.
- Steuerung über die vorhandene Einstellung `show_on_categories`.
- Startseite `/` bleibt unabhängig von dieser Einstellung berücksichtigt.

## Version 10 · Bildskalierung

- Individuelle Skalierung pro Partner mit `image_scale`.
- Bereich 90–110 %, Standard 100 %.
- Kachel, Werbelabel und Pfeil bleiben von der Bildskalierung unabhängig.

## Version 9 · Proportionaler Pfeil

- Pfeilgröße folgt der Kachelhöhe.
- 23 % der Höhe, begrenzt auf 22–55 px.
- Kräftigeres SVG-Chevron.

## Version 8 · Gewichtete mobile Auswahl

- Mobil bis 760 px eine ausgewählte Kachel.
- Individuelle Gewichte von 0–20.
- Stabile Auswahl bei DOM-Neurendern; neue Auswahl bei vollständigem Reload möglich.

## Version 7 · Mobile Breite

- Eigene mobile Rasterregeln für die volle verfügbare Inhaltsbreite.
- Schutz gegen zu schmale Kacheln durch allgemeine Theme-Regeln.

## Version 6 · Werbekennzeichnung

- Dezentes „WERBUNG“-Label mit einstellbarer Farbe.
- Rotes Chevron mit weißem SVG-Pfeil.
- Partnername als Alternativtext und Link-Beschriftung statt sichtbarer Bildüberlagerung.

## Version 5 · Höhe & Ecken

- Globale Einstellungen für Kachelhöhe und Eckenradius.

## Version 4 und frühere Stände · Grundlage

- Bis zu drei Partner in einem dreispaltigen Desktop-Raster.
- Uploads und externe Bildadressen.
- Proportionale Bilddarstellung, individuelle Hintergrundfarben und Reihenfolge.
- Einfügen unmittelbar vor der Forennavigation.

Für aktuelle Werte, Einschränkungen und Installationsschritte gilt die [README](README.md).
