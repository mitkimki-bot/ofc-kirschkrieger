# OFC Kirschrieger – Mitgliederportal

Offizieller Fanclub Hamburger SV · Web-App

## Schnellstart

1. Dieses Repository auf GitHub hochladen
2. GitHub Pages aktivieren (siehe Anleitung unten)
3. `logo.jpg` im gleichen Ordner ablegen (dein Kirschrieger-Logo)
4. Fertig – App ist online!

## GitHub Pages aktivieren (Schritt für Schritt)

1. Gehe zu deinem Repository auf github.com
2. Klicke oben auf **Settings**
3. Klicke links auf **Pages**
4. Unter "Branch" wähle `main` und `/ (root)` → **Save**
5. Nach ~1 Minute ist die App erreichbar unter:
   `https://DEIN-USERNAME.github.io/REPO-NAME/`

## Logo einbinden

- Benenne dein Kirschrieger-Logo um zu: `logo.jpg`
- Lege es in denselben Ordner wie `index.html`
- Beim GitHub-Upload einfach beide Dateien hochladen

## Demo-Zugänge

| Benutzername | Passwort | Rolle |
|---|---|---|
| admin | admin | Administrator |
| kotte | 123 | HSV-Mitglied |
| ralf | 123 | HSV-Mitglied |
| gast | 123 | Fan-Mitglied |

## Funktionen

- **Spielplan** – HSV-Spiele mit Datum, Zeit, Wettbewerb
- **Kartenverwaltung** – HSV-Mitglieder: behalten oder abgeben; Fan-Mitglieder: anfragen
- **Fairness-System** – automatische Zuteilung nach wenigsten erhaltenen Karten (Losverfahren bei Gleichstand)
- **Nichtmitglieder-Vergabe** – nur wenn keine Fan-Anfragen offen sind
- **Mein Profil** – Foto hochladen, Anzeigename und Passwort ändern
- **Statistik** – Kartenverteilung aller Mitglieder
- **Admin** – Mitglieder verwalten, Zuteilungen überschreiben

## Nächste Schritte (für spätere Erweiterung)

- **Echte Spieldaten**: football-data.org API (kostenlos für 2. Bundesliga)
- **Datenbank**: Supabase (kostenlos, EU-Server Frankfurt, DSGVO-konform)
- **DSGVO**: Datenschutzerklärung und Einwilligung beim ersten Login ergänzen

## Code ändern mit Claude

Teile Claude einfach den Link zu deinem GitHub-Repository,
dann kann Claude den Code direkt lesen und weiterentwickeln.
