# Amazon Web Scraper

![Screenshot](./images/program_screenshot.png)

The article describing the code for this repo can be found [here](https://medium.com/@brendanfrrs/scraping-amazon-results-with-selenium-and-python-547fc6be8bfa "Medium.com article.").

## Requirements:
To run this program you will need the following installed on your computer or virtual machine:

1. [selenium](https://selenium-python.readthedocs.io/installation.html)
2. [webdriver-manager](https://pypi.org/project/webdriver-manager/)
3. [selectorlib](https://pypi.org/project/selectorlib/)

You will also need the following file in the project directory:

1. *search_results_urls.txt*

You will also need the following folder in the project directory:

1. *results*

This folder will house all of the search resulting json files. The file names will be in the following format: query_date_results.jsonl

**Example Output**
![output](./images/amazon_output.png)

#### Repository Structure
<pre>
├── LICENSE
├── Mod2\ Study\ Notebook.ipynb
├── README.md
├── amazon-scraper
├── amazon_scraper.ipynb
├── amazon_scraper.py
├── banner.txt
├── images
│   ├── amazon_output.png
│   └── program_screenshot.png
├── linkedin_final_script.py
├── results
│   ├── Iphone_Oct-13-2020_results.jsonl
│   ├── Macbook\ Pro_Oct-12-2020_results.jsonl
│   ├── Xbox\ one_Oct-12-2020_results.jsonl
│   ├── statistics_Oct-12-2020_results.jsonl
│   ├── tent_Oct-12-2020_results.jsonl
│   ├── xbox_Oct-12-2020_results.jsonl
│   └── xbox_results.jsonl
├── search_results.yml
├── search_results_urls\ copy.txt
├── search_results_urls.txt
├── search_urls.txt </pre>