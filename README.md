# Scraping and Analysis of the Technology Stack for Python Vacancies

## Features
- Web Scraping: Uses Selenium to extract real-time information about Python vacancies from dou.ua, including location, experience level, and required technologies.
- Data Parsing: Cleans and processes the raw data, organizing it into a structured format for analysis.
- Data Analysis: Provides a comprehensive statistical analysis of the scraped data, including frequency distributions of technology stacks, locations, and required experience levels.

## Installation

1. **Open your terminal or command prompt.**
2. **Navigate to the directory where you want to clone the project.**
3. **Run the following commands:**
```shell
git clone https://github.com/MaglorFeanorson/vacancy_analyzer.git
python -m venv venv
source venv/bin/activate  #for Windows use: venv\Scripts\activate
```

4. **Install requirements:**

```shell
pip install -r requirements.txt
```

5. **Run the Web Scraping Script:**
```shell
python -m app
```


6. **Work with Data Analysis:**
Once the data is scraped, open the Jupyter Notebook located in the data_analysis folder to explore and analyze the data. Follow the instructions and execute each cell in the notebook sequentially to perform the analysis.

## Files Structure
- data_analysis: Contains the Jupyter Notebook file for working with data analysis. You can run various analysis operations such as visualizing the most popular technologies or analyzing the geographic distribution of Python jobs.
- data_parsing: Contains modules for scraping (parse.py), parsing, and writing data (writer.py) to CSV format. It handles the extraction and organization of vacancy data.
- app.py: The main entry point that contains the script for running the WebScraping process, which collects vacancy data and writes it to a CSV file.