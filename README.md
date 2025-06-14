# News_Scraper
# Simple News Headline Scraper

_A Python script to fetch and display the top 5 headlines from your favorite news site._

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a lightweight Python script designed to grab the latest headlines from a news website (such as BBC, NPR, or Hacker News) and print them to your terminal.  
It’s perfect for learning web scraping basics and can be adapted to different news sources by editing a few lines of code.

## Features

- Fetches and displays the top 5 news headlines
- Easy to configure for your preferred news site
- Minimal dependencies (requests, beautifulsoup4)
- Beginner-friendly code and structure
- (Optional) Save results to CSV or JSON

## Setup

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/news-headline-scraper.git
   cd news-headline-scraper
   ```

2. **Install dependencies:**  
   ```bash
   pip install requests beautifulsoup4
   ```

## Usage

Run the script with:
```bash
python news_scraper.py
```
By default, it scrapes headlines from the site set in the script.  
To change the source, update the URL and parsing selectors in `news_scraper.py`.

## Examples

**Example Output:**
```
Top 5 Headlines from Hacker News:
1. OpenAI launches new API for developers
2. NASA announces Artemis II crew
3. Python 4.0 release notes revealed
4. Global tech layoffs continue in 2025
5. Breakthrough in quantum computing announced
```

## Contributing

Contributions welcome!
1. Fork the repository
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push to your fork and open a pull request

## License

MIT License

---

*Built by WildNullberry for learning and experimentation.*
