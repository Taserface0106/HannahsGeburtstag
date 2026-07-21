# Das Geheimnis von Blackwood Manor 🏰

Ein Point-and-Click-Geburtstagsspiel, gebaut mit HTML, CSS und JavaScript.

## Was du noch ergänzen musst

Bevor du das Spiel hochlädst, führst du einmal das Download-Skript aus (siehe unten) und ergänzt die beiden Audiodateien direkt im Hauptordner (kein `assets/`-Unterordner mehr nötig):

```
geschenke-spiel/
├── index.html          (bereits fertig)
├── download-bilder.sh / .bat  (einmal ausführen, siehe oben)
├── rooms/           ← wird durch das Download-Skript automatisch befüllt
├── items/           ← wird durch das Download-Skript automatisch befüllt
└── audio/
    ├── tuer.mp3              ← Sound beim Wechseln des Raums / Tür öffnen
    ├── hintergrund-musik.mp3 ← Background-Musik (läuft in Dauerschleife)
    └── keller.mp3            ← Alternative Musik, läuft nur solange man im Keller ist
```

Die Dateinamen müssen **exakt** so lauten, wie oben angegeben (Groß-/Kleinschreibung beachten), sonst findet das Spiel sie nicht.

Das Extra-Geschenk im Büro (Schreibtischschublade → "dr3i"-Karte) führt direkt zu
einem iCloud-Link mit den Dateien — der Link ist schon fest im Code hinterlegt,
keine ZIP-Datei nötig.

## Wie du es auf GitHub Pages hostest (kostenlos)

1. Erstelle ein neues Repository auf GitHub (z. B. `blackwood-manor`).
2. Lade `index.html` sowie die Ordner `rooms/`, `items/` und `audio/` (mit den ergänzten Dateien) hoch.
3. Gehe in den Repository-Einstellungen zu **Settings → Pages**.
4. Wähle als Source den `main`-Branch und den Root-Ordner `/ (root)`.
5. Nach ein paar Minuten ist das Spiel live unter:
   `https://DEIN-USERNAME.github.io/blackwood-manor/`

## Spielübersicht

**Außen:** Vor dem Haus, Garten (Schlüssel unter einem Blumentopf)

**Erdgeschoss:** Empfang, Korridor, Speisezimmer, Bibliothek, Wohnzimmer, Küche

**1. Stock:** Korridor, Badezimmer, Büro (verschlossen — braucht den Garten-Schlüssel),
Musikzimmer, Schlafzimmer (ganz hinten im Gang — hier ist das Hauptgeschenk hinter
dem Bild versteckt)

**Extra-Geschenk:** Im Büro, in der Schreibtischschublade, liegt ein Kästchen mit
einer "dr3i"-Karte. Antippen führt direkt zum iCloud-Link mit den Dateien.

**Fortschritt:** Wird bewusst NICHT gespeichert — jedes Öffnen der Seite startet
das Spiel komplett neu von vorn.

## Falls du noch Änderungen willst

Sag mir einfach Bescheid — ob am Text, an den Bildern, an der Navigation oder am
Gameplay. Ich pass alles gerne an.
