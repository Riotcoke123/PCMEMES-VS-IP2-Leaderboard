
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README</title>
</head>
<body>
  # PCMEMES VS IP2 Leaderboard
PCMEMES VS IP2 Leaderboard
    <h1>README</h1>
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
    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
