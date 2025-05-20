<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home</title>
    <style>
      :root {
        background-color: #e9260db6;
        --primary: 7d05ec;
        --accent: #332b2b;
        --bg-dark: #b56559;
        --bg-light: rgba(255, 255, 255, 0.06);
        --glass: rgba(255, 255, 255, 0.08);
        --text-light: #ddd;
        --text-dark: #222;
      }

      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(135deg, var(--bg-dark), #2f2f4f);
        color: var(--text-light);
        padding: 60px 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
      }

      .blog-container {
        background: var(--glass);
        backdrop-filter: blur(15px);
        border-radius: 24px;
        padding: 60px;
        width: 100%;
        max-width: 1400px;
        box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
        border: 1px solid #b4331f;
        display: flex;
        flex-direction: column;
        gap: 40px;
      }

      header {
        text-align: center;
      }

      header h1 {
        font-size: 42px;
        color: var(--accent);
        margin-bottom: 10px;
        display: inline-block;
        border-bottom: 2px solid #7b5d5a;
      }

      header p {
        font-size: 18px;
        color: #ccc;
      }

      nav {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 25px;
        background: var(--bg-light);
        padding: 15px 25px;
        border-radius: 16px;
      }

      nav a {
        color: var(--accent);
        text-decoration: none;
        font-weight: 600;
        position: relative;
        transition: color 0.3s ease;
      }

      nav a::after {
        content: "";
        position: absolute;
        bottom: -6px;
        left: 0;
        width: 0;
        height: 2px;
        background-color: var(--primary);
        transition: width 0.3s ease;
      }

      nav a:hover {
        color: #fff;
      }

      nav a:hover::after {
        width: 100%;
      }

      .content {
        display: flex;
        flex-direction: column;
      }

      .main-content {
        background: var(--bg-light);
        padding: 40px;
        border-radius: 20px;
        box-shadow: 0 6px 30px rgba(0, 0, 0, 0.25);
      }

      h2 {
        font-size: 26px;
        margin-bottom: 20px;
        color: var(--accent);
        border-bottom: 2px solid var(--primary);
        padding-bottom: 10px;
      }

      p {
        font-size: 16px;
        line-height: 1.6;
        color: var(--text-light);
      }

      footer {
        text-align: center;
        font-size: 15px;
        color: #aaa;
        padding: 20px;
        background: var(--bg-light);
        border-radius: 16px;
      }

      @media (max-width: 768px) {
        header h1 {
          font-size: 32px;
        }
      }
    </style>
  </head>
  <body>
    <div class="blog-container" role="main">
      <header>
        <h1>Welcome To My Webpage</h1>
        <p>Sharing knowledge about Web Design, HTML5, CSS, and JavaScript</p>
      </header>

      <nav aria-label="Main navigation">
        <a href="home.html">Home</a>
        <a href="TRYaboutme.html">About</a>
        <a href="TRYGallery.html">Gallery</a>
        <a href="Contact.html">Contact</a>
        <a href="Dash.html">Dashboard</a>
        <a href="Menu.html">Menu</a>
      </nav>

      <div class="content">
        <article class="main-content">
          <h2>Understanding HTML5 Semantics!</h2>
          <p>
            HTML5 brought forth new semantic elements that enhance the
            organization of web pages, increasing their accessibility and
            responsiveness for contemporary web development semantics refers to
            using HTML tags that accurately convey the meaning and purpose of
            the content they enclose, rather than just defining its appearance.
            This makes the HTML code more understandable for both developers and
            search engines. Semantic HTML elements, provide a meaningful
            description of the content's role within a web page.
          </p>
        </article>
      </div>

      <footer>&copy; 2025 - MALABANAN All rights reserved.</footer>
    </div>
  </body>
</html>

