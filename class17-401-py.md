# Web Scrape with Python
Web scraping is a technique to automatically access and extract large amounts of information from a website.

**steps:**
1. inspect
2. import libraries 
> (import requests ,import urllib.request, import time, from bs4 import BeautifulSoup)
3. set the url of the website
> url = 'http://web.mta.info/developers/turnstile.html'  response = requests.get(url)
4. parse with beautiful soap
> soup = BeautifulSoup(response.text, “html.parser”)
5. remove all a tags 
> soup.findAll('a')
6. get all the links that matter with for loop
> download_url = 'http://web.mta.info/developers/'+ link   <br>    urllib.request.urlretrieve(download_url,'./'+link[link.find('/turnstile_')+1:])


### Libraries:
**requests**: allows us to access a url 

**beautiful soup**: parses the data from the website url


