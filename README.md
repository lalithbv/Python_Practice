# Project 1: Tic Tac Toe

This program does the following:
1. Two players will be able to play the game (both sitting at the same computer)
2. The board will be printed out every time a player makes a move
3. User input i.e the position of 'X' or 'O' is accepted and then the symbol is placed on the board

# Project 2: Web Scraping with Python

There are a few libraries you will need, you can go to your command line and install these below:
'''
pip install requests
pip install lxml
pip install bs4
'''
## Task 1

The website: http://books.toscrape.com/index.html is specifically designed for people to scrape it, so there are no copyright violations here.

Mission of this program is to get the title of every book that has a 2 star rating and at the end just have a Python list with all their titles.

The following is accomplished:
1. Figured out the URL structure to go through every page
2. Scraped every page in the catalogue
3. Figured out what tag/class represents the Star rating
4. Filtered by that star rating using an if statement
5. Stored the results to a list

## Task 2

Follwing tasks are achieved:
1. Used requests library & BeautifulSoup to connect to http://quotes.toscrape.com/ & got the HMTL text from homepage.
2. Got the names of all the authors in all the pages.
3. Created a list of all the quotes on the first page.
4. Inspected the site and used Beautiful Soup to extract the top ten tags from the requests text shown on the top right from the home page (e.g Love,Inspirational,Life, etc...)
