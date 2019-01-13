# Scraping Metacritic with R or: How I Learned to Stop Worrying and Love Loops

An ongoing project to scrape Metacritic scores.
The initial version scrapes the basic page content of all PS4 games.

To implement:
* Loop failsafe with 'map' function (404 errors)
* Complete descriptions (Around 50% missing at the moment)
* Scrape individual review scores 

Future aims:
* Carry out analysis on factors determining a good/bad game
* Extend the pipeline to Films and TV shows
* Use the tool to find films/games that divide critics (love it or hate it). The current single score review system doesn't offer this perspective. If a product falls into this category, it's marked as mediocre.
