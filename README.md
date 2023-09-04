<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Astrogirl - Robotics Blog</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f2f7f9; /* Snowy White */
    color: #333; /* Dark Gray */
    text-align: center;
  }

  .navbar {
    background-color: #bde0fe; /* Icy Blue */
    overflow: hidden;
  }

  .navbar a {
    float: left;
    display: block;
    color: #fff; /* Black */
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    transition: background-color 0.3s, color 0.3s;
  }

  .navbar a:hover {
    background-color: #f2f7f9; /* Snowy White */
    color: #7f9c9f; /* Icy Blue */
  }

  .blogs-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
  }

  .blog-card {
    background-color: #bde0fe; /* Frosty Blue */
    border-radius: 10px;
    padding: 20px;
    margin: 10px;
    width: calc(50% - 20px); /* Two cards per row */
    text-align: left;
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .blog-card:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }

  .read-more-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #82b5d8; /* Light Blue */
    color: #fff; /* White */
    border-radius: 20px; /* Curved edges */
    text-decoration: none;
    transition: background-color 0.3s, border 0.3s, color 0.3s;
    border: 2px solid #82b5d8; /* Light Blue border */
  }

  .read-more-button:hover {
    background-color: #5c8fb1; /* Darker Blue on hover */
    border: 2px solid #5c8fb1; /* Darker Blue border on hover */
    color: #fff; /* White color on hover */
  }
</style>
</head>
<body>

<div class="navbar">
  <a class="active" href="#"><strong>HOME</strong></a>
  <a href="About.html"><strong>ABOUT</strong></a>
  <a href="contact.html"><strong>CONTACT</strong></a>
  </div>

<h1>Welcome to Astrogirl</h1>
<p>Your ultimate source for Robotics Insights</p>

<div class="blogs-container">
  <div class="blog-card">
    <h2>Blog title 1</h2>
    <p>Short excerpt 1.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div>
  <div class="blog-card">
    <h2>Blog title 2</h2>
    <p>Short excerpt 2.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 

  <div class="blog-card">
    <h2>Blog title 3</h2>
    <p>Short excerpt.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 
   <div class="blog-card">
    <h2>Blog title 4</h2>
    <p>Short excerpt.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 
   <div class="blog-card">
    <h2>Blog title 5</h2>
    <p>Short excerpt.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 
   <div class="blog-card">
    <h2>Blog title 6</h2>
    <p>Short excerpt 6.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 
   <div class="blog-card">
    <h2>Blog title 7</h2>
    <p>Short excerpt 7.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 
   <div class="blog-card">
    <h2>Blog title 8</h2>
    <p>Short excerpt 8.</p>
    <a href="https://astrogirll.github.io/blog.html" class="read-more-button">Read More</a>
  </div> 
 
</div>

<script>
  const menuButton = document.querySelector(".menu-button");
  const navbar = document.querySelector(".navbar");

  menuButton.addEventListener("click", () => {
    navbar.classList.toggle("responsive");
  });
</script>

</body>
</html>
