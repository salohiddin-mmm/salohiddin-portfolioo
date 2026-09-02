<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mening portfolio saytim</title>

  <style>
header button {
  background-color: white;
  color: #2563eb;
}
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4ff;
      color: #1f2937;
      max-width: 700px;
      margin: 40px auto;
      padding: 25px;
    }

    header {
      background-color: #2563eb;
      color: white;
      padding: 30px;
      border-radius: 15px;
      text-align: center;
    }

    section {
      background-color: white;
      margin-top: 20px;
      padding: 20px;
      border-radius: 12px;
    }

    h2, h3 {
      color: #2563eb;
    }

    button {
      background-color: #2563eb;
      color: white;
      border: none;
      padding: 12px 18px;
      border-radius: 8px;
      cursor: pointer;
    }

    input, textarea {
      width: 95%;
      padding: 10px;
      border: 1px solid #cbd5e1;
      border-radius: 6px;
    }

    footer {
      text-align: center;
      margin-top: 25px;
    }
.dark-mode {
  background-color: #111827;
  color: white;
}

.dark-mode section {
  background-color: #1f2937;
}

.dark-mode h2,
.dark-mode h3 {
  color: #93c5fd;
}
.profil-rasmi {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 4px solid white;
  margin: 10px 0;
}
  </style>
</head>

<body>
  <header>
    <h1>Salom, mening ismim Salohiddin</h1>
    <p>Men kelajakdagi web-dasturchiman.</p>
<img class="profil-rasmi" src="https://placehold.co/180x180/ffffff/2563eb?text=S" alt="Salohiddin rasmi">
<button id="theme-button" type="button">Tungi rejim</button>
  </header>


  <main>
    <section>
      <h2>Men haqimda</h2>
      <p>
        Men Mamadaliyev Salohiddin, 2006-yil tug‘ilganman.
        Men dasturlash va sayt yaratishni o‘rganmoqchiman.
      </p>
    </section>

    <section>
      <h2>Ko‘nikmalarim</h2>
      <ul>
        <li>Python</li>
        <li>JavaScript</li>
      </ul>
    </section>

    <section>
      <h2>Bog‘lanish</h2>

      
      </form>
<p>
  <a href="https://t.me/mamadal1evme" target="_blank">
    Telegram orqali yozing
  </a>
</p>
    </section>

    <section>
      <h2>Mening loyihalarim</h2>
      <h3>Portfolio saytim</h3>
      <p>Bu mening birinchi HTML va CSS saytim.</p>
    </section>
  </main>

  <footer>
    <p>© 2026 Mening portfolioim</p>
  </footer>
<script>
  const themeButton = document.getElementById("theme-button");

  themeButton.addEventListener("click", function() {
    document.body.classList.toggle("dark-mode");
  });
</script>

 
</body>
</html>
