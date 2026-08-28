# Climate Change in the American Mind (2008–2024)
### A Quantitative Analysis of Public Concern and Climate Policy Attitudes

**Author:** at702  
**Tools Used:** Python (Pandas, PyReadStat, Matplotlib, Seaborn, SciPy)  

---

## Project Overview
This repository contains a quantitative data analysis of public attitudes toward climate change in the United States using survey data from the **Yale Program on Climate Change Communication (YPCCC)** spanning 2008 to 2024. 

### Key Findings
* **Growing Worry:** A statistically significant increase in climate change worry occurred between the early (2008–2013) and recent (2020–2024) survey periods (*t*(20,440) = -21.46, *p* < .001).

* **Perceived Distant Harm:** Respondents consistently perceive greater climate threat to future generations and natural ecosystems than to themselves personally.

* **Policy Drivers:** Both emotional worry and belief in scientific consensus strongly correlate with public support for climate action (e.g., CO2 regulation and research funding).

---

##  Repository Structure
├── climate_survey_analysis.ipynb   # Main Jupyter Notebook with code & visualizations
├── README.md                        # Project documentation
└── .gitignore                      # Prevents committing large data files

---

##  Dataset Access
Due to file size and licensing guidelines, the primary dataset is not hosted directly in this repository. 

* **Dataset Name:** Climate Change in the American Mind (CCAM) Cumulative Data (2008–2024)
* **Source:** [Yale Program on Climate Change Communication](https://climatecommunication.yale.edu/)
* **File Required:** `CCAM SPSS Data 2008-2024.sav`

To run the notebook, download the `.sav` file from YPCCC and place it in the root directory of this repository.

---

##  How to Run the Notebook

### 1. Prerequisites
Ensure you have **Python 3.10+** and **Anaconda** or **JupyterLab** installed.

### 2. Install Dependencies
Open your terminal or Anaconda Prompt and install the required packages:

```bash
pip install pandas pyreadstat matplotlib seaborn scipy

