<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MS Dhoni - A Tribute</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="banner">
    <img src="dhoni.jpg" alt="MS Dhoni batting image">
    <h1>MS Dhoni - Captain Cool</h1>
  </header>

  <main>
    <section class="biography">
      <h2>The Rise of a Legend</h2>
      <p>Write a brief biography about MS Dhoni, including his hometown, early life, and journey to cricket.</p>
    </section>

    <section class="achievements">
      <h2>Behind the Stumps - A Captain's Masterclass</h2>
      <ul>
        <li>List some of Dhoni's major achievements as a captain (World Cup wins, ICC trophies etc.)</li>
        <li>Mention his famous finishing touches and cool temperament under pressure.</li>
      </ul>
    </section>

    <section class="quotes">
      <h2>Dhoni's Words of Wisdom</h2>
      <p>"Quote 1 by MS Dhoni"</p>
      <p>"Quote 2 by MS Dhoni"</p>
    </section>

    <section class="fan-messages">
      <h2>#ThankYouDhoni - Messages from Fans</h2>
      <form action="" method="post">
        <label for="message">Leave a message for Dhoni:</label>
        <textarea name="message" id="message"></textarea>
        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Dhoni Tribute Page</p>
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.banner {
  background-image: url("bg-cricket.jpg"); /* Replace with background image */
  background-size: cover;
  background-position: center;
  padding: 50px;
  text-align: center;
  color: white;
}

.banner img {
  width: 200px;
  border-radius: 50%;
  margin-bottom: 20px;
}

h1 {
  font-size: 3em;
  margin-bottom: 10px;
}

main {
  padding: 50px;
}

section {
  margin-bottom: 30px;
}

h2 {
  font-size: 2em;
  margin-bottom: 10px;
}

.achievements ul {
  list-style: none;
  padding: 0;
}

.achievements li {
  margin-bottom: 10px;
}

.quotes {
  border-left: 1px solid #ddd;
  padding-left: 20px;
}

.fan-messages form {
  display: flex;
  flex-direction: column;
  margin-bottom: 10px;
}

.fan-messages label {
  margin-bottom: 5px;
}

.fan-messages textarea {
  padding: 10px;
  border: 1px solid #ddd;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #f2f2f2;
}

