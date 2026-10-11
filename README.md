# DentalCoach AI – Web-Prototyp

Interaktive React/Vite-Oberfläche für einen mandantenfähigen KI-Rezeptionstrainer für Zahnarztpraxen.

## Start

```bash
npm install
npm run dev
```

Danach die angezeigte lokale URL im Browser öffnen.

## Bereits enthalten
- Responsives Dashboard für Smartphone, Tablet und Desktop
- Auswahl von sechs fiktiven Beschwerdefällen
- Demonstrations-Textdialog mit lokalem Gesprächsverlauf
- Beispielhafte Teamübersicht und Anzeige abgeschlossener Demo-Transkripte
- Einfache Demo-Praxisverwaltung

## Nicht enthalten / keine Produktionsreife
- Keine Live-Sprach-KI, Audioaufzeichnung oder KI-Bewertung
- Keine Benutzeranmeldung, persistente Datenbank oder echte Mandantentrennung
- Keine datenschutzrechtliche Freigabe für Mitarbeiter- oder Patientendaten
- Demo-Gespräche werden nur im laufenden Browserzustand gehalten
- Teamstatistiken sind ausdrücklich Beispieldaten

## Nächste technische Schritte
1. Server-Backend mit echter Authentifizierung und Tenant-Isolation (PostgreSQL, Row-Level-Security plus serverseitige Prüfungen).
2. Kurzlebige serverseitig erzeugte Realtime-Sitzungen für KI-Sprachdialoge; API-Schlüssel nie im Browser hinterlegen.
3. Einwilligungs-/Rechtsgrundlagenprüfung für Aufzeichnung und personenbezogene Auswertung; Zugriffskontrollen, Löschfristen und Audit-Logs.
4. Audioaufzeichnung und Transkription in sicherem Speicher, getrennt pro Praxis.
5. Bewertungsrubrik mit nachvollziehbarer menschlicher Überprüfung und Einspruchs-/Korrekturmöglichkeit.
6. Hosting, Auftragsverarbeitung, Unterauftragsverarbeiter und Datenübermittlung prüfen.
