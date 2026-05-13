# ESP32 Marauder – Cheap Yellow Display (CYD) Edition
### Mit GPS-Support, Akku-Betrieb & externer Antenne

<p align="center">
  <img alt="Marauder logo" src="https://github.com/BlushTTV/Esp32_Marauder_Cheap_Yellow_Display_CYD_Deutsch/blob/main/Bilder/logo01.png?raw=true" width="300">
  <br>
  <a href="https://wigle.net">
    <img border="0" src="https://wigle.net/bi/E1+Rgd7Wm_rhGyoeZMfB0w.png">
  </a>
</p>

Dieses Repository bietet eine deutsche Anleitung und Ressourcen, um das **Cheap Yellow Display (CYD)** in ein mobiles **ESP32 Marauder** Kraftpaket mit GPS-Tracking und verbesserter Reichweite zu verwandeln.

---

## 🛠 Hardware-Einkaufsliste

Um das volle Potenzial (GPS & Mobilität) auszuschöpfen, werden folgende Komponenten empfohlen:

| Komponente | Beschreibung | Link |
| :--- | :--- | :--- |
| **Display** | CYD Display (ESP32-2432S028) inkl. 4-pol Kabel | [Amazon](https://www.amazon.de/dp/B0CSYPG716) |
| **GPS Modul** | NEO-6M oder NEO-M8N kompatibel | [Amazon](https://amzn.eu/d/0e4LMSs0) |
| **Akku** | 3700mAh 3.7V Lipo Akku | [Amazon](https://www.amazon.de/dp/B08215B4KK) |
| **Anschluss** | JST-Stecker (für lötfreien Akku-Anschluss) | [Amazon](https://www.amazon.de/dp/B07VYR7J49) |
| **Ladeplatine** | Li–Ion Lithium-USB-C Lader (Step-Up optional) | [Amazon](https://www.amazon.de/dp/B0BZSB3SBN) |
| **Schalter** | Mini-Schiebeschalter (Power On/Off) | [Amazon](https://www.amazon.de/dp/B08SJ2HVQB) |
| **ESP32U** | Nur zum Entlöten für den Antennenanschluss | [Amazon](https://www.amazon.de/dp/B08BZKZXLL) |
| **WLAN Antenne** | High-Gain Antenne für ESP32U | [Amazon](https://www.amazon.de/dp/B07YCBRTFB) |
| **GPS Antenne** | GPS L1 Antenne (Helix oder SMA) | [Beitian Store](https://store.beitian.com/products/beitian-drone-uav-rtk-gnss-helix-antenna-gps-bds-glonass-galileo-sma-j-bt-560-560l5-502-603-564-t009-t076-104-230l2-230l5?variant=44743070875935) |

> [!TIP]
> **Pro-Tipp:** Wenn du den ESP32U Chip auf das CYD lötest, kannst du eine externe WLAN-Antenne nutzen, was die Reichweite massiv erhöht! Eine Anleitung dazu findest du [hier](https://github.com/BlushTTV/Esp32_Marauder_Cheap_Yellow_Display_CYD_Deutsch/blob/main/ESP%20L%C3%B6tanleitung.md).

---

## 📐 3D-Druck & Gehäuse
Die STL-Dateien für das passende Gehäuse findest du im Ordner [3D Druck STL's](./3D%20Druck%20STL's).

* **Status:** Die Dateien werden laufend optimiert.
* **Geplant:** Ein breiteres Gehäuse mit seitlichem Ausgang für die WLAN-Antenne.
* **Service:** Falls du keinen 3D-Drucker hast oder ein fertiges Gehäuse benötigst, melde dich gerne bei mir auf Discord!

---

## 💾 Kompatible Firmware
Hier sind die besten Möglichkeiten, die Software auf dein Device zu bringen:

* 🚀 **Empfohlen:** [Marauder WebFlasher (fzeeflasher)](https://fzeeflasher.com/) – Immer aktuell, einfach über den Browser für CYD 2432S028.
* 📜 **Legacy:** [Marauder WebFlasher (Fletcher)](https://fr4nkfletcher.github.io/Adafruit_WebSerial_ESPTool/) – Ältere Versionen verfügbar.
* 🧪 **Alternative:** [Bruce: Predatory](https://github.com/pr3y/Bruce) oder [Ghost ESP](https://github.com/Spooks4576/Ghost_ESP) (Hinweis: Teilweise instabil oder Entwicklung eingestellt).

---

## 📸 Impressionen
<p align="center">
  <img src="https://github.com/BlushTTV/Esp32_Marauder_Cheap_Yellow_Display_CYD_Deutsch/blob/main/Bilder/IMG_4117.png?raw=true" width="45%">
  <img src="https://github.com/BlushTTV/Esp32_Marauder_Cheap_Yellow_Display_CYD_Deutsch/blob/main/Bilder/IMG_4591.png?raw=true" width="45%">
</p>

---

## 🤝 Support & Community
Hast du Fragen zum Löten, der Hardware oder der Einrichtung? Tritt unserem Discord bei:
**[HIER DEM DISCORD BEITRETEN](https://discord.com/invite/sW4CYXz8QA)**

---

## ❤️ Danksagungen
Ein großes Dankeschön für die Pionierarbeit an:
* [**JustCallMeKoko**](https://github.com/justcallmekoko) – Schöpfer des [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder).
* [**Fr4nkFletcher**](https://github.com/Fr4nkFletcher) – Für die Bereitstellung der englischen CYD-Anleitung.

---

## ⚠️ Haftungsausschluss / Disclaimer
Dieses Projekt dient ausschließlich **Bildungszwecken**. Holen Sie immer eine ordnungsgemäße Genehmigung ein, bevor Sie in Netzwerken testen, die Ihnen nicht gehören. Der Autor übernimmt keine Haftung für Sachschäden oder rechtliche Konsequenzen!
