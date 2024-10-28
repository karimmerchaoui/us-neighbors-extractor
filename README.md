<div align='center'>
    
![Neighbors_Extractor](https://github.com/user-attachments/assets/89eb6f55-6b7a-4559-ba48-50c2cc6483ac)

</div>


# Overview
The **Neighbors Extractor** is a powerful Python application designed to help real estate companies in the USA gather essential information about properties and their surrounding neighborhoods. By leveraging web scraping techniques, this tool enables users to extract detailed data about neighboring addresses, including names, phone numbers, and address histories, providing valuable insights for property analysis, client outreach, and market research.

<strong> This solves the problem </strong> of manual data collection by automating the extraction of neighbor information, making it easier to analyze properties, conduct client outreach, and perform market research.


<div align='center'>

<img src="https://github.com/user-attachments/assets/15786584-9b16-4c90-ab13-04536f6c32de" width="50%" alt="Overview Image">



</div>


# Who Would Benefit from This Tool:

<ul>
    <li><strong>Real Estate Agents</strong>: To gather contact information of potential clients and neighbors for personalized outreach.</li>
    <li><strong>Property Managers</strong>: To analyze neighboring properties and communicate with residents about community events or concerns.</li>
    <li><strong>Investors</strong>: To evaluate potential investments by analyzing surrounding properties and their demographics.</li>
    <li><strong>Marketing Professionals</strong>: Identify and reach out to individuals who may be looking to fill roles within the industry.</li>
    <li><strong>Research Analysts</strong>: To conduct studies on property values and demographic trends in specific areas.</li>
</ul>

# Features

- **Address Parsing**: Automatically extracts components of an address (number, street name, city, state, zip code) to ensure accurate data collection.
- **Web Scraping**: Utilizes <strong>BeautifulSoup</strong> and <strong>requests</strong> to scrape data from the web, specifically targeting neighbor information, with ScraperAPI used to bypass anti-bot protections.
- **Data Extraction**: Employs regex to extract pertinent details such as names, ages, phone numbers, and historical addresses from text data.
- **Excel Output**: Saves extracted data into a well-structured Excel file for easy access and analysis.
- **User-Friendly GUI**: Built with `customtkinter`, providing an intuitive interface for users to input addresses and receive results with minimal effort.
- **Progress Tracking**: Displays real-time progress during data scraping, enhancing user experience.

# Project Background
This project was originally developed for <strong> MSV Properties. </strong>
Created by <strong> Karim Merchaoui. </strong>


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


## API Key Management
<p>This application leverages <strong>ScraperAPI</strong> to access data from web pages. Make sure your API key is correctly configured:</p>

<ul>
  <li><strong>File-based Configuration:</strong> Place your API key in <code>api.txt</code>.</li>
  <li><strong>Default API Key:</strong> If <code>api.txt</code> is missing, the app will fall back to a default demo key, which may have limited usage.</li>
</ul>


# Output

<p>The output of this application is an Excel file containing key information extracted from neighbor data. Each row represents a distinct individual found during the scraping process.</p>

<ul>
  <li><strong>Name:</strong> This column provides the name of the individual.</li>
  <li><strong>Phone Numbers:</strong> This column lists the contact numbers associated with the person. If multiple phone numbers are available, they are separated by commas.</li>
  <li><strong>Address Histories:</strong> This column contains the person's address history. If the individual has lived at multiple addresses, they are separated by semicolons.</li>
</ul>

![image](https://github.com/user-attachments/assets/65644a71-2913-4ec9-945f-ad069bb05247)

