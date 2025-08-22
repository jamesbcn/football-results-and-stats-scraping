![EFL Championship Logo](./banner.png)

# EFL Championship Results and Stats Scraping 

This project automates the process of scraping football match results and team statistics from EFL Championship teams the current season (25/26) and the two previous. The collected data can be used for analytics, visualization, or further research. The code is modular, well-documented, and designed for scalability.

---

## Features

- **Automated Data Collection:** Scrapes football results and statistics for multiple teams.
- **Data Processing:** Cleans and structures the scraped data for analysis.
- **Table Merging:** Combines match results and shooting statistics tables on the match date to create a comprehensive dataset for each team.
- **Extensible Design:** Easily adaptable to new leagues, seasons, or data sources.
- **Error Handling:** Robust error checking to handle missing or inconsistent data.

---

**Note:**  
- The `for` loop iterates over each team in the `teams` list, repeating the code in the cells above.
- For each team, the code fetches the relevant results and processes them.
- This ensures that the scraping and processing logic is applied consistently to all teams, making the workflow efficient and scalable.
- The number of previous seasons scraped can be adjusted.

---

## How to Use

1. **Clone the Repository**
   ```
   git clone https://github.com/jamesbcn/football-results-and-stats-scraping.git
   cd football-results-and-stats-scraping
   ```

2. **Create and Activate a Virtual Environment (Optional)**
    ```
    python -m venv venv
    source venv/bin/activate      # On macOS/Linux
    venv\Scripts\activate         # On Windows
    ```

3. **Install Dependencies**
   ```
   pip install -r requirements.txt
   ```

4. **Open the Jupyter Notebook File**
    Launch Jupyter Lab or VS Code and open the `scraping.ipynb` file, then run the cells.

---

**Disclaimer:**  
This project is for educational purposes only. Please respect the terms of service of any website you scrape and do not use this code for commercial purposes or to overload servers.

A `time.sleep(5)` call is included in the scraping loop to pause five seconds between requests. This is important to avoid overloading the target website's servers and to reduce the risk of being blocked. Always scrape responsibly and consider the impact on the website you are accessing.