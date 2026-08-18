# HA-BB-Card-Modules

Eigene Module für [Bubble Card](https://github.com/Clooos/Bubble-Card) in Homeassistant.

Jedes Modul liegt in einem eigenen Unterordner unter `modules/`.

## Module

### custom_badges

📄 [`modules/custom_badges/custom_badges.yaml`](modules/custom_badges/custom_badges.yaml)

Fügt dem Haupt-Icon einer Bubble Card ein oder mehrere kleine Badges hinzu. Jedes Badge kann ein eigenes Icon, den Zustand/ein Attribut einer Entity und/oder freien Text anzeigen, mit eigener Farbe, Größe, Animation und Sichtbarkeits-Bedingung.

**Installation:**

1. Inhalt der Datei [`custom_badges.yaml`](modules/custom_badges/custom_badges.yaml) kopieren
2. In Home Assistant im Bubble Card Editor der jeweiligen Karte auf **"Import from YAML"** klicken
3. Den kopierten Inhalt einfügen und speichern
4. Im Editor unter **Badges** die gewünschten Badges konfigurieren (Icon, Entity, Attribut, Text, Farbe, Größe, Animation, Sichtbarkeits-Bedingung)
