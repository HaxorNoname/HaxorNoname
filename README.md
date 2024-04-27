```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dynamic Text Animation</title>
<style>
  body, html {
    height: 100%;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
  }
  
  .text-container {
    text-align: center;
    color: #333;
  }
  
  .text {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
    animation: animateText 5s infinite;
  }
  
  @keyframes animateText {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }
</style>
</head>
<body>

<div class="text-container">
  <div class="text">you known me?</div>
  <div class="text">me known you</div>
  <div class="text">haxor noname was here</div>
  <div class="text">Leviathan Perfect Hunter 2024</div>
</div>

<script>
  // Optionally, you can add JavaScript here for further interactions
</script>

</body>
</html>
