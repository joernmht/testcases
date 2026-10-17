# 3D Motor Visualisierung

Interaktive 3D-Visualisierung eines Reihenvierzylinder-Viertaktmotors (Three.js), als GitHub Page.

- Kurbelwelle, Pleuel, Kolben, Ventile, Nockenwellen und Zündkerzen bewegen sich kinematisch korrekt
- Zündfolge 1-3-4-2, farbige Gasfüllung je Takt (Ansaugen, Verdichten, Arbeiten, Ausstoßen)
- Drehzahl einstellbar, Pause, Einzelschritt, Motorblock ein-/ausblenden

## Lokal starten

`site/index.html` im Browser öffnen (oder `npx serve site`).

## GitHub Pages aktivieren

Repository → **Settings → Pages → Source: GitHub Actions**. Danach deployt der Workflow
`.github/workflows/pages.yml` den Ordner `site/` bei jedem Push.
