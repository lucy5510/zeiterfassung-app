Zeiterfassung – PWA Version 22 (lokale Testversion)

Inhalt: index.html, manifest.webmanifest, service-worker.js, Icons.

WICHTIG: Nicht direkt aus dem Chat oder per Doppelklick auf index.html testen.
Die PWA braucht eine FESTE HTTPS-Adresse oder localhost. Die Daten bleiben
auf dem jeweiligen Gerät/im Browserprofil; noch KEINE Serverdatenbank,
keine echte Büroübertragung und keine Mehrbenutzer-Anmeldung.

PC-Test (Python muss installiert sein):
1. ZIP in einen Ordner entpacken.
2. In diesem Ordner eine Konsole öffnen.
3. python -m http.server 8000
4. In demselben Browser http://localhost:8000/index.html öffnen.
5. Tätigkeit starten, Browser-Tab schließen, dieselbe URL wieder öffnen.
6. Testweise Internetverbindung ausschalten: localhost funktioniert weiter.
7. Unter Browser-Einstellungen ggf. 'App installieren' auswählen.

Auf einem Handy benötigt die PWA eine feste HTTPS-Hosting-Adresse;
localhost auf dem PC ist nicht vom Handy erreichbar.

Lokale Speicherung: IndexedDB mit localStorage als zusätzlichem Fallback.
Daten können trotzdem verloren gehen, z.B. bei gelöschten Browserdaten,
privatem Modus, Speicherbeschränkungen oder Geräteverlust.
Bitte regelmäßig 'Sicherung exportieren' nutzen. Nur Testdaten verwenden.
Die automatische Synchronisierung mit dem Büro folgt in einer späteren Phase.
