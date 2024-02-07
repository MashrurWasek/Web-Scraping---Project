---

# Web Scraping Project

## Overview

This project demonstrates how to perform web scraping using Python. It includes a step-by-step guide that covers the basics of retrieving web page content using the `requests` library and parsing the HTML to extract information.

### Features

- **Download Content:** Utilize the `requests` library to download web page content.
- **Data Extraction:** Demonstrates how to extract specific data from a webpage.

### Step 1: Download the Content

The project kicks off by downloading the content of a webpage using the `requests` library. This step is crucial for any web scraping project as it involves retrieving the HTML of the page you're interested in.

```python
import requests

depts_url = 'https://my.gwu.edu/mod/pws/subjects.cfm'
params = {
    'campus_id': '1',  # Main Campus
    'term_id': '202303'
}

depts_page = requests.get(depts_url, params=params) # depts_page is an HTTP response object
```

## Getting Started

To get started with this project, clone the repository and ensure you have Python installed on your machine. You will need to install the `requests` library if you haven't already:

```bash
pip install requests
```

## Usage

Follow the Jupyter notebook `Web-Scrap-Project.ipynb` for detailed instructions and examples on how to perform web scraping tasks.

---
