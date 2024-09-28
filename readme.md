# Automated Publications Summary Generator

The **Automated Publications Summary Generator** is a Flask-based web application designed to help academic institutions and researchers summarize and analyze author publications. It leverages scholarly data, generates summaries, and visualizes trends in publication data. Users can upload files with author names and retrieve detailed publication metrics and summary reports.

## Project Objectives

The primary goals of this project are:
- Automate the retrieval and summary of research publications for individual authors.
- Generate insightful metrics like H-index, I-index, and citation trends over time.
- Provide a customizable summary for authors' publications that can be downloaded as Word documents.
- Allow for the analysis and visualization of publication trends over time using charts and tables.

## Features

- **Upload and Process Files:** Users can upload `.csv`, `.xlsx`, or `.bib` files containing author names and optionally institution names. The app retrieves detailed publication data for the authors.
- **Automated Summary Generation:** The app generates concise summaries of author publications using Google Generative AI for natural language generation.
- **Downloadable Summaries:** Users can download the publication summaries in Word format for easy reference and reporting.
- **Publication Trend Analysis:** Visualize the publication trends of multiple authors using bar charts.
- **Interactive Data Table:** View processed data in an interactive HTML table.
- **Download CSV:** Export the processed publication data to a CSV file for further analysis.

## Technologies Used

- **Backend:**
  - [Flask](https://flask.palletsprojects.com/) - Python web framework for the server-side logic.
  - [Scholarly](https://pypi.org/project/scholarly/) - Python package to fetch publication details from Google Scholar.
  - [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis library.
  - [BibTeXParser](https://bibtexparser.readthedocs.io/) - To parse `.bib` files.
  - [Google Generative AI](https://developers.generativeai.google/) - For natural language processing and summary generation.

- **Frontend:**
  - [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - For structuring the web pages.
  - [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - For styling the web pages.
  - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - To add interactivity, such as chart rendering.

- **Visualization:**
  - [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) - Libraries used for visualizing publication trends and other data.

- **Others:**
  - [Concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - For parallel processing of data.
  - [Python-Docx](https://python-docx.readthedocs.io/) - For generating Word document summaries.
  - [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/) - For handling cross-origin resource sharing (CORS).
  
