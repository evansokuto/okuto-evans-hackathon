<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="OKUTO EVANS OMONDI" content="width=device-width, initial-scale=1.0">
  <title>OKUTO EVANS OMONDI</title>
  <link rel="stylesheet" href="portfoliostyle.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>OKUTO EVANS OMONDI</h1>

    <h2>PROFILE PICTURE</h2>
    
    <img src="OKUTO.jpg" alt="profile Picture" width="200" height="200">

     <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <h1>Welcome to My Portfolio</h1>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Okuto Evans Omondi,I am a passionate Agricultural Economics with a keen interest in software Developmnet.</p>
  </section>


  <section id="education">
    <h2>Educational Background</h2>
    <ul>
      <li>MSC.Agricultural and applied Economics (JKUAT), 2024-to date</li>
      <li>BSC.Agricultural Economics and Rural Developmnet (JKUAT), 2019-2023</li>
      <li>software Developmnet (PLP), 2025- to date</li>
      <li>Kenya Certificate of secondary Education (KCSE), 2018</li>
    </ul>
    <body>
      <h1>Download Section</h1>
      <a href="okuto jnr cv.pdf" download>
        <button>Downlaod CV</button>
      </a>
    </body>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Data analyst</li>
      <li>Agronomist</li>
      <li>Python</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me Through</h2>
      <button><a href="https://www.linkedin.com/in/okuto-evans-858970293/">LinkedIn</a></button>
      <p>whatsapp: +254 768950554</p>
      <p>Email:evansokuto2019@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2025 OKUTO EVANS OMODNI. All rights reserved.</p>
  </footer>
</body>
</html>






portfoliostyle.css


/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
  }
  
  nav ul {
    list-style-type: none;
  }
  
  nav ul li {
    display: inline;
    margin: 0 10px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  section {
    padding: 20px;
  }
  
  #about {
    background-color: #f4f4f4;
  }
 
  
  #skills ul {
    list-style-type: square;
  }
  
  form input, form textarea {
    width: calc(100% - 20px);
  }
  
  button {
    background-color: rgba(235, 220, 85, 0.734);
  }
  
  /* Footer */
  footer {
    text-align: center;
  }
