# Philosophie – Nachschlagewerk

Nachschlagewerk zur Philosophie: Disziplinen, Epochen und Denker in kurzen, verlinkten Artikeln.

**Live:** https://mvonulmerbach-ship-it.github.io/philo-nachschlagewerk/

## Inhalt

61 Artikel in diesen Bereichen: 🗺️ Grundlagen · 🧩 Disziplinen & Themen · 🏛️ Epochen & Strömungen · 🧠 Denker (47) · 📚 Service.

## Funktionen

- Menü ☰ mit allen Bereichen (am Desktop als Seitenleiste), Logo führt zur Startseite.
- Jeder Artikel hat eine eigene Adresse (z. B. `#ueberblick`), Querverweise im Text springen direkt zum Artikel.
- **Suche** über Titel und Text; Treffer im Titel stehen zuerst (exakt, dann Anfang, dann irgendwo im Titel, dann nur im Text).
- Hell/Dunkel oben rechts: ◐ System (Standard) · ☀️ Hell · 🌙 Dunkel. Die Wahl gilt für alle fünf Nachschlagewerke (`localStorage`, Schlüssel `nsw_theme`).
- Die Lern-App [Philosophie lernen](https://mvonulmerbach-ship-it.github.io/philo/) bettet das Nachschlagewerk ein und gibt dabei `?theme=dark|light` mit; dieser Parameter hat Vorrang.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | die ganze App (HTML, CSS, JavaScript und alle Artikel) |
| `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `icon-maskable.png` | Installation als App |
| `sw.js` | Service Worker für den Offline-Betrieb |

## Auf dem Handy installieren

Seite in Chrome öffnen → Menü ⋮ → „Zum Startbildschirm hinzufügen“ (Safari: Teilen → „Zum Home-Bildschirm“).

## Offline

Nach dem ersten Öffnen läuft das Nachschlagewerk ohne Netz (Service Worker, network first mit Cache als Rückfall).
