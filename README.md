<!DOCTYPE html>
<html lang="fr">
<head>
   <meta charset="UTF-8">
   <title>Mon premier site</title>
   <link rel="stylesheet" href="style.css">
</head>

<body>
   <header>
       <h1>Bienvenue sur mon site</h1>
   </header>

   <main>
       <p>Bonjour 👋, ceci est mon premier site web.</p>

       <p class="highlight">
           Je suis en train d'apprendre le HTML et le CSS !
       </p>

       <a href="https://google.com" target="_blank">Aller sur Google</a>
   </main>

   <footer>
       <p>© 2026 - Mon site</p>
   </footer>
</body>
</html>

2. Fichier style.css
body {
   font-family: Arial, sans-serif;
   background-color: #f2f2f2;
   text-align: center;
}

h1 {
   color: #2c3e50;
}

p {
   font-size: 18px;
}

.highlight {
   color: white;
   background-color: #3498db;
   padding: 10px;
   border-radius: 5px;
}

a {
   display: inline-block;
   margin-top: 20px;
   text-decoration: none;
   color: white;
   background-color: #e74c3c;
   padding: 10px 15px;
   border-radius: 5px;
}

footer {
   margin-top: 40px;
   font-size: 14px;
}
