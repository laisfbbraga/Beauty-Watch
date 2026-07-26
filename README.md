# BeautyAlert
**Smart makeup price comparison — find the best deal before you buy**


### What is BeautyAlert?
BeautyAlert is a data pipeline that monitors makeup prices across the leading beauty retail websites in Brazil. It compares prices in real time, sends automatic alerts when a product drops in price, and delivers AI-powered purchase recommendations through a public Streamlit dashboard — so anyone can search for a product and instantly see price history, site comparison, and whether now is a good time to buy.

---
### Why BeautyAlert?

There are general price comparison tools out there — but none focused on the Brazilian beauty market with the depth BeautyAlert offers.

Feature |General comparators | BeautyAlert|
|---|---|---|
|Makeup-focused |❌| ✅|
|Price history |	❌| ✅|
|Best price across sites|✅| ✅|
|AI-powered recommendations|❌| ✅|
|Price drop alerts|❌|✅|
|National + international brands|❌|	✅|

**One place. Best price. Right time to buy.**


---

### The Problem It Solves 
As someone who loves beauty and is always hunting for the best deals, I constantly found myself switching between multiple websites trying to figure out: Is this the best price? Has it been cheaper before? Which site should I buy from?

BeautyAlert was built to solve exactly that — one place to search any product, see its full price history, compare across sites, and get recommendations that actually make sense. This project is also my hands-on journey into data engineering, where every feature maps to a real technical skill.

---
### Monitored Sites
*(expanding over time)*

- Beleza na Web
- Sephora Brasil
- Época Cosméticos

---
### Monitored Brands
*(expanding over time)*

**National**: Bruna Tavares · Oceane · Boca Rosa · Mari Maria
**International (sold in Brazil)**: MAC Cosmetics · Rare Beauty · Fenty Beauty

---

### Tech Stack
Layer |	Technology | Status |
|---|---|---|
|Data Collection | Python · BeautifulSoup · Playwright | 🔜 Planned|
|Data Storage |	Google BigQuery · Cloud Storage	| 🔜 Planned|
|Transformation | dbt | 🔜 Planned|
|Orchestration | Apache Airflow |🔜 Planned|
|Cloud |	Google Cloud Platform (GCP)	| 🔜 Planned|
|AI & Recommendations |	Gemini API · ChromaDB |	🔜 Planned|
|Frontend |	Streamlit | 🔜 Planned|
|Version Control | Git · GitHub | ✅ In use|

---

### Architecture

*(Planned — diagram coming soon)*

---

### How to Run

*(Planned — instructions will be added as the project is built)*

### Project Status

🚧 *Under active development — built as part of a data engineering learning journey.*


---
### Phases:

- [ ] Phase 1 — SQL analysis
- [ ] Phase 2 — Web scraping
- [ ] Phase 3 — Automated pipeline (Airflow + dbt)
- [ ] Phase 4 — Cloud deployment (GCP)
- [ ] Phase 5 — AI recommendations
- [ ] Phase 5.5 — Streamlit public dashboard

