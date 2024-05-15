Dependencies: The server uses express for creating the server, axios for making HTTP requests, cheerio for parsing the HTML, and cors to handle cross-origin requests.
Server Setup: We set up the Express server to listen on port 5000 and include the necessary middleware.
Scraping Logic: In the /scrape endpoint, we use Axios to fetch the HTML from the provided URL, parse it with Cheerio, and extract all the anchor (<a>) elements. The data is then sent back as a JSON response.
