# 🏎️ Formula 1 Performance & Reliability Analytics (2010–2026)

An interactive **Tableau Story** and data analysis project examining Formula 1 racing dynamics through three primary lenses: **Team & Driver Performance**, **Strategy & Host Venues**, and **Technical Reliability**.

---

## 📌 Executive Summary

This project analyzes historical and contemporary Formula 1 race data (2010–2026) using Tableau. By leveraging nine distinct, interactive visualizations organized into a cohesive Tableau Story, this project translates complex telemetry and statistical race results into strategic insights regarding championship dynamics, tyre compound strategies, venue distribution, and constructor reliability patterns.

---

## 📊 Key Analysis & Insights

### 1. **Constructor & Driver Dynamics**
* **Constructor Dominance:** Visualizing point trajectories illustrates clear eras of team dominance—from Red Bull's early 2010s streak to Mercedes' hybrid-era supremacy, followed by Red Bull's resurgence and McLaren's high-efficiency scoring in recent seasons.
* **Driver Performance:**
  * **All-Time Leaders:** Max Verstappen and Lewis Hamilton lead all-time points tallies by a significant margin.
  * **Recent Form (2024–2026):** Lando Norris and Max Verstappen lead individual driver standings, with McLaren and Red Bull establishing a competitive tier of their own.
* **Podium Distribution:** Max Verstappen and Lewis Hamilton dominate total podium counts (>160 each), followed by George Russell, Charles Leclerc, Sergio Perez, and Lando Norris.

### 2. **Strategic Insights & Circuit Dynamics**
* **Tyre Strategy & Podium Probability:**
  * **Permanent & Street Circuits:** Soft tyre starting compounds yield high podium success rates (~15.8%–16.5%).
  * **Street/Park Circuits:** Hard tyre compounds prove most successful (~17.8%), while Soft tyres perform significantly worse (~8.8%).
* **Grand Prix Venues (2022–2026):**
  * The **USA** hosts the highest number of Grand Prix events across the period (e.g., Austin, Miami, Las Vegas), reflecting F1's commercial expansion.
  * Traditional host nations (Italy, UK, Spain, Monaco, Hungary, Austria) maintain stable, recurrent presence on the calendar.

### 3. **Technical Reliability & DNF Analysis**
* **Constructor Failures (2022–2026):**
  * **Red Bull Racing** experienced the highest absolute count of Did Not Finish (DNF) outcomes despite high point yields, largely driven by technical issues (hydraulics and mechanical failures) rather than driver errors.
  * **McLaren** maintained strong mechanical reliability with minimal mechanical failures across recent seasons.
  * **Williams** showed zero DNF entries attributed to collisions in recent seasons, though mechanical issues remained a factor.
* **Track-Type Vulnerability:**
  * Driver DNF rates spike significantly on permanent circuits for drivers like Max Verstappen, whereas several veteran drivers (e.g., Fernando Alonso, George Russell, Valtteri Bottas) record higher DNF percentages on tight street circuits.

---

## 📁 Repository Structure

```text
├── F1 Racing Project Dataset.xlsx   # Source dataset containing driver, race, tyre, and outcome data
└── README.md                        # Project documentation
```

---

## 🛠️ Visualizations Breakdown

| Dashboard / Story Point | Topic / Focus | Core Metric |
| :--- | :--- | :--- |
| **01. Constructor Standings** | Team Points Across Seasons | Sum of Points by Team (2010–2026) |
| **02. Driver Standings** | Top Drivers (2024–2026) | Sum of Points by Driver & Team |
| **03. Tyre Strategy** | Podium Rate by Tyre Compound & Circuit Type | Avg. Podium Flag % |
| **04. All-Time Leaderboard** | Historical Driver Points Leaders | Cumulative Points (2010–2026) |
| **05. Circuit Distribution** | Host Countries Analysis | Distinct Count of `Race Id` |
| **06. Podium Achievements** | Podium Count by Driver & Team | Sum of Podium Flags |
| **07. Failure Modes** | Constructor DNF Breakdown by Cause | Sum of DNF Flags by Failure Type |
| **08. Driver Track DNF Rate** | Track Specificity vs. Driver Retirements | Avg. DNF Flag % by Circuit Type |
| **09. Completion Reliability** | Team Race Completion Trends | % Race Completion Rate Across Seasons |

---

## 🧰 Tools & Technologies Used

* **Tableau Desktop / Tableau Public:** Data visualization, interactive filtering, calculated fields, and Storyboard layout.
* **Microsoft Excel:** Data structure, preprocessing, and tabular dataset organization.

---

## 💡 How to Explore

1. **Raw Dataset:** Review `F1 Racing Project Dataset.xlsx` for underlying telemetry and result data structure including driver flags, circuit types, and failure reasons.

---

## 📝 Future Improvements

* Integrate dynamic pit-stop timing data for deeper strategy modeling.
* Build predictive machine learning models for race outcome classification based on qualifying position and initial tyre choice.