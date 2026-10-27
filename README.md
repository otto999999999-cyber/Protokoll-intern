# Ablauf-Assistent der Wohnraumverwaltung — stillgelegt

**Status: deaktiviert / offline.** Der Assistent wurde in den „Ruhestand" versetzt.

## Zugriffsstatus (für Dritte geschlossen)
- **Repository: privat** → der Quelltext ist für Außenstehende **nicht einsehbar**.
- **GitHub Pages: abgeschaltet** → die frühere öffentliche Adresse
  `otto999999999-cyber.github.io/Protokoll` **liefert nichts mehr aus** (404).

➡️ Damit ist die App **für Dritte/Außenstehende nicht mehr erreichbar.**

## Noch zu erledigen: lokale Kopien auf den Geräten
Wer die App früher im Browser geöffnet oder „zum Startbildschirm/als App"
installiert hat, kann noch eine **lokal gespeicherte Offline-Kopie** (PWA/Cache)
haben. Diese liegt **nur auf dem jeweiligen Gerät** – kein Dritter kann sie sehen –,
sollte aber entfernt werden. Das geht **nur lokal auf jedem Gerät** (nicht aus der
Ferne, da die Seite bewusst offline ist):

### PC (Chrome / Edge)
1. Falls als App installiert: `chrome://apps` bzw. `edge://apps` öffnen →
   „Ablauf-Assistent" → Rechtsklick → **Entfernen / Deinstallieren**.
2. Websitedaten löschen: Einstellungen → Datenschutz → **Browserdaten löschen** →
   „Cookies und andere Websitedaten" + „Bilder und Dateien im Cache" auswählen →
   löschen. (Oder gezielt beim Öffnen der Seite: Schloss-Symbol links neben der
   Adresse → **Cookies und Websitedaten** → löschen.)
3. Browser schließen und neu öffnen.

### iPhone / iPad
1. Home-Symbol „Ablauf-Assistent" gedrückt halten → **App entfernen** → **App löschen**.
2. Einstellungen → **Safari** → **Erweitert** → **Website-Daten** → `github.io`
   suchen → nach links wischen → **Löschen**.
3. Gerät neu starten.

Danach ist auch die lokale Kopie weg; neu laden ist nicht möglich (Pages ist aus).

## Reaktivierung (nur falls je gewünscht)
Der App-Code liegt weiterhin im Repo (Abläufe in `daten.js`, Schulungsvideo,
Icons). Zum Wieder-Aktivieren müsste GitHub Pages neu eingerichtet werden.
Achtung: Bei einem **privaten** Repo erfordert Pages einen bezahlten GitHub-Plan;
andernfalls müsste das Repo wieder **öffentlich** gestellt werden – dann wäre der
Quelltext erneut öffentlich einsehbar.

## Interne Nutzung ohne Internet (optional)
Soll die App **intern** (ohne GitHub/Internet) weitergenutzt werden, lässt sie sich
direkt vom Netzlaufwerk betreiben. Dafür müsste sie wieder zu **einer**
eigenständigen HTML-Datei zusammengeführt werden (aktuell ist sie in `chatbot.html`
+ `daten.js` aufgeteilt, und `chatbot.html` ist derzeit die Abschaltseite).
Bei Bedarf bitte separat anstoßen.
