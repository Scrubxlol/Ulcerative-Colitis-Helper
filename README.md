# Health Tracker – Toilette • Intervallfasten • Medikamente

Single-File Web App (nur **index.html**). Keine weiteren Dateien nötig. Speichert lokal im Browser (localStorage).

## Schnellstart
1. Diese Repo-Struktur:
   ```
   /
   ├─ index.html
   └─ README.md
   ```
2. `index.html` lokal doppelklicken → App läuft im Browser.
3. **Export**: TXT/JSON direkt aus der App (Buttons im Bereich „Export & Sicherung“).
4. **Import**: JSON-Datei wieder einlesen.

## GitHub hochladen (inkl. GitHub Pages)
1. Neues Repository auf GitHub anlegen (Public oder Private).
2. `index.html` (und optional diese README) hochladen → Commit.
3. In den Repo **Settings → Pages**:
   - **Source**: „Deploy from a branch“
   - **Branch**: `main` und **/ (root)** auswählen → **Save**.
4. Nach ein paar Sekunden erscheint oben die Pages-URL. Diese URL ist deine Web-App.

> Hinweis: Die App ist client‑seitig, es werden **keine Daten an einen Server gesendet**. Alle Daten liegen im Browser‑Speicher des jeweiligen Geräts.

## Funktionen
- **Toilette**: Urin/Stuhlgang mit Zeit, Blut (ja/nein), Konsistenz (fest/mittel/flüssig), Notiz. Aufwachzeit & Cutoff (z.B. 22:00) für die „Toilettenphase“ (Aufwachen → letzter Stuhl ≤ Cutoff).
- **Intervallfasten**: „Letzte Mahlzeit (Start)“ und „Erste Mahlzeit (Ende)“, Sessions & Ø der letzten 7/30 Tage.
- **Medikamente**: Täglich Morgen/Abend abhaken, Tabelle der letzten 7 Tage.
- **Export/Import**: TXT-Zusammenfassung + Rohdaten (JSON), JSON-Export/Import, Reset‑Funktion.

## Datenschutz
- Alle Daten liegen **nur lokal** im Browser (`localStorage`).
- Für Backup zwischen Geräten: JSON exportieren und auf dem anderen Gerät importieren.
