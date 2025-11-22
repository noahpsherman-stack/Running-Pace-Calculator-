# Running-Pace-Calculator-
Pace Calculator lets runners quickly calculate pace for any distance in meters, kilometers or miles, including 400m, 800m, 1200m, 5k, mile or longer repeats. Ideal for track, cross country, road races, tempo runs, speed workouts and race pace tracking. Mobile-friendly, interactive, accurate and easy to use.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pace Calculator</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Pace Calculator</h1>
    <p>Enter any distance and your time to calculate pace per km and per mile. Works for 400m, 800m, 1200m, 5k, mile or longer repeats.</p>

    <div class="input-group">
      <label>Distance:</label>
      <input type="number" id="distance" placeholder="Distance" min="1">
      <select id="unit">
        <option value="meters">meters</option>
        <option value="km">kilometers</option>
        <option value="miles">miles</option>
      </select>
    </div>

    <div class="input-group">
      <label>Time:</label>
      <input type="number" id="hours" placeholder="Hours" min="0"> :
      <input type="number" id="minutes" placeholder="Minutes" min="0"> :
      <input type="number" id="seconds" placeholder="Seconds" min="0">
    </div>

    <button id="calculateBtn">Calculate Pace</button>

    <div id="result"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
