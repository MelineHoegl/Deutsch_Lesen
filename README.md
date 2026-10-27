# Lesespuren – Deutsch

Digitale Lesespuren für die Leseförderung (Mittelschule, Jgst. 5/6), optimiert für iPads.

**Startseite:** `index.html` – zeigt alle Lesespuren als Kacheln.

## Aufbau

```
index.html          Startseite
lesespuren.js       Liste aller Lesespuren (hier neue eintragen)
lesespuren/         die einzelnen Lesespuren als HTML-Dateien
```

## Neue Lesespur hinzufügen

1. Die HTML-Datei in den Ordner `lesespuren/` hochladen (Dateiname ohne Leerzeichen und Umlaute, z. B. `der-geheime-schatz.html`).
2. In `lesespuren.js` einen Eintrag ergänzen:

```js
{
  titel: "Der geheime Schatz",
  datei: "lesespuren/der-geheime-schatz.html",
  thema: "Piraten",
  fach: "Deutsch",
  text: "Kurzer Satz, worum es geht.",
  bild: "🏴‍☠️",
  stufen: ["★", "★★", "★★★"],
  neu: true,
},
```

Die Startseite zeigt die neue Lesespur danach automatisch an.

## Datenschutz

Die Lesespuren speichern und übertragen keine Daten. Es gibt keine Anmeldung.
