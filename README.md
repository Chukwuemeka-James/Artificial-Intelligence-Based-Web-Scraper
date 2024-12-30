# Artificial-Intelligence-Based-Web-Scraper

This project demonstrates an AI-powered web scraper using Selenium, BeautifulSoup, LangChain, and Ollama to scrape and parse website content. It leverages the capabilities of the `llama3` model to extract specific information based on user-provided descriptions.

## Features

- **Web Scraping:** Scrapes websites using Selenium and BeautifulSoup to extract the DOM content.
- **Content Cleaning:** Removes unnecessary scripts and styles, providing clean and readable content.
- **Content Parsing:** Uses LangChain with the Ollama model to extract specific information from the scraped content based on user-defined descriptions.
- **Interactive UI:** Built with Streamlit, allowing users to interactively scrape and parse content from any website.

```bash
.
├── main.py           # Streamlit app for interacting with the scraper and parser
├── scrape.py         # Web scraping logic (Selenium, BeautifulSoup)
├── parse.py          # Content parsing logic using LangChain and Ollama
├── sample.env        # Environment variables (SBR_WEBDRIVER)
├── requirements.txt  # Required Python libraries
```

## Technologies Used

- **Selenium**: Web browser automation tool for scraping websites.
- **BeautifulSoup**: Web scraping library for parsing and extracting data from HTML documents.
- **LangChain**: A framework for building language model-powered applications.
- **Ollama**: A pre-trained language model (llama3) used for content parsing.
- **Streamlit**: Framework for building interactive web applications.
- **python-dotenv**: For loading environment variables from a `.env` file.
