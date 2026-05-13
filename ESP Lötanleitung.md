# 🛠 ESP32 auf ESP32U Umlöten
### Anleitung, Zubehör und Sicherheitshinweise

Um eine externe Antenne an deinem CYD nutzen zu können, muss der Standard-ESP32-Chip gegen eine **U-Variante (mit IPX/U.FL Buchse)** ausgetauscht werden. Hier findest du das benötigte Equipment und wichtige Tipps für den Umbau.

---

## 🧰 Benötigtes Werkzeug & Material

Für diesen Umbau ist eine Heißluftstation zwingend erforderlich, da die Kontakte unter dem Chip (Thermal Pad) mit einem normalen Lötkolben nicht erreichbar sind.

| Werkzeug | Empfehlung / Beschreibung | Link |
| :--- | :--- | :--- |
| **Heißluft-Station** | Preiswerte Station, ideal für gelegentliche SMD-Arbeiten. | [Amazon](https://www.amazon.de/dp/B0CGNFK249) |
| **Lötpaste** | Erleichtert das saubere Verbinden der SMD-Kontakte. | [Amazon](https://www.amazon.de/dp/B0DBLQH34L) |
| **ESD Klebeband** | **(Optional)** Schützt umliegende Bauteile vor Hitze. | [Amazon](https://www.amazon.de/dp/B07W7RD1NB) |
| **Dritte Hand** | **(Optional)** Zur stabilen Fixierung des Boards. | [Amazon](https://www.amazon.de/L%C3%B6tstation-Lupenlampe-Metallarme-Liebhaber-Schmuckhersteller/dp/B09Y982LZR/) |

---

## 💡 Tipps für den Umbau

1. **Schutz:** Nutze das **Kapton/ESD-Klebeband**, um die umliegenden Bauteile (Widerstände, Kondensatoren) abzukleben. So verhinderst du, dass sie durch den Luftstrom weggeblasen werden, wenn das Lot schmilzt.
2. **Dosierung:** Trage die Lötpaste nur sehr dünn auf die Pads auf. Zu viel Paste kann Kurzschlüsse unter dem Chip verursachen.
3. **Geduld:** Erhitze den Chip gleichmäßig kreisend, bis er sich fast von selbst bewegen lässt. Hebe ihn vorsichtig mit einer Pinzette ab.

---

## 📸 Vorbereitung

![Lötpaste](https://github.com/BlushTTV/Esp32_Marauder_Cheap_Yellow_Display_CYD_Deutsch/blob/main/Bilder/IMG_4110.png?raw=true)
*Präzises Auftragen der Lötpaste ist der Schlüssel zum Erfolg.*

---

## ⚠️ Haftungsausschluss
Lötarbeiten an elektronischen Bauteilen erfordern Erfahrung. Ich übernehme **keine Haftung** für Schäden an deiner Hardware, verbrannte Bauteile oder Verletzungen durch unsachgemäßen Gebrauch der Werkzeuge! Durchführung auf eigene Gefahr.
