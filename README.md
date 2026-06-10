# AI-Powered GTM Market Intelligence — PLM/CAD Market
**Author: Sunanda Guha**

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini-orange?logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-HuggingFace%20Transformers-yellow)](https://huggingface.co/docs/transformers/index)
[![Tableau](https://img.shields.io/badge/Tableau-Public-blue?logo=tableau&logoColor=white)](https://public.tableau.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

---

## 📌 Project Overview & Business Context
In the highly competitive Product Lifecycle Management (PLM) and Computer-Aided Design (CAD) industry, Go-To-Market (GTM) teams often struggle to synthesize fragmented market data into actionable territory strategies. 

This project delivers an **end-to-end Market Intelligence Pipeline**. It leverages Generative AI (Gemini) and Local NLP (DistilBERT) to analyze the competitive landscape, score market territories using a custom 5-factor weighted model, and forecast 3-year revenue opportunities. The final output is an executive-ready suite of visualizations and a strategic roadmap.

## 🛠 Tech Stack
- **Data Processing:** Python (Pandas, NumPy)
- **Generative AI:** Google Gemini API (`google-generativeai`)
- **Natural Language Processing:** HuggingFace Transformers (DistilBERT)
- **Visualizations:** Matplotlib, Seaborn
- **Business Intelligence:** Tableau Public
- **Environment:** Google Colab

---

## 📂 Repository Structure
```text
├── notebooks/
│   └── GTM_Market_Intelligence_Main.ipynb   # Main analysis & AI pipeline
├── data/
│   ├── raw_market_data.csv                  # Input market segments
│   └── processed_gtm_export.csv             # Tableau-ready output
├── outputs/
│   ├── executive_summary_report.txt         # AI-generated strategic report
│   └── executive_dashboard_panel.png        # Matplotlib summary view
├── README.md                                # Project documentation
└── requirements.txt                         # Dependency list
```

---

## 🚀 Step-by-Step Execution (Google Colab)
1. **Clone the Repo:** Upload the `.ipynb` file to your Google Colab environment.
2. **API Setup:** 
   - Obtain a free API Key from [Google AI Studio](https://aistudio.google.com/).
   - Add it to Colab Secrets (Left sidebar -> Key icon) under the name `GEMINI_API_KEY`.
3. **Install Dependencies:**
   ```python
   !pip install -q -U google-generativeai transformers torch
   ```
4. **Run All Cells:** The notebook will automatically:
   - Perform NLP sentiment analysis on customer reviews.
   - Query Gemini for competitor SWOT analysis.
   - Calculate Territory Scores and 3-Year Forecasts.
   - Export `processed_gtm_export.csv` for Tableau.

---

## 📊 Key Outputs & Visuals
### 1. 4-Panel Executive Summary (Python Generated)
A comprehensive Matplotlib dashboard containing:
- **Territory Score Heatmap:** Identifying high-priority market clusters.
- **Sentiment Analysis Breakdown:** Customer perception by product category (DistilBERT).
- **Revenue Forecast (3-Year):** Projected growth trends using linear modeling.
- **Competitive Intensity Matrix:** Market Share vs. Growth Potential.

### 2. AI-Generated GTM Strategy
The `outputs/executive_summary_report.txt` provides:
- A synthesized view of the PLM/CAD landscape.
- Specific GTM "Plays" for priority segments (e.g., "The Mid-Market Disruption Play").
- Risk mitigation strategies based on competitor intelligence.

### 3. Interactive Tableau Dashboard
A dynamic version of the data for stakeholder exploration.
- **[View Interactive Tableau Dashboard Here](https://public.tableau.com/app/profile/sunanda.guha)** *(Note: Replace with your actual link)*

---

## 🧠 Skills Demonstrated
- **Strategic Modeling:** Developed a custom 5-factor weighted scoring model (Market Size, CAGR, Competitive Density, Customer Sentiment, and Ease of Entry).
- **Generative AI Integration:** Prompt engineering for SWOT and market strategy generation via Gemini API.
- **NLP & Sentiment Analysis:** Implementing local transformer models (DistilBERT) for scalable text classification.
- **Data Engineering:** Automated ETL pipeline from raw CSV to cleaned, Tableau-ready data structures.
- **Executive Communication:** Designing high-level visualization dashboards tailored for C-suite decision-making.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
**Contact:** [Sunanda Guha](https://linkedin.com/in/sunandaguha) | [Portfolio Website](#)