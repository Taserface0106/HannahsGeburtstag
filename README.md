# Das Geheimnis von Blackwood Manor 🏰

Ein Point-and-Click-Geburtstagsspiel, gebaut mit HTML, CSS und JavaScript.

## Schritt 1: Bilder herunterladen

Alle Raum- und Gegenstands-Bilder werden lokal eingebunden (nicht mehr über
externe Links). Führe dazu einmal das mitgelieferte Skript aus, in dem Ordner,
in dem auch `index.html` liegt:

```bash
bash download-bilder.sh
```

Das lädt automatisch alle Bilder in `assets/rooms/` und `assets/items/`. Kein
manuelles Speichern nötig — nur einmal ausführen (Mac/Linux: direkt im
Terminal; Windows: über Git Bash oder WSL).

## Schritt 2: Restliche Dateien ergänzen

Danach müssen noch 3 weitere Dateien in den Ordner `assets/` gelegt werden:

```
geschenke-spiel/
├── index.html          (bereits fertig)
├── download-bilder.sh  (einmal ausführen, siehe oben)
├── assets/
│   ├── rooms/           ← wird durch das Skript automatisch befüllt
│   ├── items/           ← wird durch das Skript automatisch befüllt
│   ├── audio/
│   │   ├── tuer.mp3              ← Sound beim Wechseln des Raums / Tür öffnen
│   │   └── hintergrund-musik.mp3 ← Background-Musik (läuft in Dauerschleife)
│   └── geschenk.zip     ← Deine ZIP-Datei mit dem Extra-Geschenk (wird beim
│                            Anklicken der "dr3i"-Karte im Büro heruntergeladen —
│                            hat nichts mit dem Haupt-Theaterstück-Geschenk zu tun)
```

Die Dateinamen müssen **exakt** so lauten, wie oben angegeben (Groß-/Kleinschreibung beachten), sonst findet das Spiel sie nicht.

## Wie du es auf GitHub Pages hostest (kostenlos)

1. Erstelle ein neues Repository auf GitHub (z. B. `blackwood-manor`).
2. Lade `index.html` und den `assets/`-Ordner (mit den 3 ergänzten Dateien) hoch.
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
einer "dr3i"-Karte. Antippen löst den Download deiner ZIP-Datei aus.

**Fortschritt:** Wird automatisch im Browser gespeichert (localStorage) — falls
jemand die Seite schließt, geht nichts verloren.

## Falls du noch Änderungen willst

Sag mir einfach Bescheid — ob am Text, an den Bildern, an der Navigation oder am
Gameplay. Ich pass alles gerne an.
