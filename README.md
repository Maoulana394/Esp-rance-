<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Espérance</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --primary-color:#013220;       /* Couleur principale */
      --background-color: #191970;   /* Couleur de fond */
      --text-color: #333;            /* Couleur du texte */
      --button-bg: #6A5ACD;          /* Boutons */
      --button-text: #fff;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: var(--background-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
    }

    header {
      background-color: var(--primary-color);
      color: white;
      padding: 20px;
      text-align: center;
    }

    main {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h1, h2 {
      margin-top: 0;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    li {
      background-color: #f1f1f1;
      margin: 10px 0;
      padding: 10px;
      border-radius: 5px;
    }

    form label {
      display: block;
      margin-top: 10px;
    }

    form input, form textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }

    form button {
      background-color: var(--primary-color);
      color: white;
      padding: 10px 20px;
      border: none;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 4px;
    }

    form button:hover {
      background-color: #0c4b33; /* couleur plus foncée */
    }

    .links {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      margin-top: 30px;
    }

    .button-link {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      background-color: var(--button-bg);
      color: var(--button-text);
      padding: 12px 24px;
      border: none;
      border-radius: 30px;
      text-decoration: none;
      font-size: 16px;
      transition: background-color 0.3s;
    }

    .button-link:hover {
      background-color: #483D8B; /* plus foncé au survol */
    }

    .button-link i {
      margin-right: 8px;
      font-style: normal; /* pour l'icône emoji */
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
    }

    /* Responsive */
    @media (max-width: 600px) {
      main {
        margin: 10px;
        padding: 15px;
      }
      .button-link {
        width: 80%;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Espérance</h1>
    <p>Bienvenue sur ma page personnelle !</p>
  </header>

  <main>
    <section id="presentation">
      <h2>À propos de moi</h2>
      <p>Salut ! Je suis saidMaoulana, passionné par l'avenir. Bienvenue sur ma page personnelle Espérance !</p>
    </section>

    <section id="projets">
      <h2>Mes Projets</h2>
      <ul>
        <li><strong>Projet 1 :</strong> Description rapide du projet 1.</li>
        <li><strong>Projet 2 :</strong> Description rapide du projet 2.</li>
        <li><strong>Projet 3 :</strong> Description rapide du projet 3.</li>
      </ul>
    </section>

    <section id="liens">
      <h2>Rejoignez-moi</h2>
      <div class="links">
        <a href="https://espérance.com" class="button-link" target="_blank">
          <i>🦅</i> Rejoindre ma page
        </a>
        <a href="https://wa.me/+2693945354" class="button-link" target="_blank">
          <i>💬</i> Contactez-moi sur WhatsApp
        </a>
        <a href="https://instagram.com/tonprofil" class="button-link" target="_blank">
          <i>📸</i> Suivez-moi sur Instagram
        </a>
      </div>
    </section>

    <section id="contact">
      <h2>Contactez-moi</h2>
      <form action="mailto:abdillahsaidmaoulana@gmail.com?subject=Contact depuis votre site Espérance" method="POST" enctype="text/plain">
        <label for="name">Nom :</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Téléphone :</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="message">Message :</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Envoyer</button>
      </form>
    </section>
  </main>

  <footer>
    &copy; 2025 Said Maoulana — Tous droits réservés
  </footer>
</body>
</html>
