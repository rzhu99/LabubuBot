# LabubuBot
PopMart Website Scrapper for Instock labubu Related Items

Objective:
- Create a Python script utilizing [selenium, email, beautifulsoup, requests, json, time]
- Chrome driver to assists in scrapping of data and driving the web searches
- Email stock alert notification
- Deploy on Heroku via cli
- Attract users to join listserve through a posit application

Purpose:
- The Popmart x Labubu brand has blown up over the past year because of BlackPink KPOP star Lisa.
- Kasing Lung, the Hong Kong born artist and creator of Labubu, drew inspiration from Nordic mythology and has since created a huge series of Labubu related items and collectibles.
- These collectibles are only sold through Popmart's website, app, and social media pages (TikTok). Is it very difficult to buy due to botting and limited quantities.
- I have noticed that the "notify of instock" feature from Popmart website/app does not work as intended.
- Therefore, I created this bot in hopes to help 'non-resellers' to have the better hand during "random and unannounced" restocks.

Result:
- The bot is currrently hosted on Heroku and is scheduled to scrape for the popular Labubu products every 1 min.
- Utilizes the Cron To Go
- Success rate in determining whether a product is in stock or not is at least 99% accurate.

Future:
- I hope to improve the script so that it doesn't continue hitting the memory limit set by Heroku (done)
- I have yet to create the posit app for users to type in their emails to be added to the listserve. Currently doing that manually.
- I can see this type of script being used else where [Pokemon?]

I'm not going to share my code here as there are propietary information , but once the posit app is created, there will be a visual view
