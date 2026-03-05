# AI Healthcare Compliance & Regulations Dashboard

An interactive dashboard and literature review on AI for healthcare compliance and regulations across countries.

**Supervisor:** Dr. Anuradha Kar

## Project Structure

```
AI Clinic/
├── app.py                    # Streamlit dashboard application
├── requirements.txt          # Python dependencies
├── literature_review.md      # Comprehensive literature review report
├── data/
│   └── compliance_dataset.json   # Structured country-wise compliance data
└── README.md
```

## Deliverables

1. **Literature Review Report** (`literature_review.md`) — Systematic review covering 32 references across AI healthcare regulation, data privacy, clinical validation, algorithmic transparency, and ethical governance.

2. **Country-Wise Compliance Dataset** (`data/compliance_dataset.json`) — Structured dataset covering 20 countries across 6 regions with 7 thematic compliance scores.

3. **Interactive Dashboard** (`app.py`) — Streamlit web dashboard with 6 tabs:
   - **World Map** — Choropleth map of regulatory maturity and theme scores
   - **Country Comparison** — Side-by-side radar charts, bar charts, and tables
   - **Theme Analysis** — Heatmap, regional averages, and compliance gap analysis
   - **Global Trends** — Timeline, trend cards, and device approval distribution
   - **Country Details** — Deep-dive profiles with expandable regulatory sections
   - **Literature Review** — Full review rendered within the dashboard

## Countries Covered

| Region | Countries |
|--------|-----------|
| North America | United States, Canada |
| Europe | European Union, United Kingdom, Germany, Switzerland |
| Asia | China, India, Japan, South Korea, Singapore, Thailand |
| Middle East | Saudi Arabia, UAE, Israel |
| Africa | South Africa, Nigeria, Kenya |
| Oceania | Australia |

## Themes Tracked

1. Data Privacy & Governance
2. Clinical Validation & Safety
3. Regulatory Approval Process
4. Algorithmic Transparency
5. Ethical Considerations
6. Post-Market Surveillance
7. Liability & Accountability

## Setup & Running

### Prerequisites

- Python 3.9 or higher

### Installation

```bash
pip install -r requirements.txt
```

### Running the Dashboard

```bash
streamlit run app.py
```

The dashboard will open in your browser at `http://localhost:8501`.

## Data Sources

- FDA (U.S. Food and Drug Administration)
- European Commission / EU AI Act
- European Medicines Agency (EMA)
- WHO — Ethics & Governance of AI for Health (2021)
- OECD AI Policy Observatory
- National regulatory agency publications (MHRA, NMPA, PMDA, Health Canada, TGA, etc.)
- Peer-reviewed literature (PubMed, Scopus, IEEE Xplore)

## Dashboard Features

- **Filter by region** — Focus on specific geographic areas
- **Filter by maturity level** — Compare countries at similar regulatory stages
- **Filter by theme** — Focus on specific compliance dimensions
- **Interactive visualizations** — Hover, zoom, and click on all charts
- **Downloadable data** — Export tables and charts from the dashboard
