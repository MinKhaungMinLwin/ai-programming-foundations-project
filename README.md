# AI Programming Foundations Project – NYC Airbnb Data Workflow

This Jupyter notebook cleans and explores the 2019 Airbnb listings for New York City to see how nightly prices vary. It handles missing and extreme values, checks that cleaning does not change how well each borough is represented, and compares prices across boroughs and room types with summary tables and three figures. It ends with a summary of the findings, the limitations of the data and the questions that remain open.

**Dataset:** New York City Airbnb Open Data (AB_NYC_2019.csv) — https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
The CSV is included in this repository.

## How to Run

1. Clone the repository and enter the folder:
   ```bash
   git clone https://github.com/MinKhaungMinLwin/ai-programming-foundations-project.git
   cd ai-programming-foundations-project
   ```
2. (Recommended) Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter and open the notebook:
   ```bash
   jupyter notebook data_workflow.ipynb
   ```
5. Run all cells (Kernel → Restart & Run All). Figures are saved to `figures/`.
