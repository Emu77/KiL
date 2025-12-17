# 📱 Kugel im Labyrinth

**Kugel im Labyrinth** ist ein mobiles Browser-Spiel, entwickelt und getestet
für den **lokalen Einsatz im Firefox-Browser**.  
Die Steuerung erfolgt ausschließlich über die **Neigung des Smartphones**.

Das Spiel besteht aus einer einzelnen HTML-Datei und läuft komplett lokal.

Dateiname:
**Kugel_im_Labyrint.html**

---

## Installation (lokal)

1. Speichere die Datei **Kugel_im_Labyrint.html** im Gerätespeicher
2. Öffne die Datei direkt im **Firefox-Browser**
3. Tippe im Spiel auf **Start**
4. Erlaube den Zugriff auf die Bewegungssensoren

Das Spiel läuft ohne Internetverbindung und ohne weitere Installation.

---

## Spielprinzip & Anleitung

### Ziel
Bewege die Kugel durch das Labyrinth zum **roten Ziel**,  
ohne in eines der Löcher zu fallen.

---

### Steuerung
- Das Smartphone wird gekippt:
  - vor / zurück → Kugel bewegt sich vertikal
  - links / rechts → Kugel bewegt sich horizontal
- Die Stärke der Bewegung hängt von der Neigung des Geräts ab.

---

### Schwierigkeitsgrade
Vor dem Start kann ein Schwierigkeitsgrad gewählt werden:

- **Easy**  
  Ruhige, gut kontrollierbare Bewegung

- **Normal**  
  Ausgewogenes Spiel, präzise Steuerung erforderlich

- **🔥 Extreme Hard**  
  Sehr starke, nichtlineare Reaktion, größere Löcher
  und zusätzlicher Sog in Richtung der Löcher

Die Schwierigkeitsgrade verändern das Spielgefühl deutlich.

---

## Entstehung & Dokumentation

Dieses Spiel ist **iterativ im Dialog entwickelt** worden.

### Ausgangspunkt
- Inspiration: klassisches Spiel  
  *„Kugel im kippbaren Holzlabyrinth“*
- Ziel: eine einfache, lokale Umsetzung ohne App-Store,
  ohne Frameworks und ohne Abhängigkeiten

---

### Entwicklungsverlauf
- Erste Version:
  - einfache Kugel
  - einfache Wände
  - reine Gyro-Steuerung
- Früh erkannte Probleme:
  - Level teilweise nicht lösbar
  - Reset nach Lochkontakt führte zu Freeze
  - Zielkontakt wurde nicht immer erkannt
- Verbesserungen:
  - stabile Spielzustände
  - kontrollierte Labyrinth-Generierung
  - gezielte Platzierung der Löcher
  - zuverlässige Ziel-Erkennung
  - Endscreen nach dem letzten Level

---

### Spieler-Feedback
Während der Entwicklung wurde das Spiel mehrfach getestet,
unter anderem von einem Kind.

Ein prägendes Feedback war:
> „Die Schwierigkeitsgrade fühlen sich gleich an.“

Daraufhin wurden:
- nichtlineare Bewegungsfunktionen eingeführt
- der Hard-Modus deutlich verschärft
- Löcher spielmechanisch relevanter gemacht

---

## Technik

- HTML5 Canvas
- Vanilla JavaScript
- Web Audio API
- DeviceOrientation API
- Eine einzelne HTML-Datei
- Entwickelt und getestet im **Firefox (mobil)**

---

## Lizenz

Freie Nutzung für private und Lernzwecke.  
Keine Garantie – aber mit viel Sorgfalt entwickelt ❤️

---

Viel Spaß beim Spielen 🎮