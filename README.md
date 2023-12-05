<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ezequiel Cruz's GitHub</title>
  <style>
    body {
      font-family: 'Courier New', monospace;
      text-align: center;
      margin: 50px;
    }
    img {
      border-radius: 50%;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Hello, I'm Ezequiel Cruz</h1>
  <p id="typing-text"></p>
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="100" alt="GIF">

  <script>
    // Fetch the typing animation SVG from the service
    fetch('https://readme-typing-svg.herokuapp.com?font=Courier+New&color=cyan&size=25&center=true&vCenter=true&width=600&height=100&lines=Future+junior+full+stack+developer..&hearts;++;Self-taught;+Only+Focused;CTF+Newbie,;Active+Learner/Researcher,;Love+to+learn+new+stuffs..<3')
      .then(response => response.text())
      .then(svgText => {
        // Set the SVG as the innerHTML of the typing-text element
        document.getElementById('typing-text').innerHTML = svgText;
      });
  </script>
</body>
</html>
