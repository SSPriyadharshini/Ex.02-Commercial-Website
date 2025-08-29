# Ex02 Commercial Website

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Business Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(90deg, #0077b6, #00b4d8);
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffdd00;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(to right, #e0f7fa, #f1f8e9);
    }
    .hero h2 {
      font-size: 40px;
      margin-bottom: 20px;
      color: #0077b6;
    }
    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }
    .btn {
      background: #0077b6;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #00b4d8;
    }
    section {
      padding: 50px 20px;
      width: 80%;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #0077b6;
    }
    .services {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .service-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .service-card:hover {
      transform: translateY(-5px);
    }
    .testimonials {
      background: #e3f2fd;
      padding: 50px 20px;
      text-align: center;
    }
    .testimonial {
      margin: 20px auto;
      max-width: 600px;
      font-style: italic;
    }
    .contact {
      text-align: center;
    }
    .contact p {
      font-size: 18px;
    }
    footer {
      background: #0077b6;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>MyBusiness</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#clients">Clients</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to MyBusiness</h2>
    <p>We provide professional solutions to help your business grow.</p>
    <button class="btn">Get Started</button>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Web Development</h3>
        <p>Custom websites tailored to your needs.</p>
      </div>
      <div class="service-card">
        <h3>Digital Marketing</h3>
        <p>Boost your brand with online campaigns.</p>
      </div>
      <div class="service-card">
        <h3>Consulting</h3>
        <p>Expert advice to scale your business.</p>
      </div>
    </div>
  </section>

  <section id="clients" class="testimonials">
    <h2>What Our Clients Say</h2>
    <div class="testimonial">
      "MyBusiness helped us launch our website and grow online. Highly recommend!"
      <br>– Client A
    </div>
    <div class="testimonial">
      "Their consulting services transformed our workflow. Great team!"
      <br>– Client B
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: info@mybusiness.com</p>
    <p>Phone: +91 9876543210</p>
    <p>Location: Chennai, India</p>
  </section>

  <footer>
    © <span id="year"></span> MyBusiness. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>


## OUTPUT
<img width="1878" height="876" alt="image" src="https://github.com/user-attachments/assets/46875eac-ad7b-41ed-aa37-91b73cccc019" />
<img width="1904" height="806" alt="image" src="https://github.com/user-attachments/assets/921a9516-ecce-4cb4-91a9-3e1a9b204d31" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
