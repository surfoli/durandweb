<div align="center">
  <img src="assets/images/logo.png" alt="Durand Web Studio Logo" width="300">
</div>

# Durand Web Studio

Eine moderne, responsive Website gehostet auf Netlify.

## 🚀 Live Website

Die Website ist live unter: [Ihre Netlify-URL hier einfügen]

## 📁 Projektstruktur

```
durandweb/
│
├── index.html         → Startseite
├── about.html         → Über mich Seite
├── contact.html       → Kontaktseite mit Netlify Forms
│
├── /assets
│   ├── /css
│   │   └── style.css  → Modernes, responsives Design
│   ├── /js
│   │   └── script.js  → Interaktive Funktionen
│   └── /images
│       └── olivier.jpg → Profilbild (bitte hinzufügen)
│
└── README.md
```

## 🎨 Features

- **Responsive Design**: Funktioniert perfekt auf Desktop, Tablet und Mobile
- **Modernes UI**: Sauberes, professionelles Design mit CSS Grid und Flexbox
- **Kontaktformular**: Integriert mit Netlify Forms für E-Mail-Empfang
- **SEO-optimiert**: Meta-Tags und semantisches HTML
- **Performance**: Optimierte Ladezeiten und Bilder
- **Accessibility**: Barrierefrei und benutzerfreundlich

## 🖼️ Foto hinzufügen

1. Fügen Sie Ihr Profilbild als `olivier.jpg` in den Ordner `/assets/images/` hinzu
2. Empfohlene Größe: 400x400px (quadratisch)
3. Dateigröße: Unter 1MB für optimale Performance

## 🌐 Netlify Deployment

### Erste Einrichtung:

1. **Repository zu Netlify verbinden**:
   - Gehen Sie zu [netlify.com](https://netlify.com)
   - Klicken Sie auf "New site from Git"
   - Verbinden Sie Ihr GitHub-Repository

2. **Build-Einstellungen**:
   - Build command: (leer lassen)
   - Publish directory: `/` (Root-Verzeichnis)

3. **Domain konfigurieren**:
   - Netlify gibt Ihnen automatisch eine kostenlose Subdomain
   - Optional: Eigene Domain verbinden

### Automatische Updates:

- Jeder Git-Push zu `main` löst automatisch ein neues Deployment aus
- Änderungen sind in 1-2 Minuten live

## 🛠️ Lokale Entwicklung

```bash
# Repository klonen
git clone git@github.com:surfoli/durandweb.git
cd durandweb

# Lokalen Server starten (optional)
python -m http.server 8000
# oder
npx serve .

# Website öffnen
open http://localhost:8000
```

## 📧 Kontaktformular

Das Kontaktformular ist bereits für Netlify Forms konfiguriert:
- Nachrichten werden automatisch an Ihre E-Mail weitergeleitet
- Spam-Schutz durch Honeypot-Feld
- Form-Validierung mit JavaScript

## 🔧 Anpassungen

### Inhalte ändern:
- Texte in den HTML-Dateien bearbeiten
- Farben in `assets/css/style.css` anpassen (CSS-Variablen am Anfang)

### Design anpassen:
- CSS-Variablen in `style.css` für Farben und Abstände
- Responsive Breakpoints bei Bedarf anpassen

### Neue Seiten hinzufügen:
- Neue HTML-Datei erstellen
- Navigation in allen Dateien aktualisieren

## 🚀 Performance

- Optimierte CSS und JavaScript
- Lazy Loading für Bilder
- Minimale externe Abhängigkeiten
- Lighthouse Score: 95+

## 📱 Browser-Unterstützung

- Chrome/Edge: Vollständig unterstützt
- Firefox: Vollständig unterstützt  
- Safari: Vollständig unterstützt
- Mobile Browser: Optimiert für alle Geräte

## 📞 Support

Bei Fragen oder Problemen:
- GitHub Issues erstellen
- E-Mail: olivierdurand.privat@gmail.com

---

**Erstellt mit ❤️ für eine moderne Web-Präsenz**
Website: Durand Web Studio – Olivier Durand
