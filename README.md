# intallylight

> Tallylight für Blackmagic ATEM Mixer using ESP8266 (Wemos D1 Mini)
> 
---

## 📦 Beschreibung

## ⚙️ Funktion

Dieses Projekt verwandelt einen Wemos D1 mini in ein WLAN-basiertes **Tally-Light-System** für **Blackmagic ATEM Switcher**.

- Anzeige von „Program“ (rot) und „Preview“ (grün)
- Konfigurierbare LED-Modi und -Farben
- Webinterface zur Einrichtung (Name, IP, LED-Modi etc.)
- Unterstützung für statische IPs
- Statusanzeige via Neopixel-LEDs

---

## 📦 Ordnerstruktur


/
├── ATEMmin/           # Kasper Skårhøjs ATEM Arduino-Bibliothek
├── ATEMstd/           # ATEM Bibliotheken
├── ESP8266WiFi/       # WiFi-spezifische Libraries
├── TallyServer/       # Kommunikationsmodul für Tally Server
├── intallylight_v3.ino # Hauptsketch für den Wemos

---

## 🛠️ Hardware

| Komponente                | Modell                      |
|---------------------------|-----------------------------|
| Mikrocontroller           | Wemos D1 Mini (ESP8266)     |
| LED-Modul                 | WS2812B 2x2 RGB (HW-222)     |
| Widerstand                | 22 Ohm (zwischen D6 und DIN) |
| Stromversorgung           | 5V USB                       |

## 📷 Beispiel-Schaltung:  

![intally_v2_bb](https://github.com/user-attachments/assets/7d32ac5a-a302-421a-b9c5-45a871125dd4)

---

## 🔌 Pinbelegung

| ESP8266 (D1 Mini) | LED Modul (HW-222) |
|------------------|---------------------|
| D6               | DIN (über 22 Ohm)   |
| 5V               | VCC                 |
| G                | GND                 |

---


