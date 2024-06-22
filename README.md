# forcat.github.io
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>Name and Flower</title>
 <link rel="stylesheet" href="style.css">
</head>
<body>
 <h1>Hey Cat <3</h1>
 <p>I love you so much, so here's a sunflower for my sunflower:</p>
 <button id="reveal-button">Show Flower</button>
 <img id="flower-image" src="Flower.jpg" alt="Flower">

 <script>
  const button = document.getElementById("reveal-button");
  const image = document.getElementById("flower-image");

  button.addEventListener("click", function() {
   image.classList.toggle("hidden");
  });
 </script>
</body>
</html>
