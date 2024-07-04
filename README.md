# OIBSIP_Task2Level2_TributePage
I Developed this Tribute Page using HTML &amp; CSS , JAVA SCRIPT
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Cristiano Ronaldo</title>
    <style>
      body {
        font-family: "Arial", sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
        color: #333;
      }

      header {
        background-color: #000;
        color: #fff;
        text-align: center;
        padding: 2rem 0;
      }

      header h1 {
        margin: 0;
        font-size: 3rem;
      }

      header p {
        margin: 0;
        font-size: 1.5rem;
        font-weight: 300;
      }

      .quote-section {
        background-color: #fff;
        text-align: center;
        padding: 3rem 1rem;
        position: relative;
      }

      .quote-section img {
        position: absolute;
        right: 2rem;
        top: 50%;
        transform: translateY(-50%);
        max-width: 150px;
        border-radius: 50%;
      }

      .quote-section blockquote {
        margin: 0;
        font-size: 1.5rem;
        font-style: italic;
        color: #555;
      }

      .bio-section {
        background-color: #000;
        color: #fff;
        padding: 3rem 1rem;
        text-align: center;
      }

      .bio-section h2 {
        margin-top: 0;
        font-size: 2rem;
      }

      .bio-section p {
        margin: 1rem 0;
        font-size: 1rem;
        line-height: 1.5;
        max-width: 800px;
        margin: 1rem auto;
      }

      footer {
        text-align: center;
        padding: 1rem 0;
        background-color: #333;
        color: #fff;
      }

      footer p {
        margin: 0;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Cristiano Ronaldo</h1>
      <p>1985 - Present</p>
    </header>

    <section class="quote-section">
      <blockquote>
        "Your love makes me strong, your hate makes me unstoppable."
      </blockquote>
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Cristiano_Ronaldo_2018.jpg"
        alt="Cristiano Ronaldo"
      />
    </section>

    <section class="bio-section">
      <h2>Biography</h2>
      <p>
        Cristiano Ronaldo, born on February 5, 1985, in Madeira, Portugal, is a
        professional soccer player who has won numerous awards and titles. Known
        for his exceptional skills and dedication, he is considered one of the
        greatest players of all time. Ronaldo started his career at Sporting CP
        before moving to Manchester United in 2003. He later played for Real
        Madrid and Juventus, achieving remarkable success at each club.
        Currently, he plays for Al Nassr.
      </p>
    </section>

    <footer>
      <p>&copy; 2024 Cristiano Ronaldo Fan Page. All rights reserved.</p>
    </footer>
  </body>
</html>
