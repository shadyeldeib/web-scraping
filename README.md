# **Web Scraping E-commerce Companies**

This repository contains a Jupyter Notebook (web\_scrapying\_e\_commerce\_companies.ipynb) designed to scrape information from e-commerce company listings, process the data, and export it into an Excel file. This project is a practical exercise in web scraping, data cleaning, and data handling for analytical purposes.

## **🎯 Project Goal**

The primary objective of this project is to:

* Extract structured data from web pages related to e-commerce companies, including a **web scrape of the top 100 e-commerce companies in Egypt**.  
* Gather information on individuals working in the e-commerce sector, specifically **790 records of people working in e-commerce from LinkedIn, obtained using the Google Search API**.
* Leveraged **NLP techniques** to programmatically generate query variations for the **Google Search API** (e.g., building upon a base query like "site:linkedin.com/in E-commerce Companies in Egypt").  
* Clean and transform the extracted raw data into a usable format.  
* Export the cleaned dataset to an Excel file, ensuring proper encoding for multi-language support (specifically Arabic text).

This project can serve as a foundational step for market research, lead generation, or building a dataset for further data analysis or machine learning tasks.

## **🛠️ Technologies Used**

The project is built using Python and leverages several powerful libraries:

* **Python 3.x**: The core programming language.  
* **Jupyter Notebook**: For interactive development and execution of the code.  
* **requests (or similar HTTP library)**: For making HTTP requests to fetch web page content.  
* **BeautifulSoup4**: A Python library for parsing HTML and XML documents, making it easy to extract data.  
* **pandas**: A fundamental library for data manipulation and analysis, used for creating and processing DataFrames.  
* **xlsxwriter**: A Python module that allows you to write files in the Excel 2007+ XLSX file format. It's particularly useful for handling character encoding for non-ASCII text.  
* **Google Search API**: Utilized for querying and extracting relevant LinkedIn profiles.
* **Natural Language Processing (NLP) techniques**: Applied for programmatic generation of search query variations.

## **🏃 Usage**

1. Start Jupyter:  
   Once all dependencies are installed, launch Jupyter Notebook or JupyterLab from your terminal in the project directory:  
   jupyter notebook

   (or jupyter lab)  
2. Open the Notebook:  
   In the Jupyter interface that opens in your browser, navigate to and open web\_scrapying\_e\_commerce\_companies.ipynb.  
3. Run the Cells:  
   Execute each cell in the notebook sequentially. The notebook is structured to guide you through the web scraping process, data cleaning, and finally, data export. Ensure you configure your Google Search API key within the notebook if prompted.  
4. Check the Output:  
   Upon successful execution, the cleaned data will be exported to an Excel file named cleaned1\_linkedin\_search\_results.xlsx. This file will contain both the e-commerce company data and the LinkedIn professional records. It will be saved in the directory specified within the notebook (e.g., /content/drive/MyDrive/Colab Notebooks/projects/web scraping/). The xlsxwriter engine ensures that Arabic text is correctly displayed in the Excel file.

## **🤝 Contributing**

Feel free to open issues or submit pull requests if you have suggestions for improvements or encounter any bugs.
