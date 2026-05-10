# Maison Amour — Website für eine Hochzeitsfotografin

Elegante statische Website mit Portfolio, Angebotssektion und Kontaktformular. Geeignet für GitHub Pages.

## Struktur

```text
index.html
assets/css/styles.css
assets/js/main.js
assets/img/IMG-20260503-WA0009.jpg
```

## Foto einfügen

Lege dein Foto in diesen Ordner:

```text
assets/img/IMG-20260503-WA0009.jpg
```

Der Code referenziert dieses Bild bereits an mehreren Stellen.

## Kontaktformular aktivieren

Aktuell ist ein Mailto-Fallback eingebaut. Für direkten Versand über GitHub Pages:

1. Bei Formspree ein Formular erstellen.
2. In `index.html` diese Zeile ersetzen:

```html
<form action="https://formspree.io/f/DEINE-ID" ...>
```

mit deiner echten Formspree-URL.

## GitHub Pages

1. Dateien in ein GitHub-Repository hochladen.
2. Unter Settings → Pages den Branch auswählen.
3. Nach kurzer Zeit ist die Website online.

## Branding anpassen

- Name/Logo: in `index.html` bei `Maison Amour` ändern.
- E-Mail: `hello@maison-amour.at` ersetzen.
- Texte: direkt in `index.html` bearbeiten.
