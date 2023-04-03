# stack-overflow-scraping
a simple Python script that scrapes each question on StackOverflow along with the best answer


## USAGE

`git clone https://github.com/0ut0flin3/stack-overflow-scraping.git`

`cd stack-overflow-scraping`

`pip install -r requirements.txt`

`python app.py`

Now the script will start extracting all the questions and their best answer and add them in a KEY/VALUE pair inside the `data.json` file. You can also stop the script and restart it later, it will start right where it left off since the `last` file contains the index of the last question scraped. Furthermore, since a dictionary is the place where the data is entered, there is no risk that the same question will be entered several times since dictionaries do not allow identical keys. Good scraping :heart:

## P.S. it will work the same for any StackExchange site, you just need to change the url

## [HERE](https://github.com/0ut0flin3/scraped-data) you can find already scraped questions using this script
