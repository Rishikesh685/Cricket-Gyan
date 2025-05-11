# Cricket-Gyan
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Indian Cricket Players & Records</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="logo">
      <img src="india-cricket-logo.png" alt="Indian Cricket Logo">
    </div>
    <h1>Indian Cricket Players & Records</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#players">Players</a></li>
        <li><a href="#records">Records</a></li>
        <li><a href="#stats">Stats</a></li>
      </ul>
    </nav>
  </header>

  <!-- Introduction Section -->
  <section id="home">
    <h2>Introduction</h2>
    <p>Explore detailed information about Indian cricket players, their records, and achievements. From legendary players like Sachin Tendulkar to current stars like Virat Kohli, find stats and more!</p>
  </section>

  <!-- Players Section -->
  <section id="players">
    <h2>Indian Cricket Players</h2>
    <div class="player-card">
      <img src="sachin-tendulkar.jpg" alt="Sachin Tendulkar">
      <div class="player-info">
        <h3>Sachin Tendulkar</h3>
        <p><strong>Role:</strong> Batsman</p>
        <p><strong>Career Span:</strong> 1989–2013</p>
        <p><strong>Matches Played:</strong> 200 Tests, 463 ODIs, 1 T20I</p>
        <p><strong>Runs:</strong> 15921 (Test), 18426 (ODI)</p>
        <p><strong>Centuries:</strong> 51 (Test), 49 (ODI)</p>
        <p><strong>Major Records:</strong> Most Runs in World Cup, First Player to Score 100 International Centuries</p>
      </div>
    </div>
    
    <!-- Add other player cards here -->

  </section>

  <!-- Records Section -->
  <section id="records">
    <h2>Indian Cricket Records</h2>
    
    <div class="record-table">
      <h3>Top Batting Records</h3>
      <table>
        <tr>
          <th>Player</th>
          <th>Matches Played</th>
          <th>Runs</th>
          <th>Centuries</th>
        </tr>
        <tr>
          <td>Sachin Tendulkar</td>
          <td>664</td>
          <td>34357</td>
          <td>100</td>
        </tr>
        <tr>
          <td>Virat Kohli</td>
          <td>493</td>
          <td>23883</td>
          <td>70</td>
        </tr>
        <!-- Add more records here -->
      </table>
    </div>

    <div class="record-table">
      <h3>Top Bowling Records</h3>
      <table>
        <tr>
          <th>Player</th>
          <th>Matches Played</th>
          <th>Wickets</th>
          <th>Best Bowling</th>
        </tr>
        <tr>
          <td>Anil Kumble</td>
          <td>132</td>
          <td>619</td>
          <td>10/74 (Test)</td>
        </tr>
        <tr>
          <td>Kapil Dev</td>
          <td>225</td>
          <td>434</td>
          <td>5/28 (ODI)</td>
        </tr>
        <!-- Add more records here -->
      </table>
    </div>
  </section>

  <!-- Stats Section -->
  <section id="stats">
    <h2>Detailed Stats</h2>
    <div class="stats-container">
      <div class="stats-card">
        <h3>Most Runs in Test Cricket</h3>
        <p>Sachin Tendulkar - 15921 Runs</p>
      </div>
      <div class="stats-card">
        <h3>Most Wickets in ODIs</h3>
        <p>Kapil Dev - 434 Wickets</p>
      </div>
      <!-- Add more stats cards here -->
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <div class="social-media">
      <a href="https://twitter.com/IndianCricket" target="_blank">Twitter</a>
      <a href="https://www.facebook.com/IndianCricket" target="_blank">Facebook</a>
      <a href="https://www.instagram.com/IndianCricket" target="_blank">Instagram</a>
    </div>
    <p>Contact Us: info@indiacricket.com</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body Styling */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

/* Header Styling */
header {
  background-color: #0066b3;
  color: white;
  padding: 20px;
  text-align: center;
}

header .logo img {
  width: 50px;
}

header h1 {
  margin: 10px 0;
}

header nav ul {
  list-style-type: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 10px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

header nav ul li a:hover {
  text-decoration: underline;
}

/* Section Styling */
section {
  padding: 20px;
  margin: 20px 0;
  background-color: white;
  border-radius: 8px;
}

section h2 {
  font-size: 1.5em;
  margin-bottom: 10px;
}

section p {
  font-size: 1em;
  margin-bottom: 10px;
}

/* Player Cards */
.player-card {
  display: flex;
  margin-bottom: 20px;
  background-color: #f9f9f9;
  padding: 15px;
  border-radius: 8px;
}

.player-card img {
  width: 150px;
  border-radius: 8px;
  margin-right: 20px;
}

.player-info h3 {
  font-size: 1.2em;
  margin-bottom: 10px;
}

.player-info p {
  font-size: 1em;
  margin-bottom: 8px;
}

/* Table Styling */
table {
  width: 100%;
  border-collapse: collapse;
}

table, th, td {
  border: 1px solid #ddd;
}

th, td {
  padding: 10px;
  text-align: left;
}

th {
  background-color: #0066b3;
  color: white;
}

/* Stats Container */
.stats-container {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}

.stats-card {
  background-color: #f9f9f9;
  padding: 15px;
  border-radius: 8px;
  width: 30%;
}

.stats-card h3 {
  font-size: 1.3em;
  margin-bottom: 10px;
}

.stats-card p {
  font-size: 1em;
}

/* Footer Styling */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}

footer .social-media {
  margin-bottom: 10px;
}

footer .social-media a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
}

footer .social-media a:hover {
  text-decoration: underline;
}
