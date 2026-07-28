# projeto-2--site--Violencia-contra-mulher
/* Palette Visual - Tons de Rosa */
:root {
  --bg-primary: #fff5f7;
  --bg-card: #ffffff;
  --text-primary: #4a2e35;
  --accent-color: #d63384;
  --accent-hover: #b8256f;
  --accent-soft: #f8d7da;
  --text-muted: #72525a;
  --border-color: #f5c2c7;
}

/* Modo Alto Contraste */
body.alto-contraste {
  --bg-primary: #1a0a10;
  --bg-card: #2b121a;
  --text-primary: #ffffff;
  --accent-color: #ff66a3;
  --accent-hover: #ff85b3;
  --accent-soft: #4a1525;
  --text-muted: #e0b0bc;
  --border-color: #661f35;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  transition: background-color 0.3s, color 0.3s;
}

body {
  background-color: var(--bg-primary);
  color: var(--text-primary);
  line-height: 1.6;
  font-size: 16px;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

header {
  background-color: var(--bg-card);
  border-bottom: 2px solid var(--border-color);
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.logo h1 {
  color: var(--accent-color);
  font-size: 1.5rem;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 1.5rem;
}

nav a {
  text-decoration: none;
  color: var(--text-primary);
  font-weight: 600;
}

nav a.active, nav a:hover {
  color: var(--accent-color);
  border-bottom: 2px solid var(--accent-color);
}

.acessibilidade button {
  padding: 0.3rem 0.6rem;
  margin-left: 0.3rem;
  cursor: pointer;
  background-color: var(--accent-soft);
  color: var(--text-primary);
  border: 1px solid var(--border-color);
  border-radius: 4px;
  font-weight: bold;
}

main {
  flex: 1;
  max-width: 900px;
  margin: 2rem auto;
  padding: 0 1rem;
}

.hero, .container-escuta, .container-quiz, .container-referencias {
  background-color: var(--bg-card);
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(214, 51, 132, 0.08);
  border: 1px solid var(--border-color);
}

.boas-vindas {
  font-size: 1.15rem;
  margin: 1rem 0;
  color: var(--text-muted);
}

.card-destaque {
  border-left: 5px solid var(--accent-color);
  padding: 1.2rem;
  background-color: var(--bg-primary);
  margin-top: 1.5rem;
  border-radius: 0 8px 8px 0;
}

/* Seção de Relatos */
.secao-relatos {
  margin-top: 2rem;
}

.grid-relatos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

.card-relato {
  background-color: var(--bg-primary);
  border: 1px solid var(--border-color);
  padding: 1rem;
  border-radius: 8px;
}

.card-relato h4 {
  color: var(--accent-color);
  margin-bottom: 0.5rem;
}

.card-relato p {
  font-size: 0.95rem;
  font-style: italic;
}

.btn-acao, .btn-enviar {
  display: inline-block;
  background-color: var(--accent-color);
  color: #fff;
  padding: 0.75rem 1.5rem;
  border: none;
  border-radius: 6px;
  text-decoration: none;
  margin-top: 1rem;
  cursor: pointer;
  font-size: 1rem;
  font-weight: bold;
}

.btn-acao:hover, .btn-enviar:hover {
  background-color: var(--accent-hover);
}

.alerta-simulacao {
  background-color: var(--accent-soft);
  color: var(--text-primary);
  padding: 0.75rem;
  border-radius: 6px;
  margin: 1rem 0;
  border-left: 4px solid var(--accent-color);
}

blockquote.frase-motivacional {
  font-style: italic;
  margin: 1rem 0;
  padding-left: 1rem;
  border-left: 3px solid var(--accent-color);
}

form label {
  display: block;
  margin-top: 1rem;
  font-weight: bold;
}

input[type="text"], textarea {
  width: 100%;
  padding: 0.8rem;
  margin-top: 0.5rem;
  border: 1px solid var(--border-color);
  border-radius: 6px;
  background-color: var(--bg-primary);
  color: var(--text-primary);
}

.hidden {
  display: none;
}

.card-resposta {
  margin-top: 1.5rem;
  padding: 1.5rem;
  border-radius: 8px;
  background-color: var(--bg-primary);
  border: 1px solid var(--accent-color);
}

.orientacoes-ajuda {
  margin-top: 2rem;
}

.orientacoes-ajuda ul {
  margin-left: 1.5rem;
  margin-top: 0.5rem;
}

.questao {
  margin-bottom: 1.5rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--border-color);
}

.pergunta {
  font-weight: bold;
  margin-bottom: 0.5rem;
}

footer {
  text-align: center;
  padding: 1.5rem;
  background-color: var(--bg-card);
  border-top: 1px solid var(--border-color);
  margin-top: auto;
}

#btn-topo {
  margin-top: 0.5rem;
  padding: 0.4rem 0.8rem;
  cursor: pointer;
  background-color: var(--accent-soft);
  border: 1px solid var(--border-color);
  border-radius: 4px;
}