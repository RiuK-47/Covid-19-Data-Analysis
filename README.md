# Covid-19-Data-Analysis

https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data-old.csv

📊 COVID-19 Global Data Tracker
Python
Pandas
Matplotlib
Seaborn

A data analysis and visualization project that tracks global COVID-19 trends, including cases, deaths, recoveries, and vaccinations across countries over time.

📌 Project Overview
This project analyzes COVID-19 data from Our World in Data and Johns Hopkins University to:

Track cases, deaths, and vaccination progress globally.

Compare trends between countries.

Visualize key metrics using interactive charts and maps.

Generate insights into the pandemic's impact.

🛠 Installation & Setup
Clone the repository:

bash
git clone https://github.com/yourusername/covid-19-tracker.git
cd covid-19-tracker
Install dependencies (recommended: use a virtual environment):

bash
pip install -r requirements.txt
(Alternatively, install manually: pandas matplotlib seaborn plotly jupyter)

Download the dataset:

Get owid-covid-data.csv from Our World in Data.

Place it in the project folder.

Run the Jupyter Notebook:

bash
jupyter notebook covid19_analysis.ipynb
📂 Project Structure
covid-19-tracker/
├── data/                    # Contains raw datasets
│   └── owid-covid-data.csv  # Primary dataset
├── notebooks/               # Jupyter notebooks
│   └── covid19_analysis.ipynb  # Main analysis notebook
├── outputs/                 # Generated charts & reports
├── README.md                # This file
└── requirements.txt         # Python dependencies
🔍 Key Features
✅ Data Cleaning & Preprocessing
✅ Exploratory Data Analysis (EDA)
✅ Time-Series Trends (Cases, Deaths, Vaccinations)
✅ Country Comparisons (Bar Charts, Line Plots)
✅ Death Rate Analysis
✅ Vaccination Progress Tracking
✅ Interactive Choropleth Maps (Plotly)

📈 Sample Visualizations
Total Cases Over Time	Vaccination Progress
Cases Over Time	Vaccinations
Death Rate Comparison	Global Cases (Choropleth)
Death Rate	Choropleth
📝 Insights & Findings
Vaccination disparities between developed and developing nations.

Wave patterns in cases/deaths linked to variants (Delta, Omicron).

Countries with strong healthcare systems had lower death rates.

Data reporting gaps during peak infection periods.

(See the notebook for detailed analysis.)

🚀 How to Use This Project
Modify covid19_analysis.ipynb to analyze different countries.

Add new visualizations (e.g., ICU data if available).

Export insights as PDF/HTML using Jupyter.

📚 Data Sources
Our World in Data

Johns Hopkins GitHub

🤝 Contributing
Contributions are welcome!
📥 Steps:

Fork the repo

Create a branch (git checkout -b feature/new-analysis)

Commit changes (git commit -m 'Add new visualization')

Push (git push origin feature/new-analysis)

Open a Pull Request

📜 License
MIT License - See LICENSE for details.

📧 Contact
For questions/suggestions, email: muhoho.skariuki.com

🚀 Happy Analyzing! 🌍📊
