<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Emerald Enigma Community</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🗝️ Emerald Enigma Community 🗝️</h1>
    <p>Welcome, Soul Seeker. Share your thoughts, truths, and transmissions.</p>
  </header>

  <main>
    <section class="form-section">
      <form id="postForm">
        <input type="text" id="username" placeholder="Your Mystic Name" required />
        <textarea id="message" placeholder="Speak your truth here..." required></textarea>
        <button type="submit">Post Message</button>
      </form>
    </section>

    <section class="board" id="messageBoard">
      <!-- Messages appear here -->
    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>
