
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
<h1>PCMEMES VS IP2 Leaderboard</h1>
    <h1>IP2 README</h1>
    <p>This project fetches data from two different URLs, processes the data, and then serves the results through an API endpoint. It fetches posts from the provided URLs, calculates a score based on each post's vote state and author, and then sorts the results based on the score. The sorted results are then written to an output file named <code>output.json</code>.</p>
    <h2>Dependencies</h2>
    <p>This project uses the following dependencies:</p>
    <ul>
        <li><a href="https://www.npmjs.com/package/express">express</a>: A web application framework for Node.js</li>
        <li><a href="https://www.npmjs.com/package/axios">axios</a>: A promise-based HTTP client for Node.js</li>
    </ul>
    <h2>Setup</h2>
    <p>To set up the project, follow these steps:</p>
    <ol>
        <li>Clone the repository to your local machine.</li>
        <li>Install the dependencies using npm: <code>npm install</code>.</li>
        <li>Fill in the required values for the headers in the <code>headers</code> object in <code>index.js</code>.</li>
        <li>Run the project using <code>npm start</code>.</li>
    </ol>
    <h2>Usage</h2>
    <p>Once the server is running, you can access the results through the API endpoint <code>/results</code>. This endpoint returns the sorted results in JSON format.</p>
    <h2>API Endpoints</h2>
    <ul>
        <li><strong>GET /results</strong>: Returns the sorted results in JSON format.</li>
    </ul>
     <h1>PCMEMES.NET README</h1>
  <p>This is a Python script to scrape the leaderboard data from PCMEMES.NET and save it to a JSON file.</p>

  <h2>Dependencies</h2>
  <ul>
    <li>requests</li>
    <li>BeautifulSoup</li>
    <li>json</li>
    <li>time</li>
    <li>re</li>
    <li>logging</li>
  </ul>

  <h2>Usage</h2>
  <p>To use this script, you need to provide your access token and client ID. Additionally, make sure you have Python installed on your system.</p>
  <pre><code>python scraper.py</code></pre>

  <h2>Script Explanation</h2>
  <p>This script scrapes data from the PCMEMES.NET leaderboard for various URLs. It extracts usernames and corresponding upvotes, applies a multiplier, and saves the data to a JSON file.</p>

  <h2>Configuration</h2>
  <p>You need to set your access token and client ID in the script before running it.</p>
  
<p>This project is licensed under the <a href="https://www.gnu.org/licenses/gpl-3.0.html">GPL-3.0 License</a>. See the <a href="LICENSE">LICENSE</a> file for details.</p>


<h2>Author</h2>
  <p>Created by RIOTCOKE</p>


</body>
</html>
