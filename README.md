Google Trends Keyword Analysis

This project explores search interest for a chosen keyword on Google Trends using Python and the **Pytrends** library. It focuses on understanding which countries show the highest interest and visualizing the results with clear, publication‑ready charts.

## Project overview

- Retrieve Google Trends data for a specific keyword using Pytrends.
- Aggregate **interest by region (country level)** and select the top countries by search interest.
- Create bar plots to visualize which countries search the keyword the most, making it easier to compare geographic patterns.

This notebook is intended as a beginner‑friendly, step‑by‑step example for working with Google Trends data in Python.

## Tech stack

- **Language:** Python  
- **Notebook:** Jupyter Notebook (`google.ipynb`)  
- **Libraries:**  
  - `pytrends` – unofficial Google Trends API client
  - `pandas` – data manipulation and analysis  
  - `matplotlib`, `seaborn` – data visualization 

## How to run the notebook

1. Clone the repository:

   ```bash
   git clone https://github.com/hasnatehsan/Google-Trends-Keyword.git
   cd Google-Trends-Keyword
   ```

2. (Optional but recommended) Create and activate a virtual environment.

3. Install the required libraries:

   ```bash
   pip install pytrends matplotlib pandas seaborn
   ```

4. Open the notebook:

   - Using VS Code: open the folder, then open `google.ipynb` and run cells with **Shift + Enter**. 
   - Or in Jupyter: run `jupyter notebook` and open `google.ipynb` from the browser interface. 

5. Follow the notebook cells from top to bottom to:
   - Set your keyword.  
   - Fetch interest‑by‑region data.  
   - Sort and display the top countries.  
   - Plot the bar chart of search interest.

## Notebook structure

- **Setup & imports** – load Pytrends, pandas, seaborn, matplotlib.
- **Keyword configuration** – define the keyword and time window for analysis. 
- **Fetch interest by region** – use `pytrends.interest_by_region()` to retrieve country‑level search interest.
- **Data sorting & selection** – sort countries by interest and select the top N entries.
- **Visualization** – generate bar plots (e.g., top 10–15 countries) to highlight where the keyword is most popular. 

## Possible extensions

- Compare multiple keywords on the same chart.
- Analyze interest over time in addition to interest by region.
