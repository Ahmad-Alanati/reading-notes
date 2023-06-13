# Class 17 reading

## why this topic matters?


## reading Questions

1. What are the key differences between scraping static and dynamic websites?

the key differences are:

1. page structure
2. data retrieval
3. interactivity and AJAX
4. javaScript execution
5. speed and resource requirements
6. maintenance

2. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.

1. Respect Robots.txt:this file contain the the rules of the scraping

2. Make the crawling slower, do not slam the server, treat websites nicely:it is easy for the bot to fetch data very fast and it is easy for site toe detect your scraper.

3. Do not follow the same crawling pattern: it is easy for you to make your scraping bot do the same in every web site and it is easy for intelligent anti-crawling mechanisms

3. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.

playwright is a library that is used to browse automatically

- Browser Automation: Playwright enables you to launch and control web browsers programmatically.
- Synchronous and Asynchronous Execution: Playwright supports both synchronous and asynchronous execution styles, depending on your programming language and preference.
- Network Interception and Mocking: Playwright allows you to intercept and modify network requests made by the browser.

4. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.

the purpose of using Xpath is to extract data from the websites

ex: //h1[text()="hello world"]

## Things I want to know more about