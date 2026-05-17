# Analysis of Single-Use Plastics' Consumption in Myanmar and Its Contribution to Climate Change

A data-driven web platform exploring the link between single-use plastic consumption and carbon emissions across Myanmar — built as a senior capstone thesis project at Parami University.

🔗 **Live site:** [https://monsoee29-lang.github.io](https://github.com/monsoee29-lang) *(update with your actual GitHub Pages URL)*

---

## 📌 About the Project

This platform presents the public-facing output of a capstone research project completed in May 2026. Using survey data collected from respondents across Myanmar's regions, the project quantifies plastic usage patterns, estimates associated CO₂ equivalent emissions, and surfaces insights through interactive visualizations.

**Research question:** What does Myanmar's per-person plastic footprint actually look like — region by region, product by product?

> ⚠️ Note: The dataset available for download is a sample. The full 304-response dataset is available on request — email [monsoee29@gmail.com](mailto:monsoee29@gmail.com).

---

## 📄 Pages

| File | Description |
|---|---|
| `index.html` | Home page — project overview, methodology, limitations, researcher profile, and references |
| `dashboard.html` | Interactive EDA dashboard with Chart.js charts and a Leaflet.js regional map |
| `tracker.html` | Personal CO₂ footprint calculator based on plastic usage inputs |
| `research.html` | Detailed research background and methodology |
| `style.css` | Shared stylesheet used across pages |
| `eda_development.ipynb` | Jupyter notebook for exploratory data analysis |

---

## ✨ Features

- **Interactive charts** — bar charts, pie charts, heatmaps, and stacked horizontal bars built with [Chart.js](https://www.chartjs.org/)
- **Regional map** — choropleth/marker map of Myanmar built with [Leaflet.js](https://leafletjs.com/)
- **CO₂ footprint calculator** — estimates personal plastic-related carbon emissions based on user inputs
- **Fully static** — no server or backend required; deployed via GitHub Pages
- **Responsive design** — works on desktop and mobile

---

## 🗂️ Repository Structure

├── index.html
├── dashboard.html
├── tracker.html
├── research.html
├── style.css
├── eda_development.ipynb
└── Survey_Dataset_Ei Mon Soe.csv
└── images 

---

## 🚀 Deployment

This site is deployed via **GitHub Pages** directly from the `main` branch root. To run locally, clone the repo and open `index.html` in your browser — no build step needed.

```bash
git clone https://monsoee29-lang.github.io/Senior-Capstone/.git
cd <Senior-Capstone>
open index.html
```

---

## 🔬 Data & Methodology

- **Survey instrument:** Structured questionnaire on single-use plastic purchasing habits
- **Sample size:** 304 respondents (online survey, May 2026)
- **Coverage:** Multiple regions across Myanmar
- **Emission factors:** Global lifecycle CO₂e averages from Leal Filho et al. (2025), used as indicative estimates in the absence of Myanmar-specific data
- **Limitations:** Online sampling bias toward young, urban, university-educated respondents; self-reported data; cross-sectional snapshot with no longitudinal tracking

---

## 📚 Key References

1. Leal Filho, W. et al. (2025). Decarbonising the plastic industry. *Science of the Total Environment, 999*, 180337. https://doi.org/10.1016/j.scitotenv.2025.180337
2. Rinasti, A. N. et al. (2024). Plastic Leakage Identification and Monitoring for National Action Plan Approach in Myanmar. *Global Environmental Research, 28*(1), 3–10.
3. Simantiris, N. (2024). Single-use plastic or paper products? *Cleaner Waste Systems, 7*, 100128.
4. Alteneiji, S. M. et al. (2024). Knowledge, Attitudes, and Practices towards Single-Use Plastic Bags in the UAE. *Sustainability, 16*(17), 7396. https://doi.org/10.3390/su16177396

---

## 👩‍🎓 Researcher

**Ei Mon Soe**  
Bachelor of Data Science · Division of Mathematics and Science · Parami University  
Student ID: PIUS 20220035

Supervised by **Dr. Mohamed Megheib** · Advised by **Dr. Nwe Nwe Htay Win**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ei-mon-soe-6aa022257/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/monsoee29-lang)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:monsoee29@gmail.com)

---

## 📜 License

This project is shared for academic and educational purposes. Please credit the author if you reference or reuse this work.

© 2026 Ei Mon Soe · Parami University Senior Capstone



