<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Alice in Wonderland Garden Party</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      background: linear-gradient(135deg, #fbe8eb, #fdf6e3, #e2ecf5);
      color: #4b3b2b;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      max-width: 800px;
      background: linear-gradient(90deg, #e7c6ff, #ffc8dd, #fde2e4);
      width: 90%;
      padding: 1.5rem 0;
      text-align: center;
      box-shadow: 0 3px 5px rgba(0,0,0,0.1);
      margin-bottom: 20px;
      color: #5a3e36;
    }

    h1 {
      margin: 0;
      font-size: 2.5rem;
      text-shadow: 1px 1px 2px rgba(255, 255, 255, 0.6);
    }

    main {
      max-width: 800px;
      background: #fffaf4;
      padding: 2rem;
      border-radius: 16px;
      box-shadow: 0 6px 16px rgba(75, 54, 43, 0.1);
      text-align: center;
      width: 90%;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 1.4rem;
      color: #5c4b51;
    }

    .info {
      font-size: 1.2rem;
      margin-bottom: 2rem;
      color: #3f2a2a;
      font-weight: bold;
    }

    form {
      display: flex;
      flex-direction: column;
      align-items: stretch;
      gap: 1rem;
      margin-top: 2rem;
    }

    input, textarea {
      padding: 0.7rem;
      font-size: 1rem;
      border-radius: 10px;
      border: 1px solid #d4cfc7;
      width: 100%;
      box-sizing: border-box;
      background-color: #fffdf9;
      color: #3e3e3e;
    }

    button {
      background-color: #cdb4db;
      color: #fff;
      border: none;
      padding: 0.9rem;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 10px;
      cursor: pointer;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    button:hover {
      background-color: #b392ac;
      transform: scale(1.05);
    }

    footer {
      margin-top: 40px;
      font-size: 1rem;
      font-weight: 600;
      color: #7a6f74;
      text-align: center;
      padding-bottom: 2rem;
    }

    .canva-embed-container {
      position: relative;
      width: 100%;
      height: 0;
      padding-top: 56.25%;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      margin-top: 2rem;
    }

    .canva-embed-container iframe {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      border: none;
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 2rem;
      }

      main {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Alice in Wonderland Garden Party</h1>
  </header>

  <main>
    <p>
      Somewhere between dream and daylight, in a secret garden where time ticks backward and teacups talk, you are invited to a magical celebration with Alice and her curious friends! 🌸🐇🫖
    </p>
    <p>
      Join us for an afternoon of wonder, riddles, sweet treats, and nonsensical joy. The Mad Hatter is hosting, the Queen has agreed to be nice (just for a day), and the White Rabbit promised not to be late!
    </p>

    <p class="info">
      📅 <strong>Date:</strong> July 5th, 2025<br>
      ⏰ <strong>Time:</strong> 4:00 PM<br>
      📍 <strong>Location:</strong> Doctorasi’s Garden – Râu Alb de Sus, Ciobănești Street<br>
      🍰 <strong>Bring a Dish:</strong> Sweet or savory, curious or classic – surprise us!
    </p>

    <!-- Canva presentation embedded here -->
    <div class="canva-embed-container">
      <iframe loading="lazy" src="https://www.canva.com/design/DAGobpyx0HM/jRgHwBkX4fRDaHfGrDvcrw/view?embed" allowfullscreen="allowfullscreen"></iframe>
    </div>

    <form action="https://formsubmit.co/vertitheunknown@gmail.com" method="POST">
      <input type="hidden" name="_redirect" value="https://google.com" />
      <input type="text" name="_honey" style="display:none" />
      <input type="hidden" name="_captcha" value="false" />

      <input type="text" name="Name" placeholder="Your name" required />
      <input type="text" name="Guests" placeholder="Number of guests (if any)" />
      <textarea name="Comments" rows="4" placeholder="Comments (what you’ll bring, questions, etc.)"></textarea>
      <button type="submit">Send RSVP</button>
    </form>
  </main>

  <footer>
    <p>We can't wait to see you down the rabbit hole! 🎩✨</p>
  </footer>

</body>
</html>
