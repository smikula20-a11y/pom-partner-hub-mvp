# pom-partner-hub-mvp

Frontend-Mockup für das **Place of Motion Partner-Dashboard** inkl. **Kurs-Konfigurator MVP** (nur Frontend, keine API).

## Lokal testen
1. Abhängigkeiten installieren
   ```bash
   npm install
   ```
2. Entwicklungsserver starten
   ```bash
   npm run dev
   ```
3. Im Browser öffnen
   - http://localhost:4173

## Weitere Checks
```bash
npm run build
npm run lint
```

## Kurs-Konfigurator MVP (Frontend-only)
- Neue Seite: **Kurs-Konfigurator**
- Masterbibliothek mit Dummy-Assets (Video/PDF) inkl. Suche + Kategorie-Filter
- Builder für Kursdaten, Module und Lektionen
- Module/Lektionen erstellen, bearbeiten, löschen, hoch/runter sortieren
- Lektionen aus der Masterbibliothek hinzufügen
- Lektionseditor (Titel, Beschreibung, Dosierung, Hinweise, optional)
- Templates (Rückenfit 7 Tage, Nacken Basics, Knie Einstieg) mit Bestätigung beim Laden
- Autosave + manuelles Speichern via `localStorage`
- Export als JSON + Build Summary (Clipboard/TXT)
- Reset mit Bestätigungsdialog

## Wichtige Grenzen
- Kein Backend
- Keine Datenbank
- Keine echte Authentifizierung
- Keine ThriveCart API-Integration
- Keine Patientendaten
