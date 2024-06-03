# Web_Scraping_and_Text_Analysis_from_URLs
This project focuses on web scraping and text analysis from URLs using Python libraries like pandas, requests, BeautifulSoup, and nltk. It extracts text, computes metrics (positive/negative scores, polarity, subjectivity, average sentence length, complex words), and saves the data to a CSV file.

<p align="left">
    <img src="https://img.shields.io/badge/Language-Python-blue" alt="Python" />
    <img src="https://img.shields.io/badge/Library-pandas-yellow" alt="pandas" />
    <img src="https://img.shields.io/badge/Library-requests-red" alt="requests" />
    <img src="https://img.shields.io/badge/Library-BeautifulSoup-green" alt="BeautifulSoup" />
    <img src="https://img.shields.io/badge/Library-nltk-orange" alt="nltk" />
</p>

## Aim
The aim of this project is to extract textual data from a list of URLs and perform comprehensive text analysis to compute various metrics such as positive and negative scores, polarity, subjectivity, average sentence length, and the percentage of complex words.

## Goals
- Efficiently scrape text data from a list of URLs.
- Perform detailed text analysis using natural language processing techniques.
- Compute and store various textual metrics for further analysis.
- Save the results in a structured format (CSV) for easy access and interpretation.

## Skills and Tools Used
- **Python Programming**: Core language used for scripting and automation.
- **Web Scraping**: 
  - `requests`: For making HTTP requests to fetch web page content.
  - `BeautifulSoup`: For parsing HTML and extracting text data.
- **Data Analysis**:
  - `pandas`: For data manipulation and handling DataFrames.
  - `nltk`: For natural language processing tasks like tokenization, stop words removal, and text analysis.
- **Data Storage**: Saving the processed data into CSV files for further use.

## What I Did
1. **Data Extraction**:
   - Loaded a list of URLs from an Excel file.
   - Used `requests` and `BeautifulSoup` to fetch and parse HTML content from each URL.
   - Extracted text data from specific HTML elements.
   
2. **Text Analysis**:
   - Tokenized the text into sentences and words.
   - Removed stop words and punctuation.
   - Counted syllables in words and identified complex words.
   - Computed various metrics such as positive and negative scores, polarity, subjectivity, and average sentence length.

3. **Data Manipulation**:
   - Stored extracted text and computed metrics in pandas DataFrames.
   - Created new columns for each computed metric.
   - Merged and organized data as needed.

4. **Data Storage**:
   - Saved the final DataFrame with all metrics into a CSV file for easy access and analysis.

## Conclusions
The project successfully demonstrated the process of web scraping and text analysis. By using various Python libraries and tools, it was possible to extract meaningful insights from the textual data available on web pages. The final CSV file provides a comprehensive view of the text metrics, which can be further analyzed for various applications.

## Key Takeaways
- Web scraping is a powerful technique to extract data from web pages, but it requires careful handling of HTML structures.
- Natural language processing techniques, such as tokenization and stop words removal, are essential for cleaning and analyzing text data.
- pandas is an invaluable tool for data manipulation, allowing for efficient storage, transformation, and analysis of large datasets.
- Proper data storage formats, such as CSV, ensure that the processed data can be easily accessed and utilized for further analysis.
