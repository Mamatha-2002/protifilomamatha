# protifilomamatha




<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mamatha Saddikuti | Portfolio</title>
  <!-- <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" /> -->
  <style>
    /* Reset & Base Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #0f0f0f;
      color: #ededed;
      padding-top: 100px;
      line-height: 1.6;
    }

    /* Header */
    .header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      padding: 20px 10%;
      background: #1a1a1a;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.4);
    }

    .logo {
      font-size: 24px;
      color: #00abf0;
      text-decoration: none;
      font-weight: 600;
    }

    .navbar a {
      color: #fff;
      text-decoration: none;
      margin-left: 30px;
      font-size: 16px;
      font-weight: 500;
      transition: 0.3s;
    }

    .navbar a:hover {
      color: #00abf0;
    }

    /* Section Layout */
    .section {
      padding: 80px 10%;
    }

    .section h1, .section h2 {
      font-size: 32px;
      margin-bottom: 20px;
      color: #00abf0;
    }

    .section h3 {
      margin-top: 20px;
      font-size: 20px;
      color: #ffcc00;
    }

    .section ul {
      padding-left: 20px;
    }

    .section ul li {
      margin-bottom: 8px;
      list-style: disc;
    }

    .section p {
      margin-bottom: 15px;
      font-size: 16px;
    }

    /* Contact Section */
    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      background: #1f1f1f;
      color: #fff;
      border-radius: 4px;
    }

    form button {
      padding: 10px 20px;
      background-color: #00abf0;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 4px;
      transition: background 0.3s ease;
    }

    form button:hover {
      background-color: #008ecc;
    }

    /* Links */
    a {
      color: #00abf0;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Responsive Design */
    @media screen and (max-width: 768px) {
      .header {
        flex-direction: column;
        align-items: flex-start;
        padding: 15px 5%;
      }

      .navbar {
        display: flex;
        flex-direction: column;
        margin-top: 10px;
        width: 100%;
      }

      .navbar a {
        margin: 10px 0;
        font-size: 18px;
      }

      .section {
        padding: 60px 5%;
      }

      .section h1 {
        font-size: 28px;
      }

      .section h2 {
        font-size: 24px;
      }
    }

    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header class="header">
    <a href="#" class="logo">Mamatha Saddikuti</a>
    <nav class="navbar">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home" class="section home">
    <h1>Welcome to My Portfolio</h1>
    <p>Hello! I'm Mamatha Saddikuti, a passionate web developer from India.</p>
  </section>

  <!-- About Section -->
  <section id="about" class="section about">
    <h2>About Me</h2>
    <p>
      I’m a self-taught developer who enjoys building creative websites and apps. With a strong foundation in Python, Django, and web development technologies, 
      I am passionate about creating innovative solutions. I am always eager to learn and grow in my field to contribute effectively to a team.
    </p>
    <h3>Contact Information</h3>
    <ul>
      <li>Phone: +91 93920 34731</li>
      <li>Email: <a href="mailto:mammusaddikuti@gmail.com">mammusaddikuti@gmail.com</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/saddikuti-mamatha-430350333" target="_blank">linkedin.com/in/saddikuti-mamatha</a></li>
    </ul>
    <h3>Objective</h3>
    <p>Seeking a challenging role where I can apply my technical skills to drive organizational success and further my growth in the tech industry.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="section skills">
    <h2>Skills</h2>
    <ul>
      <li>Python</li>
      <li>Django</li>
      <li>HTML / CSS / JavaScript</li>
      <li>SQL</li>
      <li>React.js</li>
      <li>Basic Data Structures</li>
    </ul>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="section portfolio">
    <h2>My Work</h2>

    <div class="project">
      <h3>Project 1: Differentially Private Frequent Itemset Mining Algorithm</h3>
      <p>
        Developed an efficient, differential privacy-based algorithm for frequent itemset mining in large-scale datasets. 
        Tackled the challenge of balancing efficiency, privacy, and data utility in frequent itemset mining. 
        Integrated techniques such as sampling and transaction truncation with length constraints to reduce computational complexity and mining sensitivity. 
        Achieved superior performance compared to existing algorithms through experimental results on multiple datasets while maintaining privacy.
      </p>
    </div>

    <div class="project">
      <h3>Project 2: ShopSphere – E-Commerce Web Application</h3>
      <p>
        ShopSphere is a responsive e-commerce web app built using Django, HTML, CSS, and Bootstrap. 
        It features user registration, login, product browsing, shopping cart, and checkout functionality. 
        Users can securely place orders, and the admin can manage products using Django’s admin panel. 
        This project showcases my skills in full-stack development, authentication, and frontend responsiveness.
      </p>
      <p><strong>Technologies:</strong> Python, Django, SQLite, HTML, CSS, Bootstrap, JavaScript</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact">
    <h2>Contact Me</h2>
    <form action="#" method="post">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

</body>
</html>
