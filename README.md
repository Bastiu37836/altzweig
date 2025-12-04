# Sebastian-Altzweig
Persönliche Portfolio-Webseite

## Über das Projekt

Dies ist eine moderne, responsive Portfolio-Webseite für die Präsentation von 2D- und 3D-Kunstwerken.

## Features

- **Responsive Design**: Optimiert für Desktop, Tablet und Mobile
- **Moderne Navigation**: Fixed Navigation mit smooth scrolling
- **2D Kunst Galerie**: Showcase für digitale Illustrationen und Konzeptkunst
- **3D Kunst Galerie**: Showcase für 3D-Modelle und Renderings
- **Kontakt-Sektion**: Einfache Kontaktaufnahme über E-Mail und soziale Netzwerke

## Struktur

```
├── index.html          # Haupt-HTML-Datei
├── css/
│   └── style.css       # Styling und Layout
├── js/
│   └── main.js         # JavaScript für Interaktivität
└── README.md           # Diese Datei
```

## Lokale Entwicklung

Um die Webseite lokal zu testen:

```bash
# Mit Python
python3 -m http.server 8080

# Dann im Browser öffnen: http://localhost:8080
```

## Anpassung

### Bilder hinzufügen

Ersetzen Sie die Platzhalter-Elemente in `index.html` durch echte Bilder:

```html
<div class="gallery-item">
    <img src="pfad/zum/bild.jpg" alt="Beschreibung">
    <div class="gallery-overlay">
        <h3>Projekt Titel</h3>
        <p>Kategorie</p>
    </div>
</div>
```

### Kontaktdaten aktualisieren

Bearbeiten Sie die Kontakt-Sektion in `index.html` mit Ihren echten Kontaktdaten.

## Lizenz

© 2024 Sebastian Altzweig. Alle Rechte vorbehalten.
