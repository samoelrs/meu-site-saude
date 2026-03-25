<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saúde & Bem-Estar</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f5f5f5;
}

header {
    background: #0f766e;
    color: white;
    padding: 15px;
    text-align: center;
}

nav {
    display: flex;
    justify-content: center;
    background: #115e59;
}

nav a {
    color: white;
    padding: 14px 20px;
    text-decoration: none;
}

nav a:hover {
    background: #134e4a;
}

.container {
    padding: 20px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 3px 8px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
}

.card-content {
    padding: 15px;
}

.card h3 {
    margin: 0 0 10px;
}

.card p {
    font-size: 14px;
    color: #555;
}

.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 12px;
    background: #0f766e;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background: #0f766e;
    color: white;
}
</style>
</head>

<body>

<header>
    <h1>Saúde & Bem-Estar</h1>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Nutrição</a>
    <a href="#">Exercícios</a>
    <a href="#">Mental</a>
    <a href="#">Contato</a>
</nav>

<div class="container">
    <h2>Últimos Posts</h2>

    <div class="grid">

        <div class="card">
            <img src="https://via.placeholder.com/400x200">
            <div class="card-content">
                <h3>Alimentação Saudável</h3>
                <p>Dicas para melhorar sua dieta no dia a dia.</p>
                <a class="btn">Ler mais</a>
            </div>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x200">
            <div class="card-content">
                <h3>Treino em Casa</h3>
                <p>Exercícios simples para fazer sem academia.</p>
                <a class="btn">Ler mais</a>
            </div>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x200">
            <div class="card-content">
                <h3>Saúde Mental</h3>
                <p>Como reduzir o estresse e melhorar sua mente.</p>
                <a class="btn">Ler mais</a>
            </div>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 Saúde & Bem-Estar</p>
</footer>

</body>
</html>
