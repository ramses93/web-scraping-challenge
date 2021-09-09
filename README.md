# Web Scraping Homework - Mission to Mars

## Overview

I performed nitial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter. I scraped the [NASA Mars News Site](https://mars.nasa.gov/news/) to collect the latest News Title and Paragraph Text. I visited the Mars Facts webpage [here](https://space-facts.com/mars/) and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc. I used MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped.

## Analysis
### NASA's JPL Mars Images
NOTE: This section was not added because the NASA's JPL Images Website does not exists anymore (It always throws a "404 Not Found" error)

### Mars Facts
A table was scrapped from https://space-facts.com/mars/. The table is shown below:

| No.  | Parameter | Value |
| 0 | Equatorial Diameter: | 6,792 km  |
| 1 | Polar Diameter: | 6,752 km |
| 2 | Mass: | 6.39x10^23 kg(0.11 Earths) |
| 3 | Moons: | 2 (Phobos & Deimos) |
| 4 | Orbit Distance: |227,943,824 km (1.38 AU) |
| 5 | Orbit Period: | 687 days (1.9 years) |
| 6 | Surface Temperature: | -87 to -5 ºC |
| 7 | First Record: | 2nd millenium BC |
| 8 | Recorded By: | Egyptian astronomers |

| Attempt | #1 | #2 |
| :---: | :---: | :---: |
| Seconds | 301 | 283 |
