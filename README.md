# rosaryReverb.github.io
<!DOCTYPE html>
<html>
  <head>
    <title>My First HTML Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
      }

      header {
        background-color: lightgray;
        padding: 20px;
      }

      nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
      }

      nav a {
        margin-right: 20px;
        text-decoration: none;
        color: black;
      }

      section {
        padding: 20px;
      }

      footer {
        background-color: lightgray;
        padding: 20px;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About Us</h2>
        <p>We are a company dedicated to providing top-quality services to our clients.</p>
      </section>
      <section id="services">
        <h2>Our Services</h2>
        <ul>
          <li>Service 1</li>
          <li>Service 2</li>
          <li>Service 3</li>
        </ul>
      </section>
      <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit-form.php" method="post">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email">
          <label for="message">Message:</label>
          <textarea id="message" name="message"></textarea>
          <input type="submit" value="Submit">
        </form>
      </section>
    </main>
    <footer>
      <p>Copyright &copy; 2023 My Company</p>
    </footer>
  </body>
</html>
