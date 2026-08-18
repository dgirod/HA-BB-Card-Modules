# Custom Badges - Modul

## Zweck: 
Es fügt dem Haupt-Icon einer Bubble Card konfigurierbare Mini-Badges / Status-Abzeichen hinzu.

## Wichtigste Features: 
*	**Positionierung:** Badges können in einer der vier Ecken des Icons platziert werden (top-right, top-left, bottom-right, bottom-left).
*	**Inhalt:** Anzeige von MDI-Icons, aktuellen Sensor-Zuständen (show_state), Attributwerten oder individuellem Text (custom_text mit {state}-Platzhalter).
*	**Dynamisches Design:** Unterscheidet zwischen Icon-Badges (kreisförmig) und Text-Badges (Pill-Form), skaliert Icon- und Schriftgröße automatisch passend zur Badge-Grösse.
*	**Bedingungen & Effekte:** Unterstützt Sichtbarkeits-Bedingungen (condition) und Animationen (z. B. glow, fade).

**Installation:**

1. Inhalt der YAML-Datei kopieren
2. In Home Assistant im Bubble Card Editor der jeweiligen Karte auf **"Import from YAML"** klicken
3. Den kopierten Inhalt einfügen und speichern
4. Im Editor unter **Badges** die gewünschten Badges konfigurieren (Icon, Entity, Attribut, Text, Farbe, Größe, Animation, Sichtbarkeits-Bedingung)
