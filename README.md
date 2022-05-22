# Scraping data with Puppeteer

This was created for the first group project called [Not another CookBook](https://github.com/RaphaCH/not-another-cookbook) as the last step in The Hill stage at the BeCode formation.

## :bulb: What was the objective?

- Manage and scrape the most relevant data from a source to populate the content of our future application

## :rocket: What was the outcome?

- Used Puppeteer to crawl the [All recipes](https://www.allrecipes.com/) website. I made a function to scrape first the main recipe categories for the recipe URLs, then used those to scrape data from more than 400 recipes at once.

## :grey_question: How to get started?

### `npm install`

This will install dependencies

### `node index.js`
This will run the scraping function, prompting the launch of Chromium.

**Attention!** Since there were over 400 recipes to scrape, I modified the number to just 2 for testing purposes. The number can be changed in the argument of the scrapContentFromUrls() function on line 144 in the index.js file.
