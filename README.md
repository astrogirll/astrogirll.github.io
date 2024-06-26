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

  /* Chatbot styles */
  .chatbot {
    display: none;
    position: fixed;
    bottom: 100px;
    right: 20px;
    width: 300px;
    background-image: url('snowflake-background.jpg'); /* Winter-themed background image */
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    color: #000; /* Text color in chatbot */
    font-family: Arial, sans-serif;
  }

  .chatbox {
    height: 300px;
    overflow: auto;
    padding: 10px;
  }

  .chat-input {
    width: 100%;
    padding: 10px;
    border: none;
    border-top: 1px solid #ccc;
    background-color: #fff;
    color: #000;
  }

  .user-message {
    text-align: right;
    background-color: #0077B5; /* Dark blue for user messages */
    color: #000;
    border-radius: 10px;
    padding: 10px;
    margin: 5px;
    width: 60%;
  }

  .chatbot-message {
    text-align: left;
    background-color: #82b5d8; /* Light blue for chatbot messages */
    color: #000;
    border-radius: 10px;
    padding: 10px;
    margin: 5px;
    width: 60%;
  }

  .chatbot-buttons {
    text-align: left;
    margin-left: 10%;
  }

  .chatbot-button-option {
    display: block;
    background-color: #82b5d8; /* Light blue for chatbot buttons */
    color: #000; /* Black text color for chatbot buttons */
    border: none;
    border-radius: 10px;
    padding: 10px 20px;
    margin: 5px;
    width: 80%;
    text-align: left;
    cursor: pointer;
  }

  /* Responsive design */
  @media only screen and (max-width: 768px) {
    .blog-card {
      width: calc(100% - 20px); /* Full width for single card */
    }
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

<!-- Chatbot container (hidden by

 default) -->
<div class="chatbot" id="chatbot" aria-hidden="true" aria-live="polite">
  <div class="chatbox" id="chatbox">
    <div id="chatbot-content">
      <p class="chatbot-message">Hello, I am Astrobot. How can I help you today?</p>
      <p class="chatbot-message">Would you like to read a blog on robotics or medicinal applications?</p>
      <div class="chatbot-buttons">
        <button class="chatbot-button-option" onclick="window.location.href = 'https://astrogirll.github.io/blog2.html'">Medicinal Application</button>
        <button class="chatbot-button-option" onclick="window.location.href = 'https://astrogirll.github.io/blog1.html'">Robotic Arm</button>
        <button class="chatbot-button-option" onclick="window.location.href = 'https://astrogirll.github.io/About.html'">Know more about the author</button>
      </div>
    </div>
  </div>
  <input type="text" class="chat-input" id="user-input" placeholder="Type your message and press Enter" aria-label="Type your message and press Enter">
</div>

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
  const menuButton = document.querySelector(".menu-button");
  const navbar = document.querySelector(".navbar");
  // JavaScript to toggle the chatbot visibility
  const chatbotButton = document.getElementById("chatbot-button");
  const chatbot = document.getElementById("chatbot");

  chatbotButton.addEventListener("click", () => {
    chatbot.style.display = chatbot.style.display === "none" ? "block" : "none";
    chatbot.setAttribute("aria-hidden", chatbot.style.display === "none");
  });

  // Handle user input and chatbot responses
  const userInput = document.getElementById("user-input");
  userInput.addEventListener("keyup", function (event) {
    if (event.key === "Enter") {
      const userMessage = userInput.value;
      const chatbox = document.getElementById("chatbox");

      // Display user message on the right
      chatbox.innerHTML += `<div class="user-message">${userMessage}</div>`;

      // Clear the user input
      userInput.value = "";

      // Process user input and provide responses
      handleUserInput(userMessage);
    }
  });

  // Function to handle user input and chatbot responses
  function handleUserInput(userMessage) {
    const chatbotContent = document.getElementById("chatbot-content");

    switch (userMessage.toLowerCase()) {
      case "medicinal applications":
        chatbotContent.innerHTML += `
          <p class="chatbot-message">Great choice! Here's the blog on medicinal applications:</p>
          <button class="chatbot-button-option" onclick="window.location.href = 'https://astrogirll.github.io/blog2.html'">Read Medicinal Application Blog</button>
        `;
        break;
      case "robotic arm":
        chatbotContent.innerHTML += `
          <p class="chatbot-message">Sure thing! Here's the blog on building a robotic arm:</p>
          <button class="chatbot-button-option" onclick="window.location.href = 'https://astrogirll.github.io/blog1.html'">Read Robotic Arm Blog</button>
        `;
        break;
      case "know more about the author":
        chatbotContent.innerHTML += `
          <p class="chatbot-message">You can know more about the author by visiting their About page:</p>
          <button class="chatbot-button-option" onclick="window.location.href = 'https://astrogirll.github.io/About.html'">About the Author</button>
        `;
        break;
      default:
        chatbotContent.innerHTML += `
          <p class="chatbot-message">Thank you for your message. Our team will get back to you.</p>
          <p class="chatbot-message">Please contact tiwarinavya1808@gmail.com</p>
        `;
        break;
    }
  }


  menuButton.addEventListener("click", () => {
    navbar.classList.toggle("responsive");
  });
</script>

</body>
</html>
