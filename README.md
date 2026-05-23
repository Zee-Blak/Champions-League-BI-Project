# ⚽ UEFA Champions League (UCL) Tactical Intelligence Hub
An end-to-end cloud data analytics pipeline extracting strategic team efficiency, defensive resilience, and match environment insights from 144 group phase fixtures.

## 📌 Project Overview
In modern football, standard league tables often mask true performance characteristics. This project constructs a complete data pipeline that moves raw, unaggregated match logs into an enterprise business intelligence layout. The goal is to provide a Technical Director or Coaching Staff with deep, granular insights into team efficiency, venue biases, and external match factors like referee behavior.

### 💡 Core Analytical Insights Uncovered:
* **The "Clinical Snipers" (PSV):** While volume giants like Arsenal, Bayern, and Barcelona led in raw scoring, deeper metrics exposed **PSV Eindhoven** as the ultimate tactical anomaly, maintaining a tournament-high **52% shot-conversion rate** (goals to shots on target).
* **The Defensive Wall (Newcastle United):** Outfield structure protected Arsenal (lowest gross goals conceded), but **Newcastle United** logged the most resilient defensive shift, maintaining an elite **86.06% average save percentage** under high pressure.
* **Home Fortress vs. Road Warriors:** Atlético Madrid and Sporting CP exhibited massive home dependency (scoring nearly 2x more goals at home than away), while **Real Madrid** inverted the trend, proving completely unfazed by hostile environments by scoring more goals on the road.
* **The Referee "Match Climate":** Official behavior heavily governs match velocity. Fixtures under Manfredas Lukjančukas averaged **6.0 goals per match**, whereas strict regulators like Anthony Taylor choked output down to **4.3 goals**.

---

## 🛠️ Tech Stack & Architecture
* **Data Warehouse:** Google BigQuery (SQL)
* **Business Intelligence Engine:** Power BI Desktop
* **Data Transformations:** Cloud SQL ETL & Advanced DAX Semantic Modeling
* <img width="2075" height="1200" alt="UCL Tactical Intelligence Hub (Final)" src="https://github.com/user-attachments/assets/d40b5505-2ec0-4051-9331-9c4210e9519e" />
