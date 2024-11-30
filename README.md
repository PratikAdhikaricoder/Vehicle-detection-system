# Vehicle-detection-system
#html code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vehicle Detection System</title>
  <link rel="stylesheet" href="vehicledetection.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Vehicle Detection System</h1>
    </header>

    <main>
      <div class="video-section">
        <input type="file" id="videoInput" accept="video/*" />
        <video id="video" controls></video>
        <canvas id="canvas"></canvas>
      </div>
    </main>

    <footer>
      <p>Powered by Vehicle Detection System | &copy; 2024</p>
    </footer>
  </div>

  <script src="vehicledetection.js"></script>
</body>
</html>
