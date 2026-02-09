# Vitakreis - Modulare Struktur

Die HTML-Datei wurde in übersichtliche Module aufgeteilt.

## 📁 Dateistruktur

```
├── index.html                  (Haupt-Datei - lädt alle Komponenten)
├── styles.css                  (alle CSS-Styles)
├── hero-irene.html            (Hero-Section mit Irene)
├── gallery-orga-reviews.html  (Laufende Galerie, Orga & Bewertungen)
├── kostenrechner.html         (Vitakreis Kostenrechner)
├── kontakt-maps.html          (Kontaktformular & Google Maps)
└── faq.html                   (FAQ & Jobs-Bereich)
```

## 🚀 Installation

1. Alle Dateien in dasselbe Verzeichnis kopieren
2. `index.html` im Browser öffnen oder auf Webserver hochladen

## ⚠️ Wichtig

**Lokales Testen:** Wegen CORS-Einschränkungen muss die Seite über einen lokalen Webserver laufen, nicht direkt als `file://`.

### Schneller lokaler Server:

**Python 3:**
```bash
python -m http.server 8000
```
Dann öffne: http://localhost:8000

**Node.js:**
```bash
npx http-server
```

**PHP:**
```bash
php -S localhost:8000
```

**VS Code:** Installiere die Extension "Live Server" und klicke auf "Go Live"

## ✅ Vorteile der modularen Struktur

- ✓ Übersichtlicher und wartbarer Code
- ✓ Einzelne Komponenten können unabhängig bearbeitet werden
- ✓ Schnelleres Debugging
- ✓ Wiederverwendbare Komponenten
- ✓ Bessere Teamarbeit möglich

## 🔧 Komponenten bearbeiten

1. Öffne die entsprechende HTML-Komponente (z.B. `hero-irene.html`)
2. Bearbeite den Inhalt
3. Speichern - Änderungen sind sofort sichtbar (nach Browser-Refresh)

## 🎨 Styles bearbeiten

Alle CSS-Styles befinden sich in `styles.css`. Änderungen gelten für alle Komponenten.

## ⚡ Performance

Die Komponenten werden asynchron geladen. Das initiale Laden kann minimal verzögert sein,
aber die Seite bleibt responsiv und der Code ist deutlich übersichtlicher.

---

Bei Fragen: Einfach melden! 🚀
