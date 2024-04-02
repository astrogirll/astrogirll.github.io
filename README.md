<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Astrogirl - Your ultimate source for Robotics Insights">
<title>Astrogirl - Robotics Blog</title>
<!-- Meta tags for search engine optimization -->
<meta name="keywords" content="Astrogirl, Robotics Blog, Robotics Insights">
<meta name="author" content="Astrogirl Team">
<!-- Open Graph meta tags for better social sharing -->
<meta property="og:title" content="Astrogirl - Robotics Blog">
<meta property="og:description" content="Your ultimate source for Robotics Insights">
<meta property="og:image" content="https://example.com/og-image.jpg">
<meta property="og:url" content="https://example.com">
<meta name="twitter:card" content="summary_large_image">
<!-- Canonical URL for better SEO -->
<link rel="canonical" href="https://example.com">

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
   .chatbot-button {
    background-color: #00AEEF; /* Blue color for the chatbot button */
    color: #fff; /* White text color */
    border: none;
    border-radius: 50%; /* Makes the button circular */
    width: 60px;
    height: 60px;
    position: fixed;
    bottom: 20px;
    right: 20px;
    cursor: pointer;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .chatbot-button:hover {
    background-color: #0077B5; /* Darker blue on hover */
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
<!-- Chatbot button -->
<button class="chatbot-button" id="chatbot-button" aria-label="Open Chatbot">&#128172;</button>

<div class="blogs-container">
  <div class="blog-card">
    <h2>Revolutionizing Healthcare: A journey through Digital transformation with Dr. Surendra Ramamurthy</h2>
    <p>Explore Dr. Surendra Ramamurthy's journey, navigating the intersection of technology and healthcare, and envision a patient-centric, and technologically advanced future.</p>
    <a href="https://astrogirll.github.io/blog2.html" class="read-more-button">Read More</a>
  </div> 
  <div class="blog-card">
    <h2>Summer of Robotic laughter: Building my first robotic arm</h2>
    <p>Discovering robotics and creating a robotic arm-a journey filled with learning and excitement.</p>
    <a href="https://astrogirll.github.io/blog1.html" class="read-more-button">Read More</a>
  </div> 
</div>

<script>
  const chatbotButton = document.getElementById("chatbot-button");

  chatbotButton.addEventListener("click", () => {
    window.location.href = "Chatbot.html";
  });
</script>

</body>
</html>
