<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Bienvenue sur mon Application – Formidable</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
*{
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}
body{
    margin:0;
    background:#f2f2f2;
}
/* HEADER */
header{
    background:linear-gradient(135deg,#0d47a1,#1976d2);
    color:white;
    padding:20px;
    text-align:center;
}
/* LOGO */
.logo img{
    height:60px;
}
/* HERO IMAGE */
.hero img{
    width:100%;
    max-height:250px;
    object-fit:cover;
}
/* CONTAINER */
.container{
    max-width:450px;
    margin:20px auto;
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}
/* FORM */
input{
    width:100%;
    padding:12px;
    margin:8px 0;
    border-radius:6px;
    border:1px solid #ccc;
}
button{
    width:100%;
    padding:12px;
    background:#1976d2;
    color:white;
    border:none;
    border-radius:6px;
    font-size:16px;
    cursor:pointer;
}
button:hover{
    background:#0d47a1;
}
.link{
    text-align:center;
    margin-top:10px;
}
.link a{
    color:#1976d2;
    font-weight:bold;
    cursor:pointer;
}
/* PARTNER */
.partner{
    background:#e3f2fd;
    padding:15px;
    border-radius:8px;
    margin-top:15px;
    text-align:center;
}
/* HIDE */
.hidden{
    display:none;
}
/* FOOTER */
footer{
    text-align:center;
    font-size:12px;
    padding:15px;
    color:#555;
}
</style>
</head>
<body>
<header>
    <div class="logo">
        <!-- LOGO DE TON SITE -->
        <img src="c:\Users\USER\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\F7177163C833DFF4B38FC8D2872F1EC6\WhatsApp Image 2025-12-16 à 16.47.21_c06a8077.jpg">
    </div>
    <h2>Bienvenue📊 sur une Application 🏠 Formidable Pour decouvrir une nouvelle monde⭐vip</h2>
</header>
<!-- IMAGE PRINCIPALE -->
<div class="hero">
    <img src="c:\Users\USER\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\17E62166FC8586DFA4D1BC0E1742C08B\WhatsApp Image 2025-12-16 à 16.44.00_48eae90f.jpg">
</div>
<div class="container">
    <!-- CONNEXION -->
    <div id="login">
        <h3>Connexion</h3>
        <input type="email" placeholder="Email" name="email">
        <input type="password" placeholder="Mot de passe" name="password">
       <a href="https://www.google.com"> <button onclick="login()">Se connecter</button></a>
        <div class="link">
            <nav>
            Pas de compte ? <li><a href="creeruncompte.html" text aling="center">Créer un compte</a></li>
            </nav>

        </div>
    </div>
    <!-- INSCRIPTION -->
    <div id="register" class="hidden">
        <h3>Inscription</h3>
        <input type="text" placeholder="Nom complet">
        <input type="text" placeholder="prenom complet">
        <input type="email" placeholder="Email">
        <input type="password" placeholder="Mot de passe">
        <button onclick="register()">S'inscrire</button>
        <div class="link">
            Déjà inscrit ? <a onclick="showLogin()">Connexion</a>
        </div>
    </div>
    <!-- PARTENARIAT -->
    <div class="partner">
        <h4>🏢 Entreprise Publique Partenaire📊</h4>
        <p>
            Gagnez de l'argent légalement grâce à :
            <br>✔ affiliation
            <br>✔ services numériques
            <br>✔ publicité officielle
        </p>
        <!-- LIEN OFFICIEL (EXEMPLE) -->
        <a href="https://www.google.com" target="_blank">
            <a href="https://www.instagram.com" target="_blank">
                <a href="https://www.tiktok.com" target="_blank">
                    <a href="https://www.vidmat.com" target="_blank">
                        <a href="https://www.Youtube.com" target="_blank">
            <button>Accéder au partenaire officiel</button>
        </a>
    </div>
</div>
<footer>
    App – SEAF-ARTH EN 2026 VIP
</footer>
<script>
function showRegister(){
    document.getElementById("login").classList.add("hidden");
    document.getElementById("register").classList.remove("hidden");
}
function showLogin(){
    document.getElementById("register").classList.add("hidden");
    document.getElementById("login").classList.remove("hidden");
}
function login(){
    alert("Connexion réussie (démo)");
}
