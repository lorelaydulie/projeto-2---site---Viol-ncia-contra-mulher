:root {
    /* Paleta inspirada na Kushina Uzumaki */
    --primary: #d90429;             /* Vermelho vibrante (Cabelo da Kushina) */
    --primary-hover: #ef233c;       /* Vermelho mais claro para interações */
    --primary-dark: #8d0801;        /* Carmesim profundo */
    --sakura-pink: #ffb7c5;         /* Tom suave de Flor de Sakura */
    --bg-color: #fff0f3;           /* Fundo suave rosado/claro */
    --bg-alt: #ffffff;
    --text-color: #2b2d42;
    --card-bg: #ffffff;
    --border-color: #ffccd5;
    --font-size-base: 16px;
}

/* Modo Alto Contraste */
body.alto-contraste {
    --primary: #ffff00;
    --primary-hover: #ffd700;
    --primary-dark: #ffff00;
    --sakura-pink: #ffff00;
    --bg-color: #000000;
    --bg-alt: #1a1a1a;
    --text-color: #ffffff;
    --card-bg: #111111;
    --border-color: #ffff00;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    transition: background-color 0.3s, color 0.3s;
}

html {
    scroll-behavior: smooth;
    font-size: var(--font-size-base);
}

body {
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
    /* Padrão sutil de flores de Sakura usando SVG no background */
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='80' height='80' viewBox='0 0 100 100'%3E%3Cpath fill='%25ffb7c5' opacity='0.25' d='M50 30 C45 15, 30 15, 35 30 C20 25, 15 40, 30 45 C15 50, 20 65, 35 60 C30 75, 45 75, 50 60 C55 75, 70 75, 65 60 C80 65, 85 50, 70 45 C85 40, 80 25, 65 30 C70 15, 55 15, 50 30 Z'/%3E%3Ccircle cx='50' cy='45' r='4' fill='%25d90429' opacity='0.3'/%3E%3C/svg%3E");
}

/* Barra Superior de Acessibilidade */
.top-bar {
    background-color: var(--primary-dark);
    padding: 8px 5%;
    display: flex;
    justify-content: flex-end;
    gap: 10px;
    border-bottom: 2px solid var(--sakura-pink);
}

.top-bar button {
    background: transparent;
    border: 1px solid var(--sakura-pink);
    color: #fff;
    padding: 5px 10px;
    cursor: pointer;
    border-radius: 4px;
    font-size: 0.85rem;
}
m;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 600;
}

.form-group input, .form-group textarea {
    width: 100%;
    padding: 0.8rem;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-family: inherit;
    font-size: 1rem;
}

.form-group input:focus, .form-group textarea:focus {
    outline: none;
    border-color: var(--primar
.top-bar button:hover {
    background-color: var(--primary-hover);
}

/* Header & Nav */
header {
    background-color: var(--bg-alt);
    padding: 1rem 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 3px solid var(--primary);
    box-shadow: 0 4px 10px rgba(217, 4, 41, 0.1);
}

.logo {
    font-size: 1.4rem;
    font-weight: bold;
    color: var(--primary);
}

.logo i {
    color: var(--primary-hover);
}

nav ul {
    display: flex;
    list-style: none;
    gap: 20px;
}

nav a {
    text-decoration: none;
    color: var(--text-color);
    font-weight: 600;
    position: relative;
    padding-bottom: 4px;
}

nav a:hover {
    color: var(--primary);
}

nav a::after {
    content: '🌸';
    font-size: 0.6rem;
    position: absolute;
    right: -12px;
    top: -2px;
    opacity: 0;
    transition: opacity 0.2s;
}

nav a:hover::after {
    opacity: 1;
}

/* Hero / Início */
.hero {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    padding: 4rem 5%;
    align-items: center;
}

.hero-card {
    background-color: var(--card-bg);
    padding: 30px;
    border-radius: 16px;
    border: 2px solid var(--border-color);
    box-shadow: 0 8px 20px rgba(217, 4, 41, 0.08);
    text-align: center;
    position: relative;
    overflow: hidden;
}

/* Detalhe de flor de sakura no canto do card */
.hero-card::before {
    content: '🌸';
    font-size: 3rem;
    position: absolute;
    top: -10px;
    right: -10px;
    opacity: 0.4;
}

.main-icon {
    font-size: 4rem;
    color: var(--primary);
    margin-bottom: 15px;
}

/* Seções Gerais */
.section-container m;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 600;
}

.form-group input, .form-group textarea {
    width: 100%;
    padding: 0.8rem;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-family: inherit;
    font-size: 1rem;
}

.form-group input:focus, .form-group textarea:focus {
    outline: none;
    border-color: var(--primar{
    padding: 4rem 5%;
    max-width: 1000px;
    margin: 0 auto;
}

.bg-alt {
    background-color: var(--bg-alt);
    border-radius: 16px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.03);
}

.subtitle {
    margin-bottom: 20px;
    opacity: 0.85;
}

/* Form de Escuta */
#form-escuta {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

textarea {
    width: 100%;
    padding: 12px;
    border-radius: 8px;
    border: 2px solid var(--border-color);
    background-color: var(--card-bg);
    color: var(--text-color);
    font-size: 1rem;
}

textarea:focus {
    outline: none;
    border-color: var(--primary);
}

.resposta-box {
    margin-top: 20px;
    background-color: var(--card-bg);
    padding: 20px;
    border-radius: 12px;
    border-left: 6px solid var(--primary);
    box-shadow: 0 4px 12px rgba(217, 4, 41, 0.1);
}

.check-icon {
    color: var(--primary);
    font-size: 1.5rem;
    margin-bottom: 10px;
}

/* Quiz */
.opcoes-grid {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin-top: 20px;
}

.opcao-btn {
    padding: 12px 16px;
    border: 2px solid var(--border-color);
    background-color: var(--card-bg);
    color: var(--text-color);
    border-radius: 8px;
    cursor: pointer;
    text-align: left;
    font-size: 1rem;
    font-weight: 500;
}

.opcao-btn:hover {
    background-color: var(--primary);
    color: #ffffff;
    border-color: var(--primary);
}

/* Botões */
.btn-primary {
    background-color: var(--primary);
    color: #ffffff;
    border: none;
    padding: 12px 24px;
    border-radius: 30px;
    cursor: pointer;
    font-weight: bold;
    text-decoration: none;
    display: inline-block;
    box-shadow: 0 4px 12px rgba(217, 4, 41, 0.3);
}

.btn-primary:hover {
    background-color: var(--primary-hover);
}

/* Lista Referências */
.lista-referencias {
    list-style: none;
}

.lista-referencias li {
    margin-bottom: 15px;
    padding: 10px;
    background-color: var(--card-bg);
    border-radius: 8px;
    border: 1px solid var(--border-color);
}

.lista-referencias a {
    color: var(--primary);
    font-weight: bold;
    text-decoration: none;
}

.lista-referencias a:hover {
    text-decoration: underline;
}

/* Voltar ao Topo */
#btn-topo {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: var(--primary);
    color: white;
    border: 2px solid var(--sakura-pink);
    padding: 12px 15px;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

#btn-topo:hover {
    background-color: var(--primary-dark);
}

.hidden {
    display: none;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: var(--primary-dark);
    color: #ffffff;
    margin-top: 40px;
    border-top: 3px solid var(--sakura-pink);
}

/* Responsividade */
@media (max-width: 768px) {
    .hero {
        grid-template-columns: 1fr;
    }
    nav ul {
        flex-direction: column;
        gap: 10px;
    }
}