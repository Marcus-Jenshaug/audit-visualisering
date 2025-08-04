# Aktivitets-visualisering for GitHub Audit Log

Dette prosjektet visualiserer data fra en GitHub audit log-eksport. Det viser en oversikt over hendelser, en toppliste over de mest vanlige handlingene, og et interaktivt diagram over aktivitetsnivået over tid.

## Hvordan bruke det

1.  **Last ned filene**: Klon eller last ned dette repoet til din lokale maskin.
2.  **Åpne i nettleseren**: Åpne `index.html`-filen i en moderne nettleser som støtter ES-moduler (f.eks. Chrome, Firefox, Safari, Edge).

Det er det! Siden vil automatisk laste og behandle dataen fra den inkluderte JSON-filen.

## Datakilde

Dataen som visualiseres kommer fra `export-eiendomsavtaler-1-1754309573.json`, som er en eksport av GitHub audit-logger i JSON Lines-format. Skriptet i `index.html` er satt opp til å analysere denne spesifikke filen og vise aktiviteten til brukeren "Marcus-Jenshaug".

## Teknologier

*   **HTML5**
*   **Tailwind CSS** for styling
*   **Chart.js** for datavisualisering
*   **JavaScript (ES Modules)** for databehandling og interaktivitet
