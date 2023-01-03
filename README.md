- 👋 Hi, I’m @BRAVOGOTBEATS
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
BRAVOGOTBEATS/BRAVOGOTBEATS is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
  <title>Beat Selling Website</title>
  <style>
    /* Add some styling for the website here */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header a {
      color: white;
      text-decoration: none;
    }
    .beat-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      grid-gap: 20px;
      padding: 20px;
    }
    .beat-card {
      background-color: #f4f4f4;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
      padding: 20px;
    }
    .beat-card h3 {
      margin: 0;
      padding: 0;
    }
    .beat-card p {
      margin: 0;
      padding: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to the Beat Selling Website</h1>
    <p>Browse and purchase beats from top producers</p>
    <a href="#">Log In</a> | <a href="#">Sign Up</a>
  </header>
  <main>
    <div class="beat-grid">
      <!-- Display a grid of beats using a loop -->
      <div class="beat-card">
        <h3>Beat 1</h3>
        <p>Producer: John Doe</p>
        <audio controls>
          <source src="beat1.mp3" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
        <p>Price: $20</p>
        <button>Add to Cart</button>
      </div>
      <div class="beat-card">
        <h3>Beat 2</h3>
        <p>Producer: Jane Doe</p>
        <audio controls>
          <source src="beat2.mp3" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
        <p>Price: $30</p>
        <button>Add to Cart</button>
      </div>
      <!-- Add more beat cards here -->
    </div>
  </main>
  <footer>
    <p>Copyright 2021</p>
  </footer>
  <script>
    // Add some JavaScript to handle adding beats to the cart
    const buttons = document.querySelectorAll('button');
    buttons.forEach((button) => {
      button.addEventListener('click', (event) => {
        // Add the beat to the cart and update the total price
      });
    });
