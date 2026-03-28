# Datenschutz-Scout – Interaktive Lernübung

Schülerinnen und Schüler lernen spielerisch, persönliche Daten im Netz zu schützen. Szenariobasiert, mit Punktesystem und gestuften Hilfen.

## Was ist das?

Eine einzelne HTML-Seite mit einer interaktiven Lernübung zum Thema Datenschutz und Datenmissbrauch-Vermeidung. Gedacht als Selbstlernmaterial für die Mittelstufe, einbettbar per iframe in Moodle oder direkt im Browser nutzbar.

**Zielgruppe:** Klasse 7–10 (Realschule / Gymnasium)
**Bearbeitungszeit:** ca. 20–30 Minuten
**Vorwissen:** Keins erforderlich (Erstkontakt mit dem Thema Datenschutz)

## Inhalte

Die Übung ist in sechs Phasen gegliedert:

1. **Einstieg** – Selbst-Check: Welche Daten habe ich schon online geteilt?
2. **Datenkategorien** – Drag & Drop: harmlos, sensibel, hochsensibel unterscheiden
3. **Daten-Check** – Vier Fragen vor jeder Dateneingabe (Wer fragt? Warum? Muss ich das? Was kann passieren?)
4. **Szenarien-Parcours** – Fünf Alltagssituationen mit Punktesystem (Apps, Gewinnspiele, Social Media, KI-Chatbots, Gaming)
5. **Hilfe-Netzwerk** – Anlaufstellen bei Problemen (Lehrkräfte, Vertrauenslehrkräfte, Schulsozialarbeit, Eltern, ältere Schülerinnen und Schüler, externe Beratung)
6. **Sicherung** – Fünf Aufgaben mit 3-Versuche-System, gestuften Hilfen, Ergebnisübersicht, Druck- und Markdown-Export

## Live ansehen

👉 [https://mgkurz.github.io/datenschutz-scout/](https://mgkurz.github.io/datenschutz-scout/)

## Einsatz in Moodle

Per iframe einbetten:

```html
<iframe src="https://mgkurz.github.io/datenschutz-scout/" width="100%" height="800" frameborder="0"></iframe>
```

## Technik

- Eine einzige `index.html` – kein Framework, kein Build-Step
- Alle Inhalte direkt in der Datei (HTML + CSS + JS)
- Responsive (iPad + Laptop), touch-optimiert
- Datenschutzerklärung integriert (Hash-Routing, keine zweite Datei)
- Keine externen Abhängigkeiten – keine Cookies, kein Tracking, keine CDN-Schriften
- Offline-fähig
- DSGVO-konform

## Deployment

Datei `index.html` ins Repo legen, GitHub Pages auf den `main`-Branch zeigen lassen. Fertig.

## Lizenz

CC BY-SA 4.0 · Hessische Lehrkräfteakademie · Martin Kurz

## Kontakt

Martin Kurz, Hessische Lehrkräfteakademie, Dezernat II.3 Medien
E-Mail: martin.kurz@bildung.hessen.de
