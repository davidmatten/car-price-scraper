# car-price-scraper
a tool to scrape car prices with details from multiple online car sales sites

There are many car sales websites for south africa:
gumtree
autotrader
automart
olx
autodealer
surf4cars
etc..

There is a wealth of information available here, if scraped and details captured longitudinally.

Spefic questions I am interested in answering with scraped data are:

- How do car's values depreciate over time?
- Is this linked to their age / milage / location / colour / etc.

This could be useful to inform:
"I want to buy the car which will lose me the least money over the life of my owning the car"
A big contender in this would be the resale price... but its hard to estimate the resale price without historic data and trends to look at.

How much will I be able to sell my Volvo for when its got another 50k on the clock in 3 years time?
A good estimate to answer this might be to look at how much similar spec'd Volvo's were selling for 3 years ago with 50k less on their clocks, and how much they are going for now - 3 years on +50k.


For this task it would probably be good to populate a database.

Car table
- make, model, age, colour, as many details as possible... 
- when was this info captured
- location


Then run this script twice a week, for a year, 2 years... forever...
When enough data has been populated, then we can start to build queries.
