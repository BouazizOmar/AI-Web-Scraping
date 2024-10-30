# AI Web Scraper

<p align="center">
    <img src="https://img.shields.io/badge/python-3.8%2B-blue" alt="Python 3.8+">
    <img src="https://img.shields.io/badge/selenium-3.141.0-green" alt="Selenium">
    <img src="https://img.shields.io/badge/BeautifulSoup-4.9.3-orange" alt="BeautifulSoup">
    <img src="https://img.shields.io/badge/langchain-0.0.9-purple" alt="LangChain">
</p>

The **AI Web Scraper** is a Python-based application that allows users to scrape content from any website by providing a URL. This tool captures the website’s DOM structure and uses AI to answer questions or retrieve specific information based on user prompts, making it an ideal solution for quickly extracting targeted data without manually parsing the content.

## Features

- **Automated Web Scraping**: Fetches website data based on the provided URL.
- **Interactive AI Responses**: Allows users to submit prompts to the AI, which analyzes the scraped content to answer questions or extract relevant details.
- **Advanced Parsing Tools**: Utilizes Selenium for browser automation, BeautifulSoup for HTML parsing, and LangChain for natural language processing.
- **User-Friendly Interface**: Interact with the scraped data through an intuitive interface to explore website content in a new way.

## Tools and Technologies

- **Selenium**: For simulating browser actions and capturing dynamic content.
- **BeautifulSoup**: For parsing HTML and navigating the DOM.
- **LangChain**: An AI framework that enhances natural language processing capabilities for complex queries.
- **Python**: The primary language used for building this application.

## How It Works

1. **Provide a URL**: Enter the URL of the website you want to scrape.
2. **Capture the DOM Content**: The scraper fetches and parses the website’s content.
3. **Submit a Prompt**: Enter a question or request information, and the AI will process your prompt, analyzing the scraped content to generate relevant responses.

## Getting Started

### Prerequisites

- Python 3.8+
- Install dependencies from `requirements.txt`:
  
  ```bash
  pip install -r requirements.txt
