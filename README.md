# CN116
Team Name : Code Crushers
Team Code : CN116
Problem Statement : Organizing events, whether they're conferences, weddings, or corporate gatherings, involves numerous tasks such as venue selection, attendee registration, agenda planning, and logistics coordination. Traditional methods of managing events through spreadsheets or manual processes can be inefficient and error-prone. Your task is to develop an event management website that streamlines the entire event planning process, from initial setup to post-event evaluation, providing organizers with the tools they need to plan, promote, and execute successful events seamlessly.
Problem Code 
HTML :
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Event Management Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Event Management System</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Events</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2><strong>Welcome to Event Horizon</h2>
      <p>"Enabling event excellence for any Occasion"</p>
      <a href="#" class="btn">Get Started</a>
    </div>
  </section>

  <section class="features">
    <div class="container">
      <h2>Key Features :</h2>
      <div class="feature">
        <h3>Event Creation and Management</h3>
        <p>Implement tools for organizers to create and manage events.</p>
      </div>
      <div class="feature">
        <h3>Event Registration and Attendance Tracking</h3>
        <p>Provide attendees with an easy-to-use registration system.</p>
      </div>
      <div class="feature">
        <h3>Event Promotion and Communication</h3>
        <p>Integrate features for promoting events and facilitating communication.</p>
      </div>
      <div class="feature">
        <h3>Calendar Integration</h3>
        <p>Integrate a centralized calendar system for displaying upcoming events.</p>
      </div>
      <div class="feature">
        <h3>Feedback and Evaluation</h3>
        <p>Collect feedback from attendees and provide analytics to organizers.</p>
      </div>
      <div class="feature">
        <h3>Resource Sharing and Collaboration</h3>
        <p>Offer a platform for sharing resources and enabling collaboration among members.</p>
      </div>
      <h2>About Us :</h2>
      <div class="feature">
        
        <p>Welcome to Event Horizon, where we specialize in crafting extraordinary events tailored to your unique vision. With years of experience and a passion for perfection, we have established ourselves as leaders in the industry, dedicated to orchestrating seamless and unforgettable experiences.</p>

          <p>Our Journey</p>
          <p>At Event Horizon, we understand that organizing events, whether they're conferences, weddings, or corporate gatherings, involves a multitude of tasks. From venue selection to attendee registration, agenda planning, and logistics coordination, every detail matters. Recognizing the challenges posed by traditional event management methods, we embarked on a mission to revolutionize the industry.</p>
          
          <p>Our Mission</p>
          <p>Our mission is simple yet ambitious: to streamline the entire event planning process, from initial setup to post-event evaluation. We empower organizers with the tools they need to plan, promote, and execute successful events seamlessly. With our innovative technology solutions and dedicated team of event professionals, we ensure that your event journey is smooth, efficient, and stress-free.</p>
          
          
      </div>
    </div>
  </section>

  
  <footer>
    <div class="container">
      <p>&copy; 2024 Event Management Website. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>


CSS: 
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #dcb69a;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
  }
  
  header h1 {
    margin: 0;
  }
  
  nav ul {
    list-style: none;
    padding: 0;
  }
  
  nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  .hero {
    background-image: url('hero-background.jpg'); /* Add your hero background image */
    background-size: cover;
    color: #fff;
    padding: 15px 0;
    text-align: center;
  }
  
  .hero h2 {
    margin-bottom: 10px;
    font-size: 35px;
    vertical-align: top;
  }
  
  .btn {
    display: inline-block;
    background-color: #ff6600;
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }
  
  .btn:hover {
    background-color: #e55e00;
  }
  
  .features {
    padding: 50px 0;
  }
  
  .features .feature {
    margin-bottom: 20px;
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  .features .feature h3 {
    color: #333;
  }
  
  .features .feature p {
    color: #666;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }

  
  
