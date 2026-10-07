Ein Script, das YouTube um über 20 Funktionen erweitert. Läuft als Userscript (Tampermonkey) oder direkt in der Browser-Konsole.

Funktionen
Wiedergabe
Auto HD – Stellt automatisch die höchste verfügbare Videoqualität ein.

Geschwindigkeit – Regler von 0,25x bis 4x. Bleibt nach Neuladen erhalten.

Video loopen – Video läuft in Endlosschleife.

Werbung überspringen – Klickt automatisch den Skip-Button, sobald er erscheint.

Endscreen ausblenden – Entfernt die Empfehlungen am Videoende.

Infokarten ausblenden – Blendet Teaser und Info-Karten im Player aus.

Volume-Boost – Lautstärke bis 500% über die Web Audio API.

Feed
Shorts ausblenden – Entfernt Shorts aus Feed, Suche und Seitenleiste.

Werbung ausblenden – Versteckt Werbe-Slots im Feed.

Gesehene dimmen – Bereits angesehene Videos werden abgeblendet.

Empfehlungen ausblenden – Blendet die rechte Spalte auf der Watch-Seite aus.

Kommentare ausblenden – Versteckt den Kommentarbereich.

Kopfzeile verstecken – Masthead fährt beim Scrollen aus dem Bild.

Aussehen
AMOLED-Schwarz – Tiefes Schwarz statt Dunkelgrau.

Breiter Kinomodus – Nutzt mehr vertikalen Raum im Theatermodus.

Kompaktes Grid – Engere Abstände zwischen Video-Kacheln.

Scrollbar verstecken – Entfernt den Scrollbalken.

Tools
Screenshot – Speichert den aktuellen Frame als PNG.

Thumbnail-Download – Lädt das Thumbnail in höchster Auflösung.

Sauberer Link – Kopiert youtu.be/ID ohne Tracking-Parameter.

Video-Info kopieren – Titel, Kanal, Zeit und Link in die Zwischenablage.

Vollbild – Browser-Vollbildmodus.

Kino-Modus – YouTube-Theatermodus.

Bild-in-Bild – PiP-Fenster.

Installation
Als Userscript (dauerhaft)
Tampermonkey im Browser installieren.

Neue Datei youtube-plus.user.js anlegen.

Code einfügen und speichern.

youtube.com öffnen.

Als Konsolen-Script (temporär)
youtube.com öffnen.

F12 drücken und zum Tab "Konsole" wechseln.

Script aus youtube-plus.js einfügen und Enter drücken.

Nach Neuladen der Seite muss das Script in der Konsole erneut ausgeführt werden. Einstellungen bleiben trotzdem gespeichert.

Verwendung
Unten rechts erscheint ein runder Button. Klick darauf öffnet das Menü. Vier Tabs:

Wiedergabe

Feed

Aussehen

Tools

Jede Zeile ist ein Schalter. Klick drauf zum Ein-/Ausschalten. Alle Einstellungen landen im localStorage und bleiben beim nächsten Besuch erhalten.

Tastenkürzel
Tasten	Funktion
Alt + K	Menü öffnen/schließen
Alt + S	Shorts ein/aus
Alt + W	Werbung ein/aus
Alt + D	AMOLED ein/aus
Alt + P	Bild-in-Bild
