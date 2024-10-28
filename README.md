<div align='center'>
    
![Neighbors_Extractor](https://github.com/user-attachments/assets/89eb6f55-6b7a-4559-ba48-50c2cc6483ac)

</div>


# Neighbors Extractor

## Overview

The **Neighbors Extractor** is a powerful Python application designed to help real estate companies in the USA gather essential information about properties and their surrounding neighborhoods. By leveraging web scraping techniques, this tool enables users to extract detailed data about neighboring addresses, including names, phone numbers, and address histories, providing valuable insights for property analysis, client outreach, and market research.

## Who Would Benefit from This Tool:

<ul>
    <li><strong>Real Estate Agents</strong>: To gather contact information of potential clients and neighbors for personalized outreach.</li>
    <li><strong>Property Managers</strong>: To analyze neighboring properties and communicate with residents about community events or concerns.</li>
    <li><strong>Investors</strong>: To evaluate potential investments by analyzing surrounding properties and their demographics.</li>
    <li><strong>Marketing Professionals</strong>: Identify and reach out to individuals who may be looking to fill roles within the industry.</li>
    <li><strong>Research Analysts</strong>: To conduct studies on property values and demographic trends in specific areas.</li>
</ul>

## Features

- **Address Parsing**: Automatically extracts components of an address (number, street name, city, state, zip code) to ensure accurate data collection.
- **Web Scraping**: Utilizes BeautifulSoup and requests to scrape data from the web, specifically targeting neighbor information.
- **Data Extraction**: Employs regex to extract pertinent details such as names, ages, phone numbers, and historical addresses from text data.
- **Excel Output**: Saves extracted data into a well-structured Excel file for easy access and analysis.
- **User-Friendly GUI**: Built with `customtkinter`, providing an intuitive interface for users to input addresses and receive results with minimal effort.
- **Progress Tracking**: Displays real-time progress during data scraping, enhancing user experience.

# Installation

To get started with Neighbors Extractor, follow these steps:




## Steps
<ul>
  <li>Clone the repository:
    <pre><code>
git clone https://github.com/karimmerchaoui/us-neighbors-extractor/edit/main/README.md
cd Craigslist-phone-numbers-extractor
</code></pre>
  </li>
  <li>Install required dependencies:
    <pre><code>
pip install -r requirements.txt
</code></pre>
  </li>
</ul>

## Prerequesite

<ul>
<li>Python 3.x</li>
<li>pip (Python package manager)</li>
</ul>


# Usage

<ol type="1">
    <li>Run the application:</li>
    <pre><code>python src/main.py</code></pre>
    <li>Enter the number,street,city,state or zip and the number of addresses you want to check in the GUI.</li>
    <li>Click "Extract" to begin extracting .</li>
</ol>
