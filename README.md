<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jokic vs SGA: Who Runs the West?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #121212;
      color: #e0e0e0;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 720px;
      margin: auto;
      background: #1e1e1e;
      padding: 20px;
    }
    h1, h2 {
      color: #ffffff;
    }
    img {
      width: 100%;
      border-radius: 10px;
      margin: 15px 0;
    }
    .ad-banner, .native-banner {
      text-align: center;
      margin: 25px 0;
    }
    .facebook-follow {
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: #1877f2;
      color: white;
      text-decoration: none;
      padding: 12px 20px;
      border-radius: 8px;
      font-size: 16px;
      margin-top: 40px;
    }
    .facebook-follow img {
      width: 24px;
      height: 24px;
      margin-right: 10px;
    }
    .poll {
      background-color: #2c2c2c;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
      text-align: center;
    }
    .poll button {
      background-color: #1877f2;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 5px;
      border-radius: 6px;
      cursor: pointer;
    }
    .poll-results {
      margin-top: 20px;
      text-align: left;
    }
    .poll-bar {
      background: #444;
      border-radius: 4px;
      overflow: hidden;
      margin-bottom: 8px;
    }
    .poll-bar-inner {
      background: #1877f2;
      height: 20px;
      text-align: right;
      color: #fff;
      padding-right: 5px;
      line-height: 20px;
    }
  </style>
</head>
<body>
<div class="container">
  <!-- Banner Ad (Top) -->
  <div class="ad-banner">
    <script type="text/javascript">
      atOptions = {
        'key' : '6a8b8392a37323947b7e9c9b315ca281',
        'format' : 'iframe',
        'height' : 50,
        'width' : 320,
        'params' : {}
      };
    </script>
    <script type="text/javascript" src="//www.highperformanceformat.com/6a8b8392a37323947b7e9c9b315ca281/invoke.js"></script>
  </div>  <!-- Poll Section -->  <div class="poll">
    <h2>On a scale of 1 to 10, how confident are you in your team tonight?</h2>
    <div id="poll-options"></div>
    <div id="poll-results" class="poll-results" style="display:none;"></div>
  </div>  <h1>Jokic vs SGA: Who Really Runs the West?</h1>
  <img src="https://cdn.nba.com/headshots/nba/latest/1040x760/203999.png" alt="Nikola Jokic">
  <p>Tonight’s clash between the Denver Nuggets and the Oklahoma City Thunder isn’t just another regular-season game — it’s a battle for Western Conference supremacy...</p>
  <img src="https://cdn.nba.com/headshots/nba/latest/1040x760/1628983.png" alt="Shai Gilgeous-Alexander">
  <p><strong>Shai Gilgeous-Alexander</strong> has elevated his game...</p>  <h2>Tonight’s Showdown</h2>
  <p>Both teams are hungry...</p>  <!-- Native Banner Ad -->  <div class="native-banner">
    <script async="async" data-cfasync="false" src="//pl26659972.profitableratecpm.com/6f7e351969652b406af11cfd3b9c735f/invoke.js"></script>
    <div id="container-6f7e351969652b406af11cfd3b9c735f"></div>
  </div>  <!-- Facebook Subscribe Button -->  <a class="facebook-follow" href="https://www.facebook.com/share/1ATEmYa5jX/" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo">
    Follow our NBA News page!
  </a>
</div>
<script>
  const pollOptions = document.getElementById("poll-options");
  const pollResults = document.getElementById("poll-results");
  let votes = Array(10).fill(0);function renderPoll() { for (let i = 1; i <= 10; i++) { const btn = document.createElement("button"); btn.textContent = i; btn.onclick = () => { votes[i - 1]++; showResults(); }; pollOptions.appendChild(btn); } }

function showResults() { pollOptions.style.display = "none"; pollResults.style.display = "block"; pollResults.innerHTML = "<h3>Results:</h3>";

const totalVotes = votes.reduce((a, b) => a + b, 0);

votes.forEach((vote, index) => {
  const percent = totalVotes ? Math.round((vote / totalVotes) * 100) : 0;
  pollResults.innerHTML += `
    <div>${index + 1} - ${percent}%</div>
    <div class="poll-bar">
      <div class="poll-bar-inner" style="width:${percent}%">${vote}</div>
    </div>
  `;
});

}

renderPoll(); </script>

</body>
</html>
