# Mami-Startseite: Feature-Dokumentation

Diese Datei dokumentiert alle Features der Startseite und dient als Checkliste nach Updates.

---

## 1. Anzeige-Elemente

| Feature | Beschreibung | Status |
|---------|--------------|--------|
| **Digitale Uhr** | Aktuelle Uhrzeit im Format HH:MM, gut lesbar aus Entfernung | Aktiv |
| **Datumsanzeige** | Wochentag, Tag, Monat, Jahr in deutscher Sprache | Aktiv |
| **Wetter-Anzeige** | Aktuelles Wetter fuer Pullach mit Temperatur, Wind und freundlichen Kommentaren | Aktiv |

---

## 2. Nachrichten & Kommunikation

| Feature | Beschreibung | Status |
|---------|--------------|--------|
| **Nachrichten von den Soehnen** | Zeigt Nachrichten von Daniel und Joachim | Aktiv |
| **Profilbilder** | Avatar neben jeder Nachricht (Daniel.jpg, Joachim.jpg) | Aktiv |
| **Zeitstempel** | Relative Zeit ("Heute", "Gestern", konkrete Daten) | Aktiv |
| **Neu-Indikator** | Pulsierende Animation fuer neue Nachrichten (< 5 Stunden alt) | Aktiv |

---

## 3. Termine & Erinnerungen

| Feature | Beschreibung | Status |
|---------|--------------|--------|
| **Bevorstehende Termine** | Naechste 2 Tage aus Google Kalender | Aktiv |
| **Termin-Formular** | Textfeld + Button zum Eintragen neuer Termine | Aktiv |
| **Erinnerungen fuer heute** | Liste der heutigen Erinnerungen aus Google Sheet | Aktiv |

---

## 4. Hinweis-Sticker

| Feature | Beschreibung | Position | Status |
|---------|--------------|----------|--------|
| **Ruhiger Hinweisbereich** | Hinweise zur Bezahlung und zu Betrugsanrufen | Nach den Nachrichten | Aktiv |

---

## 5. Warnungen

| Feature | Beschreibung | Status |
|---------|--------------|--------|
| **Batterie-Warnung** | Banner bei Akkustand <= 30% mit Bitte, Tablet zu laden | Aktiv |

---

## 6. Externe Integrationen

| Integration | Zweck | Status |
|-------------|-------|--------|
| **Google Kalender (iCal)** | Termine abrufen | Aktiv |
| **Open-Meteo API** | Wetterdaten fuer Pullach | Aktiv |
| **Google Sheets** | Nachrichten und Erinnerungen | Aktiv |
| **Google Apps Script** | Neue Termine speichern | Aktiv |
| **Fully Kiosk Browser API** | Batteriestand des Tablets | Aktiv |

---

## 7. Dekorative Elemente (Hintergrund-Szene)

| Element | Beschreibung | Status |
|---------|--------------|--------|
| **Sommer-Gradient** | Heller Verlauf aus Naturweiss, frischem Gruen und Himmelblau | Aktiv |
| **Sonnenlicht** | Warmer, dezent pulsierender Schein oben links | Aktiv |
| **Farb-Orbs** | Ruhige abstrakte Farbformen fuer raeumliche Tiefe | Aktiv |
| **Sommerblaetter** | Zwei dezent im Wind schwebende Blaetter | Aktiv |
| **Reduzierte Bewegung** | Animationen respektieren die Systemeinstellung | Aktiv |

---

## Entfernte Features (Historie)

| Feature | Entfernt am | Grund |
|---------|-------------|-------|
| SmugMug Foto-Slideshow "Avignon" | 2026-05-16 | Nicht mehr benoetigt |
| "Gedanke fuer heute" (Sprichwoerter) | 2026-05-16 | Vereinfachung |
| "Literatur-Herausforderung" (Quiz) | 2026-05-16 | Vereinfachung |

---

## Checkliste nach Updates

Nach jedem groesseren Update diese Features pruefen:

- [ ] Uhrzeit wird korrekt angezeigt und ist gut lesbar
- [ ] Datum wird korrekt angezeigt (Wochentag, Tag, Monat, Jahr)
- [ ] Wetter wird geladen und zeigt Temperatur, Wind, Kommentar
- [ ] Nachrichten von den Soehnen werden angezeigt
- [ ] Profilbilder erscheinen neben Nachrichten
- [ ] Neue Nachrichten haben pulsierenden Indikator
- [ ] Termine aus Google Kalender werden geladen
- [ ] Termin-Formular funktioniert (Eingabe + Absenden)
- [ ] Erinnerungen fuer heute werden angezeigt
- [ ] Gelber Sticker links sichtbar
- [ ] Grauer Sticker rechts sichtbar
- [ ] Batterie-Warnung erscheint bei niedrigem Akku
- [ ] Sommer-Hintergrund mit Sonnenlicht und Farbformen wird angezeigt
- [ ] Uhrzeit und Datum sind auch aus groesserer Entfernung sehr gut lesbar
- [ ] Nachrichtentext ist gross, kontrastreich und klar dem Absender zugeordnet

---

*Letzte Aktualisierung: 2026-08-08*
