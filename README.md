# Project: Spotify Dashboard - Analysis of Music Trends and Audience Engagement

![Dashboard Thumbnail](quarto/capa.png)

### ➡️ Detailed Analysis and Interactive Dashboard in My Portfolio:
[Access the full project page here](https://ferreiragabrielw.github.io/portfolio-gabriel/projetos/Dashboards/8DashboardSpotify/Projeto8DA.html)

---

## About the Project

This **Spotify** dashboard, developed in **Power BI**, explores music trends, audience engagement, and characteristics of popular songs. The project highlights the implementation of advanced functionalities such as **integration with the Spotify API via Python** for data enrichment (album covers) and the use of **custom visuals (Deneb and HTML Content)** for an immersive and visually rich experience.

## Technologies and Process

*   **Main Tools**: Power BI Desktop (DAX, M), Figma (design).
*   **Advanced Technologies**: Python (for data enrichment), Spotify API (collecting cover URLs), HTML Visuals (rendering covers), Deneb (custom Vega/Vega-Lite charts).
*   **ETL**: Kaggle dataset enriched with Python script (Spotify API), date transformations in Power Query, and data modeling in Power BI.
*   **Key Insights**: Average listeners and total streams, song/artist rankings, sound characteristics (energy, danceability), and release patterns over time.

## Repository Content

*   `data/`: Original database (`.xls`).
*   `python/`: Python script used to interact with the Spotify API and enrich the dataset.
*   `quarto/`: `.qmd` file and its rendered HTML version.
*   `powerbi/`: Power BI dashboard `.pbix` file.
*   `figma/`: Files related to the prototype and design in Figma.
*   `html/`: HTML file used for the custom HTML visual.
*   `README.md`: This document.
*   `LICENSE`: Project license (MIT License).

## How to View

*   **Online**: [Access the published dashboard on Power BI Service](https://app.powerbi.com/groups/me/reports/76ca68bc-548e-4c6f-aad1-79c11ece500e/ReportSectionf29673a5990829443c5d?experience=power-bi)
*   **Locally**: Download the `.pbix` file from the `powerbi/` folder and open it with Power BI Desktop. Note that for HTML cover visuals to work locally, the Python script to download images may need to be run, and Power BI Desktop security settings for custom visuals may need adjustment.

---

### License

This project is licensed under the [MIT License](LICENSE).
