# Project Summary
## Background
After watching my two favourite sports teams lose important games in the space of 6 hours I found myself emotionally shattered and in need of a sport I could enjoy without needing to be invested in the outcome. Flicking through the options I saw a livestream for a car racing competition called Extreme E, electric powered offroad vehicles racing through deserts, abandoned mines, and remote scrubland. The action-packed side-by-side racing had me hooked and it wasn't long before I was looking for other similar competitions to watch between events. I started watching World Rallycross (or World RX) and quickly became intrigued by the data behind the strategies. After a quick search revealed the timing data for races going back to the 2022 season was there on the FIA website I started work pulling it all together and displaying it in an accessible format to compare driver performances.

## Webscraping
I used [webscraper.io](https://webscraper.io/) to set up a sitemap that would go through the FIA website and extract the timing data for every available race. Once I had all the data collated I set about processing it and displaying it in Power BI.

## Power BI
I used Power Query to process the text-heavy scraped data and organise it into a very granular database (screenshot available in repository). The data was then displayed in a two page dashboard, page 1 lets the user see in depth data for individual races between 2022 and 2024, and page 2 lets the user compare two drivers head to head in a bunch of different stats.
