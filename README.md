# Python-Project-Submission
This is for python training capstone assignment: Book info scrape and recommend
# Book Scraper and Recommendation System

A Python project that includes web scraping for book data and a book recommendation system. The project can scrape book information from books.toscrape.com and provide various book filtering and recommendation features.

## Project Features

### 1. Book Scraper
- Automatically scrape book website data
- Extract the following information:
  - Title
  - Author
  - Genre
  - Publication Year
  - Stock
  - Rating
  - Price
  - Description
  - URL
- Save data in CSV format
- Include progress display and error handling
- Support custom page scraping

### 2. Book Recommender
- Three filtering methods:
  1. Filter by Genre
  2. Filter by Price Range
     - 0-20￡
     - 20-50￡
     - 50-80￡
     - 80￡ and above
  3. Filter by Rating
     - One ⭐ to Five ⭐
- Random Recommendation:
  - Random recommendation from all books
  - Random recommendation from specified genre

## Tech Stack
- Python 3.x
- Web Scraping:
  - requests
  - BeautifulSoup4
  - re (Regular Expression)
- Data Processing:
  - pandas
  - csv
- File Processing:
  - os
  - time

## Project Structure
book_Project/
│  scraper.py         # Web scraping program
│  recommender.py     # Recommendation system program
│
└─data/
└─book.csv        # Scraped book data

## Installation
1. Clone project locally
2. Install dependencies:
```bash
pip install requests
pip install beautifulsoup4
pip install pandas

##Usage Instructions
1. Data Scraping
Run scraper.py to start data collection:

    Automatically scrapes 5 pages of book data
    Displays scraping progress
    Saves data to CSV file
    Shows category statistics
2. Book Recommendation System

Run recommender.py to start the recommendation system:
Main menu options:

    Filter Books
        By Genre
        By Price Range
        By Rating
    Random Recommendation
        Random from all books
        Random from specified genre
    Exit Program

##Notes

    Ensure network connection is stable
    Scraper includes 0.5s delay to avoid server pressure
    Prices displayed with ￡ symbol
    Ratings shown in text format (one to five)

##Error Handling

    File path verification
    Network request exception handling
    Data parsing exception handling
    User input validation

##Future Improvements

    Add more filtering options
    Improve user interface
    Add data visualization
    Optimize recommendation algorithm

##Author

[Dai yining]

##License

MIT License
