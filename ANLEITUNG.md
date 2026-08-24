# Lagerfeuer FM – ganz einfach online stellen (5 Minuten)

## 1. Cloudflare-Konto
Falls noch nicht vorhanden: **dash.cloudflare.com** → kostenlos registrieren.

## 2. Hochladen
1. Im Dashboard: **Workers & Pages** → **Create** → Tab **Pages** → **Upload assets**
2. Projektnamen vergeben, z. B. `lagerfeuer-fm`
3. Alle Dateien aus **diesem Ordner** (index.html, manifest.json, icons/, logos/) per
   Drag & Drop hochladen — am besten den ganzen Ordnerinhalt auf einmal reinziehen
4. **Deploy site** klicken

Fertig. Du bekommst eine Adresse wie `lagerfeuer-fm.pages.dev` – die kannst du mit
allen teilen, die beim Camping dabei sind.

## 3. Zum Startbildschirm hinzufügen
Die Adresse im Handy-Browser öffnen → Menü → **Zum Startbildschirm hinzufügen**.
Jetzt erscheint das Flammen-Icon, weil die Seite über eine echte https-Adresse mit
eigenem App-Icon läuft (ging bei der lokalen Datei vorher nicht).

## Wie das Speichern funktioniert
Eigene Sender, die du über "Eigenen Sender hinzufügen" einträgst, werden im Browser
auf deinem Gerät gespeichert (localStorage). Das heißt: jeder, der die App nutzt, kann
eigene Sender hinzufügen, aber diese werden nicht automatisch mit anderen geteilt –
jeder sieht nur seine eigenen zusätzlichen Sender. Die 5 vorinstallierten Sender mit
Logos sehen aber alle gleich.

Falls ihr das später doch zentral teilen wollt, sag Bescheid – das lässt sich jederzeit
nachrüsten.
