# forcat.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Name and Flower</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Hello, {{ name }}!</h1>
  <p>Click the button to reveal your flower:</p>
  <button id="reveal-button">Show Flower</button>
  <img id="flower-image" src="flower.jpg" alt="Flower">

  <script>
    const button = document.getElementById("reveal-button");
    const image = document.getElementById("flower-image");

    button.addEventListener("click", function() {
      image.classList.toggle("hidden");
    });
  </script>
</body>
</html>
