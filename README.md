<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>yasmine</title>
  <link rel="icon" type="image/x-icon" href="LOGO.jpg">
  <style>
    body {
      font-family: Ahinds, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1em;
      text-align: center;
    }
    header img {
      width: 60px;
      vertical-align: middle;
    }
    header h1 {
      display: inline;
      margin-left: 10px;
      font-size: 2em;
    }
    nav {
      background-color: #444;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #ddd;
      color: black;
    }
    section {
      padding: 2em;
    }
    .panda-img {
      width: 100%;
      max-width: 400px;
      display: block;
      margin-top: 1em;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1em;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    .panda-container {
  display: flex;
  justify-content: flex-end;
  margin-top: 20px;
}

.animated-panda {
  width: 200px;
  animation: float 3s ease-in-out infinite;
}

@keyframes  {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-15px);
  }
}

  </style>
</head>
<body>

  <header>
    <img src="LOGO.jpg" alt="Site Logo">
    <h1>yasmine</h1>
  </header>

  <nav>
    <a href="#facebook">facebook</a>
    <a href="#youtube">youtube</a>
  </nav>

  <section id="facebook">
    <h2>facebook</h2> 
    <p>facebook nmo</p>
    <a href="https://www.facebook.com/profile.php?id=100077516572274" target="_blank">Facebook</a>
  </section>

  <section id="youtube">
    <h2>youtube</h2>
    <p>youre favorate movie</p>
    <a href="https://www.youtube.com/watch?v=HqGsT6VM8Vg" target="_blank">your favorate to watch</a>
  </section>

  <section id="features">
    <h2>Features</h2>
   
    <img class="panda-img" src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Grosser_Panda.JPG" alt="Cute Panda">
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>0922 AYG TOO AMAW</p>


      
        <div class="panda-container">
          <img class="panda-img animated-panda" src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Grosser_Panda.JPG" alt="Cute Panda">
        </div>
      </section>
      

    <footer>
        <h4>© Copyright Reserved</h4>
       
      </footer>

      </body>
      </html>
