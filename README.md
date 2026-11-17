# SONQIVO – Music Practice Studio

Das Übungsstudio für Musiker: Songs langsamer spielen **ohne Tonhöhenänderung**, Tonhöhe ändern, Passagen als A-B-Loop wiederholen, Marker setzen, Equalizer, Tempo-Trainer, Bibliothek mit Playlisten und Notizen – als eigenständiges Windows-Programm.

© 2026 Thorsten Opificius

## Download
Die aktuelle Version steht unter **[Releases](../../releases/latest)**.

- **`SONQIVO-Setup.exe`** – Installer (empfohlen): installiert ohne Administratorrechte, legt auf Wunsch ein Desktop-Symbol und einen Startmenü-Eintrag an und lässt sich über „Apps & Features“ deinstallieren.
- **`SONQIVO-portable.zip`** – ohne Installation: entpacken und `SONQIVO.exe` starten.

> Windows meldet beim ersten Start evtl. „Der Computer wurde durch Windows geschützt“ (SmartScreen), weil das Programm noch nicht signiert ist. Mit **Weitere Informationen → Trotzdem ausführen** startet es.

## Funktionen
| Funktion | Free | Pro |
| --- | :---: | :---: |
| Abspielen, Tempo (ohne Tonhöhe), Tonhöhe, A-B-Loops, Marker | ✔ | ✔ |
| Bibliothek, Playlisten, Notizen, Tags bearbeiten | bis 10 Songs | unbegrenzt |
| Spektrumanalyzer | ✔ | ✔ |
| Playlist-Backup importieren (`.sonqpack`) | ✔ | ✔ |
| Playlist-Backup erstellen (Export) | – | ✔ |
| Metronom synchron zum Song, Taktraster, Einrasten von Loops/Markern | – | ✔ |
| Farbschemata: Dunkel, Dunkelgrau, Hell | ✔ | ✔ |
| Oberfläche in Deutsch oder Englisch (umschaltbar unter System → Einstellungen) | ✔ | ✔ |
| Equalizer (6 Bänder) | – | ✔ |
| BPM-Erkennung | – | ✔ |
| Tempo-Trainer (von xx % bis max. xx %, mit großer Tempoanzeige) | – | ✔ |
| Gespeicherte Loop-Regionen | – | ✔ |
| Getunte Songs als MP3 speichern | – | ✔ |

Pro wird mit einem persönlichen Lizenzschlüssel freigeschaltet (Reiter „Lizenz & Updates“). Ein Schlüssel gilt für alle Updates innerhalb einer Hauptversion (z. B. alle 1.x-Versionen).

## Playlist-Backup
In der Pro-Version: Rechtsklick auf eine Playlist → **Backup erstellen (Export) …** sichert die Playlist mit den Original-Audiodateien und den gespeicherten Einstellungen in einer `.sonqpack`-Datei (ZIP). Wählbar sind einzelne Songs und die Inhalte: Audiodateien, Tags, Notizen, Tunings, Marker, Loops. Das Importieren ist auch in Free möglich: **📦 Import** in der Seitenleiste oder per Drag & Drop der Datei ins Fenster. Songs, die schon in der Bibliothek sind, werden nicht doppelt angelegt; die Free-Grenze von 10 Songs wird beachtet.

> **Urheberrecht:** Das Backup ist für die Sicherung der eigenen Playlist gedacht. Die Weitergabe urheberrechtlich geschützten Materials (z. B. MP3-Dateien) an andere ist verboten.

## Metronom und Taktraster (Pro)
Der Klick läuft synchron zu den Schlägen im Song und folgt dem Tempo-Regler. Tempo und Startpunkt bestimmt SONQIVO automatisch („Automatisch ausrichten“); von Hand lässt sich nachjustieren. Senkrechte Rasterlinien in der Wellenform zeigen die Schläge, Loops und Marker rasten auf Wunsch am Raster ein. Bei live gespielten Songs mit schwankendem Tempo kann ein festes Raster driften. Eine Feinkorrektur für die Geräte-Latenz steht unter System → Einstellungen.

## System-Menü
Über **⚙ System** in der Kopfzeile erreichst du die Einstellungen (Farbschema, Metronom-Feinkorrektur), „Was ist neu“, Kontakt und „Fehler melden“.

## Daten
Importierte Songs, Notizen und Einstellungen liegen unter `%APPDATA%\SONQIVO`. Die Originaldateien bleiben unverändert.

## Updates
SONQIVO prüft beim Start (abschaltbar) auf neue Versionen über die Releases dieser Seite. Dabei wird nur die kleine Datei `version.json` abgerufen; der Server sieht dabei technisch bedingt die IP-Adresse.

## Änderungen
Siehe [CHANGELOG.md](CHANGELOG.md).
