# Tagwerk als App auf Android installieren

Tagwerk ist eine installierbare Web-App. Chrome auf Android installiert sie wie eine normale App: mit eigenem Symbol in der App-Übersicht, im Vollbild und auch offline. Damit Chrome sie installieren kann, muss sie einmal über eine https-Adresse erreichbar sein. Beide Wege unten sind kostenlos.

## Schritt 1: Online stellen (einmalig, am PC)

**Variante A: Netlify Drop (am schnellsten, ca. 2 Minuten)**
1. Die ZIP-Datei entpacken.
2. https://app.netlify.com/drop öffnen und den entpackten Ordner `tagwerk-app` auf die Seite ziehen.
3. Kostenloses Konto anlegen, damit die Seite dauerhaft bleibt.
4. Die angezeigte Adresse notieren (z. B. `https://xyz-123.netlify.app`). Unter „Site settings“ lässt sich der Name ändern.

**Variante B: GitHub Pages**
1. Auf GitHub ein neues öffentliches Repository anlegen, z. B. `tagwerk`.
2. Alle Dateien aus dem Ordner hochladen („Add file“ → „Upload files“).
3. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
4. Nach etwa einer Minute ist die App unter `https://<dein-name>.github.io/tagwerk/` erreichbar.

## Schritt 2: Auf dem Handy installieren

1. Die Adresse in **Chrome** öffnen.
2. Menü ⋮ → **„App installieren“** (oder „Zum Startbildschirm hinzufügen“ → „Installieren“).
3. Fertig: Tagwerk erscheint mit Symbol in der App-Übersicht und startet ohne Browserleiste.

## Wichtig zu den Daten

- Alle Daten liegen **nur auf dem Handy**, nicht im Internet. Die Adresse liefert nur die App aus, deine Aufgaben werden dort nicht gespeichert.
- Wenn du die App deinstallierst oder die Chrome-Websitedaten löschst, sind die Daten weg.
- Daher regelmäßig sichern: **Missionen → Daten → „Als Datei sichern“**. Mit **„Datei laden“** spielst du eine Sicherung wieder ein, auch auf einem anderen Gerät.

## Updates

Neue Version einfach erneut hochladen (Netlify: neuen Ordner auf die Seite ziehen; GitHub: Dateien ersetzen). Die App lädt das Update beim nächsten oder übernächsten Öffnen. Deine Daten bleiben dabei erhalten.

## Mail → Aufgabe

- **Teilen (installierte App):** In der Mail den Betreff bzw. Text markieren → „Teilen“ → **Tagwerk**. Es öffnet sich „Aufgabe aus E-Mail“ mit Titel und Text. Mission und Tag wählen, speichern.
  Gmail kann ganze Mails nicht an andere Apps teilen, nur markierten Text. Andere Mail-Apps (z. B. Outlook, K-9) bieten teils „Teilen“ für die ganze Mail.
- **Einfügen:** In Tagwerk auf **✉ Aus Mail** tippen und den kopierten Mailtext einfügen. Zeilen wie „Betreff:“ und „Von:“ werden erkannt, „AW:/WG:/Re:/Fwd:“ entfernt.
- Damit Tagwerk im Teilen-Menü erscheint, nach dem Update die App **einmal deinstallieren und neu installieren** (deine Daten vorher unter Missionen → Daten → „Als Datei sichern“ sichern).
