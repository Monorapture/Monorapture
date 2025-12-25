# 🚛 Logistics Python Tools

> **Bridging the gap between physical operations and data architecture.**
> A modular toolkit for supply chain analytics, liability calculation, and data quality assurance.

---

## 🎯 The Mission
This repository demonstrates how modern software engineering principles can solve real-world logistics problems. 
Instead of monolithic scripts, this project provides **modular, single-purpose tools** designed with:

1.  **Physical Grounding:** Logic that respects operational reality (e.g., detecting impossible lead times).
2.  **System Integrity:** Clean, readable code avoiding "Spaghetti" structures.
3.  **Usability:** Interfaces designed for non-technical stakeholders (Dispatchers, Managers).

## 🧰 The Toolkit

| Module | Type | Description | Tech Stack |
| :--- | :--- | :--- | :--- |
| **[📂 Supply Chain Dashboard](./dashboard)** | **Frontend** | An interactive Control Tower to visualize revenue, KPIs, and shipping performance. | `Streamlit` `Plotly` |
| **[📂 Data Cleaning Pipeline](./data_cleaning)** | **ETL / Engineering** | A robust cleaning engine. Handles "Zombie Data", sanitizes IDs, and ensures data quality before analysis. | `Pandas` `Jupyter` |
| **[📂 SDR Liability Calculator](./sdr_calculator)** | **Utility Tool** | A precise calculator for CMR liability risks (SDR/SZR). Fetches live exchange rates via API. | `Python` `Tkinter` |

> *Click on the module names above to view detailed documentation and usage instructions.*

---

## 🛠️ Tech Stack

**Core Engineering:**
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-150458?style=flat&logo=pandas&logoColor=white)

**Visualization & UI:**
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboarding-FF4B4B?style=flat&logo=Streamlit&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-Desktop_GUI-gray?style=flat)

**Architecture:**
![Modular](https://img.shields.io/badge/Pattern-Modular_Design-purple?style=flat)
![Clean Code](https://img.shields.io/badge/Philosophy-First_Principles-green?style=flat)

---

## 🚀 Getting Started

Since this is a mono-repo containing multiple tools, you can set up the environment once for all of them.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Monorapture/logistics-python-tools.git](https://github.com/Monorapture/logistics-python-tools.git)
    cd logistics-python-tools
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Navigate to a tool:**
    Check the `README.md` inside each subfolder for specific run instructions.

---

### 👨‍💻 About the Author

**Kilian Sender** | Industrial Data Architect
*Combining operational leadership (Industriemeister) with analytics engineering.*

* **Focus:** Pattern Recognition, System Consistency, Process Optimization.
* **Philosophy:** "I don't just write queries; I build architectures that validate if the data matches the warehouse reality."

[🔗 Connect on LinkedIn](https://www.linkedin.com/in/kilian-sender-aa3100347/)
