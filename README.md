# Data Scraping Project for Election Commission of India Results

## Overview

This project involves scraping data from the Election Commission of India's results website. The scraped data includes information about parliamentary and assembly constituencies, as well as bye election constituencies. The data is then structured into a table format for analysis.

## Project Structure

```
data-scraping-project/
├── README.md
├── Data_scraping_Report.txt
├── Lok_Sabha_Election_Data_Scraping.ipynb
├── requirements.txt
└── results.csv
```

- `README.md`: This file. Provides an overview of the project.
- `Data_scraping_Report.txt`: Contains key insights derived from the scraped data.
- `Lok_Sabha_Election_Data_Scraping.ipynb`: The Python notebook for scraping the data.
- `requirements.txt`: Lists the required Python packages.
- `results.csv`: The output file containing the scraped data in CSV format.

## Key Insights

1. **Total Number of Parliamentary Constituencies**: There are 543 parliamentary constituencies for which results are reported.
2. **Total Number of Assembly Constituencies in Andhra Pradesh**: Andhra Pradesh has 175 assembly constituencies.
3. **Total Number of Assembly Constituencies in Odisha**: Odisha has 147 assembly constituencies.
4. **Bye Elections Constituencies**: There are 25 assembly constituencies involved in bye elections.
5. **Geographical Distribution**: The results are distributed across multiple states, including Andhra Pradesh, Odisha, Arunachal Pradesh, and Sikkim.
6. **Focus on Assembly Elections**: The data highlights significant information about assembly constituencies in specific states.
7. **Digital Access to Results**: The availability of results via mobile apps shows a digital push for voter engagement.
8. **Disclaimers on Data Accuracy**: The results are provisional and subject to final verification, indicating a cautious approach to data presentation.
9. **Responsive Web Design**: The website and data are designed to be accessible on various devices, ensuring a wider reach.
10. **Use of Modern Web Technologies**: The use of Bootstrap and other modern web technologies indicates an effort to provide a user-friendly interface.

## Setup and Installation

1. **Clone the Repository**

    ```sh
    git clone https://github.com/BalapriyaPalanivel/Lok_Sabha_Election_Data_Scraping.git
    cd Lok_Sabha_Election_Data_Scraping
    ```

2. **Install Dependencies**

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Data Scraping Script**

    ```sh
    Lok_Sabha_Election_Data_Scraping.ipynb
    ```

    This script will scrape the data from the Election Commission of India's results website and save it to `results.csv`.

2. **View the Results**

    Open `results.csv` to see the scraped data.

3. **Generate Insights**

    The insights have been provided in the `Data_scraping_Report.txt` file.



