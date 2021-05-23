# Stock-Revenue-Data-Dashboard

This Project Uses beautiful soup to web scrape data from http://shortsqueeze.com/. This script launches an automated chrome window to scrape data from short squeeze.com using tickers.
This program configures chrome webdrive to use Tor's (free browser) proxy. This enables us to get more than the limited daily quotes from short squeeze which are based on public I.P. address. Tor must be open while the program runs.

It outputs a file (result.csv) file in the directory from which the script was executed.

# Example use
```
python shortScanner.py --outputFileName results.csv
```
[Example results](./ExampleResults.csv)

# Requirements

Install [python 3](https://www.python.org/downloads).

Install [Tor](https://www.torproject.org/download/) browser.

Install required python packages:

```pip install urllib```

```pip install beautifulsoup4```

```pip install requests```

```pip install selenium```

```pip install pandas```
	
