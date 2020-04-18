# Web-Scraping-in-Python
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites.

The incredible amount of data on the Internet is a rich resource for any field of research or personal interest. To effectively harvest that data, we need to become skilled at web scraping.

In this exercise, we will do the following:
- Use 'requests' and 'Beautiful Soup' for scraping and parsing data from the Web
- Walk through a web scraping pipeline from start to finish
- Build a script that fetches job offers from the Web and displays relevant information in your console

# Challenges of Web Scraping
The Web has grown organically out of many sources. It combines a ton of different technologies, styles, and personalities, and it continues to grow to this day. In other words, the Web is kind of a hot mess! This can lead to a few challenges you’ll see when you try web scraping.

One challenge is variety. Every website is different. While you’ll encounter general structures that tend to repeat themselves, each website is unique and will need its own personal treatment if you want to extract the information that’s relevant to you.

Another challenge is durability. Websites constantly change. Say you’ve built a shiny new web scraper that automatically cherry-picks precisely what you want from your resource of interest. The first time you run your script, it works flawlessly. But when you run the same script only a short while later, you run into a discouraging and lengthy stack of tracebacks!

This is a realistic scenario, as many websites are in active development. Once the site’s structure has changed, your scraper might not be able to navigate the sitemap correctly or find the relevant information. The good news is that many changes to websites are small and incremental, so you’ll likely be able to update your scraper with only minimal adjustments.

However, keep in mind that because the internet is dynamic, the scrapers you’ll build will probably require constant maintenance. You can set up continuous integration to run scraping tests periodically to ensure that your main script doesn’t break without your knowledge.

## References:
https://realpython.com/beautiful-soup-web-scraper-python/
