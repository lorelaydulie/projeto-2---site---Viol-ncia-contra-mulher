<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Laços que Protegem | Portal de Apoio ao Estudante</title>

    <meta
        name="description"
        content="Portal de apoio ao estudante sobre inclusão, respeito às diferenças e combate ao preconceito."
    >

    <link rel="stylesheet" href="style.css">

    <!-- Ícones -->
    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
    >
</head>

<body>

    <!-- =========================
         ACESSIBILIDADE
    ========================== -->

    <div class="accessibility-bar">

        <button id="fontIncrease" title="Aumentar fonte">
            <i class="fa-solid fa-plus"></i> A+
        </button>

        <button id="fontDecrease" title="Diminuir fonte">
            <i class="fa-solid fa-minus"></i> A-
        </button>

        <button id="contrastButton" title="Alto contraste">
            <i class="fa-solid fa-circle-half-stroke"></i>
            Alto contraste
        </button>

        <button id="darkModeButton" title="Modo escuro">
            <i class="fa-solid fa-moon"></i>
            Modo escuro
        </button>

    </div>


    <!-- =========================
         CABEÇALHO
    ========================== -->

    <header class="header">

        <nav class="navbar">

            <a href="#inicio" class="logo">
                <span class="logo-flower">🌺</span>
                Laços que Protegem
            </a>

            <button class="menu-button" id="menuButton">
                <i class="fa-solid fa-bars"></i>
            </button>

            <ul class="nav-links" id="navLinks">

                <li>
                    <a href="#inicio">
                        <i class="fa-solid fa-house"></i>
                        Início
                    </a>
                </li>

                <li>
                    <a href="#sobre">
                        <i class="fa-solid fa-heart"></i>
                        Respeito
                    </a>
                </li>

                <li>
                    <a href="#escuta">
                        <i class="fa-solid fa-ear-listen"></i>
                        Portal de Escuta
                    </a>
                </li>

                <li>
                    <a href="#quiz">
                        <i class="fa-solid fa-circle-question"></i>
                        Quiz
                    </a>
                </li>

                <li>
                    <a href="#referencias">
                        <i class="fa-solid fa-book"></i>
                        Referências
                    </a>
                </li>

            </ul>

        </nav>

    </header>


    <main>

        <!-- =========================
             HERO / INÍCIO
        ========================== -->

        <section id="inicio" class="hero">

            <div class="hero-decoration flower-one">🌸</div>
            <div class="hero-decoration flower-two">🌺</div>
            <div class="hero-decoration flower-three">🌼</div>

            <div class="hero-content">

                <div class="hero-text">

                    <span class="small-title">
                        🌺 PORTAL DE APOIO AO ESTUDANTE
                    </span>

                    <h1>
                        Laços que <span>Protegem</span>
                    </h1>

                    <h2>
                        Respeito, inclusão e acolhimento contra o preconceito.
                    </h2>

                    <p>
                        Um espaço criado para lembrar que cada pessoa tem
                        sua própria história, sua própria identidade e seu
                        próprio jeito de ser.
                    </p>

                    <p>
                        Assim como os laços que unem uma família, uma amizade
                        ou uma comunidade, o respeito também nos conecta.
                    </p>

                    <div class="hero-buttons">

                        <a href="#escuta" class="button primary-button">
                            <i class="fa-solid fa-heart"></i>
                            Preciso conversar
                        </a>

                        <a href="#quiz" class="button secondary-button">
                            <i class="fa-solid fa-gamepad"></i>
                            Fazer o Quiz
                        </a>

                    </div>

                </div>


                <div class="hero-character">

                    <div class="flower-circle">
                        🌸 🌺 🌸
                    </div>

                    <div class="character-card">

                        <div class="character-glow"></div>

                        <img
                            src="images/kushina.jpg"
                            alt="Kushina Uzumaki cercada por flores"
                            class="kushina-image"
                        >

                        <div class="character-caption">
                            <strong>Kushina Uzumaki</strong>
                            <span>
                                Representação de força, carinho e proteção
                            </span>
                        </div>

                    </div>

                </div>

            </div>

            <div class="scroll-indicator">
                <i class="fa-solid fa-chevron-down"></i>
            </div>

        </section>


        <!-- =========================
             SOBRE / RESPEITO
        ========================== -->

        <section id="sobre" class="section">

            <div class="section-heading">

                <span class="section-label">
                    <i class="fa-solid fa-seedling"></i>
                    RESPEITO
                </span>

                <h2>
                    Diferenças não são defeitos.
                </h2>

                <p>
                    Uma escola acolhedora é construída quando todos podem
                    existir, aprender e se expressar com segurança.
                </p>

            </div>


            <div class="cards">

                <article class="info-card">

                    <div class="card-icon red">
                        <i class="fa-solid fa-people-group"></i>
                    </div>

                    <h3>Inclusão</h3>

                    <p>
                        Incluir significa criar espaço para que todas as
                        pessoas participem e sejam respeitadas,
                        independentemente de suas características.
                    </p>

                </article>


                <article class="info-card">

                    <div class="card-icon pink">
                        <i class="fa-solid fa-heart"></i>
                    </div>

                    <h3>Empatia</h3>

                    <p>
                        Tente compreender como outra pessoa pode estar se
                        sentindo antes de julgar ou agir. Ouvir também é
                        uma forma de cuidar.
                    </p>

                </article>


                <article class="info-card">

                    <div class="card-icon orange">
                        <i class="fa-solid fa-hand"></i>
                    </div>

                    <h3>Respeito</h3>

                    <p>
                        Respeitar diferenças de aparência, cultura,
                        personalidade, origem e opiniões ajuda a construir
                        relações mais saudáveis.
                    </p>

                </article>


                <article class="info-card">

                    <div class="card-icon purple">
                        <i class="fa-solid fa-shield-heart"></i>
                    </div>

                    <h3>Proteção</h3>

                    <p>
                        Situações de bullying, discriminação ou violência
                        não devem ser enfrentadas em silêncio. Procure
                        alguém de confiança.
                    </p>

                </article>

            </div>


            <div class="quote-box">

                <div class="quote-flower">
                    🌺
                </div>

                <div>
                    <blockquote>
                        "Sua diferença não diminui seu valor.
                        Ela faz parte da sua história."
                    </blockquote>

                    <span>
                        — Mensagem do Portal Laços que Protegem
                    </span>
                </div>

            </div>

        </section>


        <!-- =========================
             TIPOS DE PRECONCEITO
        ========================== -->

        <section class="section red-section">

            <div class="section-heading light">

                <span class="section-label">
                    <i class="fa-solid fa-scale-balanced"></i>
                    CONSCIENTIZAÇÃO
                </span>

                <h2>
                    Preconceito pode aparecer de muitas formas.
                </h2>

                <p>
                    Reconhecer atitudes preconceituosas é um passo importante
                    para combatê-las.
                </p>

            </div>


            <div class="prejudice-grid">

                <div class="prejudice-item">
                    <i class="fa-solid fa-globe"></i>
                    <h3>Xenofobia</h3>
                    <p>
                        Preconceito ou hostilidade contra pessoas de outras
                        nacionalidades ou origens.
                    </p>
                </div>

                <div class="prejudice-item">
                    <i class="fa-solid fa-people-arrows"></i>
                    <h3>Racismo</h3>
                    <p>
                        Discriminação ou inferiorização de pessoas por
                        características raciais ou étnicas.
                    </p>
                </div>

                <div class="prejudice-item">
                    <i class="fa-solid fa-wheelchair"></i>
                    <h3>Capacitismo</h3>
                    <p>
                        Preconceitos e barreiras dirigidos a pessoas com
                        deficiência.
                    </p>
                </div>

                <div class="prejudice-item">
                    <i class="fa-solid fa-comments"></i>
                    <h3>Bullying</h3>
                    <p>
                        Agressões ou humilhações que podem ocorrer
                        presencialmente ou no ambiente digital.
                    </p>
                </div>

            </div>

        </section>


        <!-- =========================
             PORTAL DE ESCUTA
        ========================== -->

        <section id="escuta" class="section listening-section">

            <div class="section-heading">

                <span class="section-label">
                    <i class="fa-solid fa-ear-listen"></i>
                    PORTAL DE ESCUTA
                </span>

                <h2>
                    Você não precisa guardar tudo sozinho.
                </h2>

                <p>
                    Este espaço é uma simulação para você escrever aquilo
                    que gostaria de colocar para fora.
                </p>

            </div>


            <div class="listening-container">

                <div class="listening-message">

                    <div class="big-flower">
                        🌺
                    </div>

                    <h3>
                        Estamos aqui para ouvir.
                    </h3>

                    <p>
                        Escrever pode ajudar a organizar os sentimentos.
                        Mas lembre-se: este formulário é apenas uma
                        simulação e nenhuma informação será armazenada.
                    </p>

                    <div class="support-list">

                        <div>
                            <i class="fa-solid fa-user-tie"></i>
                            <span>Converse com um professor de confiança.</span>
                        </div>

                        <div>
                            <i class="fa-solid fa-school"></i>
                            <span>Procure a coordenação ou direção.</span>
                        </div>

                        <div>
                            <i class="fa-solid fa-house-user"></i>
                            <span>Converse com familiares ou responsáveis.</span>
                        </div>

                        <div>
                            <i class="fa-solid fa-hand-holding-heart"></i>
                            <span>Procure outro adulto em quem confie.</span>
                        </div>

                    </div>

                </div>


                <div class="listening-form-card">

                    <form id="listeningForm">

                        <label for="name">
                            Como podemos chamar você?
                        </label>

                        <input
                            type="text"
                            id="name"
                            placeholder="Seu nome ou apelido (opcional)"
                        >


                        <label for="feeling">
                            Como você está se sentindo?
                        </label>

                        <select id="feeling">

                            <option value="">
                                Escolha uma opção
                            </option>

                            <option>Triste</option>
                            <option>Ansioso(a)</option>
                            <option>Com raiva</option>
                            <option>Confuso(a)</option>
                            <option>Com medo</option>
                            <option>Preciso apenas conversar</option>

                        </select>


                        <label for="message">
                            Escreva seu desabafo:
                        </label>

                        <textarea
                            id="message"
                            rows="7"
                            placeholder="Escreva aqui o que você gostaria de compartilhar..."
                            required
                        ></textarea>


                        <div class="privacy-note">

                            <i class="fa-solid fa-lock"></i>

                            <span>
                                Este formulário é somente uma simulação.
                                Nenhuma informação será enviada ou armazenada.
                            </span>

                        </div>


                        <button
                            type="submit"
                            class="button primary-button full-button"
                        >
                            <i class="fa-solid fa-paper-plane"></i>
                            Enviar desabafo
                        </button>

                    </form>


                    <div
                        id="supportResponse"
                        class="support-response"
                        aria-live="polite"
                    ></div>

                </div>

            </div>

        </section>


        <!-- =========================
             FRASES
        ========================== -->

        <section class="motivational-section">

            <div class="motivational-flower">
                🌸
            </div>

            <h2 id="motivationalPhrase">
                "Você merece ser tratado com respeito."
            </h2>

            <p>
                <i class="fa-solid fa-heart"></i>
                Sua voz importa.
            </p>

            <button id="newPhrase" class="phrase-button">
                <i class="fa-solid fa-wand-magic-sparkles"></i>
                Outra mensagem
            </button>

        </section>


        <!-- =========================
             QUIZ
        ========================== -->

        <section id="quiz" class="section quiz-section">

            <div class="section-heading">

                <span class="section-label">
                    <i class="fa-solid fa-gamepad"></i>
                    QUIZ INTERATIVO
                </span>

                <h2>
                    Você está preparado para combater o preconceito?
                </h2>

                <p>
                    Responda às cinco perguntas e descubra sua pontuação.
                </p>

            </div>


            <div class="quiz-card">

                <div class="quiz-progress">
                    <span id="questionNumber">Pergunta 1 de 5</span>

                    <div class="progress-bar">
                        <div id="progress"></div>
                    </div>
                </div>


                <div id="quizContent">

                    <h3 id="question">
                        Carregando pergunta...
                    </h3>

                    <div id="answers"></div>

                </div>


                <button
                    id="nextQuestion"
                    class="button primary-button quiz-next"
                    disabled
                >
                    Próxima pergunta
                    <i class="fa-solid fa-arrow-right"></i>
                </button>


                <div
                    id="quizResult"
                    class="quiz-result"
                ></div>

            </div>

        </section>


        <!-- =========================
             REFERÊNCIAS
        ========================== -->

        <section id="referencias" class="section references-section">

            <div class="section-heading">

                <span class="section-label">
                    <i class="fa-solid fa-book-open"></i>
                    REFERÊNCIAS
                </span>

                <h2>
                    Informação confiável também é uma forma de proteção.
                </h2>

                <p>
                    Estas são algumas das fontes utilizadas para construir
                    o conteúdo educativo do portal.
                </p>

            </div>


            <div class="references-list">

                <article class="reference-card">

                    <div class="reference-icon">
                        <i class="fa-solid fa-earth-americas"></i>
                    </div>

                    <div>

                        <h3>UNICEF Brasil</h3>

                        <p>
                            Materiais sobre educação, proteção,
                            violência e prevenção no ambiente escolar.
                        </p>

                        <a
                            href="https://www.unicef.org/brazil/educacao-que-protege"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            Acessar fonte
                            <i class="fa-solid fa-arrow-up-right-from-square"></i>
                        </a>

                    </div>

                </article>


                <article class="reference-card">

                    <div class="reference-icon">
                        <i class="fa-solid fa-school"></i>
                    </div>

                    <div>

                        <h3>UNICEF — Comunidade Escolar</h3>

                        <p>
                            Cartilha com orientações para prevenção e
                            resposta às violências nas escolas.
                        </p>

                        <a
                            href="https://www.unicef.org/brazil/relatorios/comunidade-escolar-na-prevencao-e-resposta-as-violencias"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            Acessar fonte
                            <i class="fa-solid fa-arrow-up-right-from-square"></i>
                        </a>

                    </div>

                </article>


                <article class="reference-card">

                    <div class="reference-icon">
                        <i class="fa-solid fa-landmark"></i>
                    </div>

                    <div>

                        <h3>Governo Federal — Escola que Protege</h3>

                        <p>
                            Informações sobre políticas de proteção e
                            enfrentamento da violência no ambiente escolar.
                        </p>

                        <a
                            href="https://www.gov.br/igualdaderacial/pt-br/assuntos/programas-e-projetos/politicas-intergovernamentais/educacao/perguntas-e-respostas/programa-escola-que-protege"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            Acessar fonte
                            <i class="fa-solid fa-arrow-up-right-from-square"></i>
                        </a>

                    </div>

                </article>


                <article class="reference-card">

                    <div class="reference-icon">
                        <i class="fa-solid fa-city"></i>
                    </div>

                    <div>

                        <h3>Secretaria Municipal da Educação de Curitiba</h3>

                        <p>
                            Materiais do programa Escola que Protege,
                            incluindo conteúdos sobre bullying e convivência escolar.
                        </p>

                        <a
                            href="https://educacao.curitiba.pr.gov.br/conteudo/programa-escola-que-protege/15699"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            Acessar fonte
                            <i class="fa-solid fa-arrow-up-right-from-square"></i>
                        </a>

                    </div>

                </article>

            </div>


            <div class="academic-note">

                <i class="fa-solid fa-circle-info"></i>

                <p>
                    <strong>Importante:</strong>
                    o Portal de Escuta deste projeto é uma simulação
                    acadêmica. Ele não substitui atendimento profissional
                    nem os canais oficiais de proteção.
                </p>

            </div>

        </section>

    </main>


    <!-- =========================
         RODAPÉ
    ========================== -->

    <footer class="footer">

        <div class="footer-flower">
            🌺
        </div>

        <h2>
            Laços que Protegem
        </h2>

        <p>
            Inclusão • Respeito • Empatia • Acolhimento
        </p>

        <div class="footer-line"></div>

        <p class="copyright">
            Projeto Individual — Portal de Apoio ao Estudante
        </p>

        <p class="inspiration">
            Inspirado na força e no carinho de Kushina Uzumaki 🌺
        </p>

    </footer>


    <!-- VOLTAR AO TOPO -->

    <button
        id="backToTop"
        class="back-to-top"
        title="Voltar ao topo"
    >
        <i class="fa-solid fa-arrow-up"></i>
    </button>


    <script src="script.js"></script>

</body>
</html>/* =========================================
   CONFIGURAÇÕES GERAIS
========================================= */

:root {
    --red: #b91c3c;
    --dark-red: #74152b;
    --light-red: #e94d6d;
    --pink: #f48fb1;
    --soft-pink: #fff0f4;
    --orange: #f28c28;
    --purple: #8e5aa8;

    --cream: #fffaf5;
    --white: #ffffff;
    --black: #211b1d;
    --gray: #686063;
    --light-gray: #f5f1f2;

    --shadow:
        0 15px 45px rgba(96, 24, 45, 0.13);

    --radius: 24px;

    --font-size: 16px;
}


/* =========================================
   RESET
========================================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    font-size: var(--font-size);
}

body {
    font-family:
        "Segoe UI",
        Arial,
        sans-serif;

    color: var(--black);
    background: var(--cream);

    line-height: 1.7;

    overflow-x: hidden;

    transition:
        background 0.3s ease,
        color 0.3s ease;
}

img {
    max-width: 100%;
    display: block;
}

button,
input,
textarea,
select {
    font: inherit;
}

button {
    cursor: pointer;
}

a {
    color: inherit;
    text-decoration: none;
}


/* =========================================
   ACESSIBILIDADE
========================================= */

.accessibility-bar {
    background: #32131e;
    color: white;

    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 8px;

    padding: 8px 5%;

    position: relative;
    z-index: 1000;
}

.accessibility-bar button {
    background: transparent;
    color: white;

    border: 1px solid rgba(255,255,255,0.3);

    border-radius: 8px;

    padding: 6px 10px;

    transition: 0.2s;
}

.accessibility-bar button:hover,
.accessibility-bar button:focus {
    background: white;
    color: var(--dark-red);
}


/* =========================================
   HEADER
========================================= */

.header {
    position: sticky;
    top: 0;
    z-index: 999;

    background: rgba(255, 250, 245, 0.94);

    backdrop-filter: blur(15px);

    border-bottom: 1px solid #ead9dd;
}

.navbar {
    max-width: 1200px;
    margin: auto;

    min-height: 78px;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 0 24px;
}

.logo {
    font-size: 1.25rem;
    font-weight: 800;

    color: var(--dark-red);

    display: flex;
    align-items: center;
    gap: 8px;
}

.logo-flower {
    font-size: 1.6rem;
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 5px;

    list-style: none;
}

.nav-links a {
    padding: 10px 14px;

    border-radius: 10px;

    font-weight: 600;
    font-size: 0.9rem;

    transition: 0.25s;
}

.nav-links a:hover {
    background: var(--soft-pink);
    color: var(--red);
}

.menu-button {
    display: none;

    background: transparent;
    border: none;

    color: var(--red);

    font-size: 1.5rem;
}


/* =========================================
   HERO
========================================= */

.hero {
    min-height: 720px;

    position: relative;
    overflow: hidden;

    background:
        radial-gradient(
            circle at 85% 20%,
            rgba(244, 143, 177, 0.35),
            transparent 25%
        ),
        linear-gradient(
            135deg,
            #fffaf5 0%,
            #fff0f4 55%,
            #ffe4ec 100%
        );

    display: flex;
    align-items: center;
}

.hero::before {
    content: "";

    position: absolute;

    width: 500px;
    height: 500px;

    right: -180px;
    bottom: -200px;

    background: rgba(185, 28, 60, 0.08);

    border-radius: 50%;
}

.hero-content {
    width: min(1200px, 92%);

    margin: auto;

    display: grid;
    grid-template-columns: 1.05fr 0.95fr;

    align-items: center;

    gap: 60px;

    position: relative;
    z-index: 2;
}

.small-title,
.section-label {
    color: var(--red);

    font-weight: 800;

    letter-spacing: 1.5px;

    font-size: 0.8rem;
}

.hero h1 {
    font-size: clamp(3.5rem, 7vw, 6.2rem);

    line-height: 1;

    margin: 15px 0;

    color: var(--dark-red);
}

.hero h1 span {
    color: var(--red);
}

.hero h2 {
    max-width: 650px;

    font-size: 1.55rem;

    color: #55343e;

    margin-bottom: 20px;
}

.hero p {
    max-width: 650px;

    color: var(--gray);

    margin-bottom: 10px;
}

.hero-buttons {
    display: flex;
    flex-wrap: wrap;

    gap: 14px;

    margin-top: 28px;
}


/* =========================================
   BOTÕES
========================================= */

.button {
    border: none;

    padding: 13px 22px;

    border-radius: 13px;

    font-weight: 800;

    display: inline-flex;

    align-items: center;
    justify-content: center;

    gap: 9px;

    transition:
        transform 0.2s,
        box-shadow 0.2s;
}

.button:hover {
    transform: translateY(-3px);
}

.primary-button {
    background: var(--red);

    color: white;

    box-shadow:
        0 8px 25px rgba(185, 28, 60, 0.25);
}

.primary-button:hover {
    background: var(--dark-red);
}

.secondary-button {
    background: white;

    color: var(--red);

    border: 2px solid #edcbd4;
}

.full-button {
    width: 100%;
}


/* =========================================
   PERSONAGEM
========================================= */

.hero-character {
    display: flex;
    justify-content: center;

    position: relative;
}

.character-card {
    width: min(410px, 90vw);

    padding: 13px;

    background: white;

    border-radius: 45px;

    box-shadow:
        0 30px 70px rgba(106, 27, 51, 0.22);

    transform: rotate(2deg);

    position: relative;

    overflow: hidden;

    animation: floating 5s ease-in-out infinite;
}

.character-glow {
    position: absolute;

    width: 250px;
    height: 250px;

    background: #f48fb1;

    filter: blur(70px);

    opacity: 0.3;

    top: -100px;
    right: -100px;
}

.kushina-image {
    width: 100%;
    height: 490px;

    object-fit: cover;

    border-radius: 35px;

    position: relative;
}

.character-caption {
    padding: 15px 10px 10px;

    display: flex;
    flex-direction: column;
}

.character-caption strong {
    color: var(--dark-red);

    font-size: 1.2rem;
}

.character-caption span {
    color: var(--gray);

    font-size: 0.85rem;
}

.flower-circle {
    position: absolute;

    z-index: 4;

    top: -30px;
    left: -30px;

    font-size: 2rem;

    letter-spacing: 8px;

    transform: rotate(-12deg);
}

.hero-decoration {
    position: absolute;

    z-index: 1;

    animation: floating 4s ease-in-out infinite;
}

.flower-one {
    top: 20%;
    left: 4%;

    font-size: 3rem;
}

.flower-two {
    bottom: 12%;
    left: 45%;

    font-size: 2rem;
}

.flower-three {
    top: 15%;
    right: 5%;

    font-size: 2.5rem;
}


/* =========================================
   SEÇÕES
========================================= */

.section {
    width: min(1200px, 92%);

    margin: auto;

    padding: 100px 0;
}

.section-heading {
    max-width: 800px;

    margin: 0 auto 55px;

    text-align: center;
}

.section-heading h2 {
    color: var(--dark-red);

    font-size: clamp(2rem, 4vw, 3rem);

    line-height: 1.2;

    margin: 12px 0;
}

.section-heading p {
    color: var(--gray);
}


/* =========================================
   CARDS
========================================= */

.cards {
    display: grid;

    grid-template-columns:
        repeat(4, 1fr);

    gap: 20px;
}

.info-card {
    background: white;

    padding: 28px;

    border-radius: var(--radius);

    box-shadow: var(--shadow);

    border: 1px solid #f0dfe4;

    transition:
        transform 0.3s,
        box-shadow 0.3s;
}

.info-card:hover {
    transform: translateY(-8px);

    box-shadow:
        0 25px 55px rgba(96, 24, 45, 0.17);
}

.card-icon {
    width: 55px;
    height: 55px;

    border-radius: 15px;

    display: grid;
    place-items: center;

    color: white;

    font-size: 1.35rem;

    margin-bottom: 20px;
}

.card-icon.red {
    background: var(--red);
}

.card-icon.pink {
    background: #e86a91;
}

.card-icon.orange {
    background: var(--orange);
}

.card-icon.purple {
    background: var(--purple);
}

.info-card h3 {
    color: var(--dark-red);

    margin-bottom: 8px;
}

.info-card p {
    color: var(--gray);

    font-size: 0.9rem;
}


/* =========================================
   QUOTE
========================================= */

.quote-box {
    margin-top: 50px;

    background:
        linear-gradient(
            135deg,
            var(--dark-red),
            var(--red)
        );

    color: white;

    padding: 35px;

    border-radius: var(--radius);

    display: flex;

    align-items: center;

    gap: 25px;

    box-shadow: var(--shadow);
}

.quote-flower {
    font-size: 3.2rem;
}

.quote-box blockquote {
    font-size: 1.5rem;

    font-weight: 700;

    margin-bottom: 5px;
}

.quote-box span {
    opacity: 0.8;

    font-size: 0.85rem;
}


/* =========================================
   SEÇÃO VERMELHA
========================================= */

.red-section {
    width: 100%;
    max-width: none;

    padding-left: 5%;
    padding-right: 5%;

    background:
        radial-gradient(
            circle at 10% 20%,
            rgba(255,255,255,0.1),
            transparent 25%
        ),
        linear-gradient(
            135deg,
            #71142b,
            #b91c3c
        );

    color: white;
}

.light h2,
.light p,
.light .section-label {
    color: white;
}

.prejudice-grid {
    max-width: 1200px;

    margin: auto;

    display: grid;

    grid-template-columns:
        repeat(4, 1fr);

    gap: 20px;
}

.prejudice-item {
    padding: 28px;

    border-radius: var(--radius);

    background: rgba(255,255,255,0.1);

    border: 1px solid rgba(255,255,255,0.2);

    transition: 0.3s;
}

.prejudice-item:hover {
    background: rgba(255,255,255,0.16);

    transform: translateY(-5px);
}

.prejudice-item i {
    font-size: 2rem;

    color: #ffd4df;

    margin-bottom: 18px;
}

.prejudice-item h3 {
    margin-bottom: 7px;
}

.prejudice-item p {
    color: #ffe9ef;

    font-size: 0.9rem;
}


/* =========================================
   ESCUTA
========================================= */

.listening-container {
    display: grid;

    grid-template-columns: 0.8fr 1.2fr;

    gap: 30px;

    align-items: stretch;
}

.listening-message {
    background:
        linear-gradient(
            145deg,
            #7b1830,
            #b91c3c
        );

    color: white;

    padding: 45px;

    border-radius: var(--radius);

    box-shadow: var(--shadow);
}

.big-flower {
    font-size: 3rem;

    margin-bottom: 10px;
}

.listening-message h3 {
    font-size: 2rem;

    margin-bottom: 10px;
}

.listening-message p {
    color: #ffe7ed;
}

.support-list {
    margin-top: 30px;

    display: grid;

    gap: 17px;
}

.support-list div {
    display: flex;

    gap: 12px;

    align-items: flex-start;
}

.support-list i {
    color: #ffd0dc;

    margin-top: 5px;
}

.listening-form-card {
    background: white;

    border-radius: var(--radius);

    padding: 35px;

    box-shadow: var(--shadow);

    border: 1px solid #f0dfe4;
}

.listening-form-card label {
    display: block;

    font-weight: 800;

    color: var(--dark-red);

    margin: 15px 0 7px;
}

.listening-form-card input,
.listening-form-card select,
.listening-form-card textarea {
    width: 100%;

    padding: 13px 15px;

    border: 2px solid #eadde1;

    border-radius: 12px;

    outline: none;

    background: #fffafa;

    color: var(--black);

    transition: 0.2s;
}

.listening-form-card input:focus,
.listening-form-card select:focus,
.listening-form-card textarea:focus {
    border-color: var(--red);

    box-shadow:
        0 0 0 4px rgba(185,28,60,0.1);
}

.listening-form-card textarea {
    resize: vertical;
}

.privacy-note {
    background: #fff3f6;

    color: #734651;

    padding: 13px;

    border-radius: 12px;

    margin: 15px 0;

    display: flex;

    gap: 10px;

    font-size: 0.82rem;
}

.support-response {
    display: none;

    margin-top: 20px;

    padding: 20px;

    background: #fff0f4;

    border-left: 5px solid var(--red);

    border-radius: 12px;

    color: #5c2634;
}


/* =========================================
   FRASES
========================================= */

.motivational-section {
    padding: 80px 20px;

    text-align: center;

    background:
        radial-gradient(
            circle at center,
            #ffe0e9,
            #fff5f7
        );

    position: relative;
}

.motivational-flower {
    font-size: 3rem;

    margin-bottom: 15px;
}

.motivational-section h2 {
    color: var(--dark-red);

    font-size: clamp(1.8rem, 4vw, 3rem);

    max-width: 800px;

    margin: auto;
}

.motivational-section p {
    color: var(--red);

    margin: 10px 0 20px;
}

.phrase-button {
    background: white;

    border: 2px solid #edcbd4;

    color: var(--red);

    padding: 10px 18px;

    border-radius: 10px;

    font-weight: 700;
}


/* =========================================
   QUIZ
========================================= */

.quiz-section {
    background: var(--cream);
}

.quiz-card {
    max-width: 800px;

    margin: auto;

    background: white;

    border-radius: 30px;

    padding: 40px;

    box-shadow: var(--shadow);

    border: 1px solid #f0dfe4;
}

.quiz-progress {
    color: var(--gray);

    font-weight: 700;

    margin-bottom: 30px;
}

.progress-bar {
    height: 8px;

    background: #f0e4e7;

    border-radius: 20px;

    margin-top: 10px;

    overflow: hidden;
}

#progress {
    width: 20%;

    height: 100%;

    background: var(--red);

    border-radius: inherit;

    transition: width 0.3s;
}

#question {
    color: var(--dark-red);

    font-size: 1.5rem;

    margin-bottom: 25px;
}

.answer-button {
    width: 100%;

    text-align: left;

    background: #fffafa;

    border: 2px solid #eadde1;

    color: var(--black);

    padding: 15px;

    border-radius: 12px;

    margin-bottom: 10px;

    transition: 0.2s;
}

.answer-button:hover:not(:disabled) {
    border-color: var(--red);

    background: #fff1f4;
}

.answer-button.correct {
    background: #e4f7eb;

    border-color: #36a269;

    color: #17613a;
}

.answer-button.wrong {
    background: #ffe7ea;

    border-color: #d64256;

    color: #821d2d;
}

.answer-button:disabled {
    cursor: default;
}

.quiz-next {
    margin-top: 20px;

    width: 100%;
}

.quiz-result {
    display: none;

    text-align: center;

    padding: 30px;

    margin-top: 20px;

    border-radius: 20px;

    background: #fff0f4;
}

.quiz-result h3 {
    color: var(--dark-red);

    font-size: 2rem;

    margin-bottom: 8px;
}


/* =========================================
   REFERÊNCIAS
========================================= */

.references-list {
    max-width: 900px;

    margin: auto;

    display: grid;

    gap: 15px;
}

.reference-card {
    background: white;

    border: 1px solid #f0dfe4;

    box-shadow: 0 8px 25px rgba(96, 24, 45, 0.07);

    padding: 22px;

    border-radius: 18px;

    display: flex;

    gap: 18px;

    align-items: flex-start;
}

.reference-icon {
    min-width: 50px;
    height: 50px;

    background: var(--soft-pink);

    color: var(--red);

    display: grid;

    place-items: center;

    border-radius: 12px;
}

.reference-card h3 {
    color: var(--dark-red);

    margin-bottom: 4px;
}

.reference-card p {
    color: var(--gray);

    font-size: 0.9rem;

    margin-bottom: 8px;
}

.reference-card a {
    color: var(--red);

    font-weight: 800;

    font-size: 0.85rem;
}

.academic-note {
    max-width: 900px;

    margin: 30px auto 0;

    padding: 20px;

    background: #fff3f6;

    border-radius: 15px;

    display: flex;

    gap: 12px;

    color: #6d3442;
}

.academic-note i {
    color: var(--red);

    margin-top: 5px;
}


/* =========================================
   FOOTER
========================================= */

.footer {
    text-align: center;

    background: #32131e;

    color: white;

    padding: 55px 20px;
}

.footer-flower {
    font-size: 2.5rem;
}

.footer h2 {
    margin: 10px 0;

    color: #ffd6e1;
}

.footer p {
    color: #e9bdc9;

    font-size: 0.9rem;
}

.footer-line {
    width: 80px;

    height: 2px;

    background: var(--light-red);

    margin: 25px auto;
}

.inspiration {
    margin-top: 10px;
}


/* =========================================
   VOLTAR AO TOPO
========================================= */

.back-to-top {
    position: fixed;

    right: 25px;
    bottom: 25px;

    width: 50px;
    height: 50px;

    border: none;

    border-radius: 50%;

    background: var(--red);

    color: white;

    box-shadow: 0 8px 25px rgba(185,28,60,0.3);

    opacity: 0;

    visibility: hidden;

    transition: 0.3s;

    z-index: 500;
}

.back-to-top.visible {
    opacity: 1;

    visibility: visible;
}

.back-to-top:hover {
    transform: translateY(-3px);
}


/* =========================================
   ANIMAÇÕES
========================================= */

@keyframes floating {

    0%,
    100% {
        transform: translateY(0) rotate(2deg);
    }

    50% {
        transform: translateY(-12px) rotate(2deg);
    }
}


/* =========================================
   MODO ESCURO
========================================= */

body.dark-mode {
    --cream: #171114;
    --white: #231a1e;
    --black: #f9e9ed;
    --gray: #cbbbc0;
    --light-gray: #251b20;

    background: #171114;
    color: #f9e9ed;
}

body.dark-mode .header {
    background: rgba(23,17,20,0.94);

    border-color: #3d2a31;
}

body.dark-mode .nav-links a:hover {
    background: #342027;
}

body.dark-mode .hero {
    background:
        radial-gradient(
            circle at 85% 20%,
            rgba(185,28,60,0.25),
            transparent 25%
        ),
        #1d1518;
}

body.dark-mode .hero h1,
body.dark-mode .hero h2,
body.dark-mode .section-heading h2,
body.dark-mode .info-card h3,
body.dark-mode #question,
body.dark-mode .listening-message h3,
body.dark-mode .reference-card h3 {
    color: #ffd8e1;
}

body.dark-mode .info-card,
body.dark-mode .quiz-card,
body.dark-mode .listening-form-card,
body.dark-mode .reference-card {
    background: #241a1f;

    border-color: #412c34;
}

body.dark-mode .secondary-button,
body.dark-mode .phrase-button {
    background: #241a1f;

    color: #ff9eb5;

    border-color: #633341;
}

body.dark-mode .listening-form-card input,
body.dark-mode .listening-form-card select,
body.dark-mode .listening-form-card textarea,
body.dark-mode .answer-button {
    background: #1a1417;

    color: white;

    border-color: #49333b;
}

body.dark-mode .privacy-note,
body.dark-mode .support-response,
body.dark-mode .academic-note,
body.dark-mode .motivational-section {
    background: #2b1d23;

    color: #e8cbd2;
}

body.dark-mode .reference-icon {
    background: #3a232c;
}


/* =========================================
   ALTO CONTRASTE
========================================= */

body.high-contrast {
    background: #000 !important;

    color: #fff !important;
}

body.high-contrast * {
    border-color: #fff !important;
}

body.high-contrast .header,
body.high-contrast .info-card,
body.high-contrast .quiz-card,
body.high-contrast .listening-form-card,
body.high-contrast .reference-card,
body.high-contrast .hero,
body.high-contrast .motivational-section {
    background: #000 !important;

    color: #fff !important;
}

body.high-contrast h1,
body.high-contrast h2,
body.high-contrast h3,
body.high-contrast p,
body.high-contrast span,
body.high-contrast a,
body.high-contrast label {
    color: #fff !important;
}

body.high-contrast .button,
body.high-contrast .card-icon {
    background: #ffff00 !important;

    color: #000 !important;
}

body.high-contrast .red-section {
    background: #000 !important;
}


/* =========================================
   RESPONSIVIDADE
========================================= */

@media (max-width: 950px) {

    .cards,
    .prejudice-grid {
        grid-template-columns:
            repeat(2, 1fr);
    }

    .hero-content {
        grid-template-columns: 1fr;

        text-align: center;

        padding: 70px 0;
    }

    .hero p,
    .hero h2 {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-buttons {
        justify-content: center;
    }

    .hero-character {
        margin-top: 20px;
    }

    .listening-container {
        grid-template-columns: 1fr;
    }

}


@media (max-width: 720px) {

    .accessibility-bar {
        justify-content: center;

        flex-wrap: wrap;
    }

    .menu-button {
        display: block;
    }

    .nav-links {
        display: none;

        position: absolute;

        top: 100%;

        left: 0;
        right: 0;

        background: var(--cream);

        flex-direction: column;

        align-items: stretch;

        padding: 15px 5%;

        border-bottom: 1px solid #ead9dd;
    }

    .nav-links.active {
        display: flex;
    }

    .nav-links a {
        display: block;
    }

    .hero {
        min-height: auto;
    }

    .hero h1 {
        font-size: 3.5rem;
    }

    .cards,
    .prejudice-grid {
        grid-template-columns: 1fr;
    }

    .section {
        padding: 70px 0;
    }

    .quote-box {
        flex-direction: column;

        text-align: center;
    }

    .quiz-card,
    .listening-form-card,
    .listening-message {
        padding: 25px;
    }

    .kushina-image {
        height: 400px;
    }

    .reference-card {
        flex-direction: column;
    }

}

/* =========================================
   MENU MOBILE
========================================= */

const menuButton = document.getElementById("menuButton");
const navLinks = document.getElementById("navLinks");

menuButton.addEventListener("click", () => {
    navLinks.classList.toggle("active");
});


/* Fecha o menu ao clicar em algum link */

document.querySelectorAll(".nav-links a").forEach(link => {

    link.addEventListener("click", () => {

        navLinks.classList.remove("active");

    });

});


/* =========================================
   MODO ESCURO
========================================= */

const darkModeButton =
    document.getElementById("darkModeButton");

darkModeButton.addEventListener("click", () => {

    document.body.classList.toggle("dark-mode");

    const ativado =
        document.body.classList.contains("dark-mode");

    darkModeButton.innerHTML = ativado
        ? '<i class="fa-solid fa-sun"></i> Modo claro'
        : '<i class="fa-solid fa-moon"></i> Modo escuro';

});


/* =========================================
   ALTO CONTRASTE
========================================= */

const contrastButton =
    document.getElementById("contrastButton");

contrastButton.addEventListener("click", () => {

    document.body.classList.toggle("high-contrast");

    const ativado =
        document.body.classList.contains("high-contrast");

    contrastButton.innerHTML = ativado
        ? '<i class="fa-solid fa-circle-half-stroke"></i> Contraste normal'
        : '<i class="fa-solid fa-circle-half-stroke"></i> Alto contraste';

});


/* =========================================
   AUMENTAR / DIMINUIR FONTE
========================================= */

const fontIncrease =
    document.getElementById("fontIncrease");

const fontDecrease =
    document.getElementById("fontDecrease");

let fontSize = 16;


fontIncrease.addEventListener("click", () => {

    if (fontSize < 21) {

        fontSize += 1;

        document.documentElement.style.setProperty(
            "--font-size",
            `${fontSize}px`
        );

    }

});


fontDecrease.addEventListener("click", () => {

    if (fontSize > 13) {

        fontSize -= 1;

        document.documentElement.style.setProperty(
            "--font-size",
            `${fontSize}px`
        );

    }

});


/* =========================================
   VOLTAR AO TOPO
========================================= */

const backToTop =
    document.getElementById("backToTop");

window.addEventListener("scroll", () => {

    if (window.scrollY > 500) {

        backToTop.classList.add("visible");

    } else {

        backToTop.classList.remove("visible");

    }

});


backToTop.addEventListener("click", () => {

    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });

});


/* =========================================
   PORTAL DE ESCUTA
========================================= */

const listeningForm =
    document.getElementById("listeningForm");

const supportResponse =
    document.getElementById("supportResponse");


listeningForm.addEventListener("submit", (event) => {

    event.preventDefault();

    const name =
        document.getElementById("name").value.trim();

    const feeling =
        document.getElementById("feeling").value;

    const message =
        document.getElementById("message").value.trim();


    if (!message) {

        supportResponse.style.display = "block";

        supportResponse.innerHTML = `
            <strong>
                🌺 Queremos ouvir você.
            </strong>
            <br>
            Escreva um pouco sobre o que está acontecendo.
        `;

        return;

    }


    const nomeFinal =
        name || "amigo(a)";


    let mensagemExtra = "";

    if (feeling) {

        mensagemExtra =
            ` Percebemos que você está se sentindo ${feeling.toLowerCase()}.`;

    }


    supportResponse.style.display = "block";

    supportResponse.innerHTML = `
        <strong>
            🌺 Obrigado por confiar neste espaço, ${nomeFinal}!
        </strong>

        <br><br>

        Seu desabafo foi recebido apenas pelo seu navegador
        nesta simulação e <strong>não foi armazenado nem enviado</strong>.

        ${mensagemExtra}

        <br><br>

        Lembre-se: se algo estiver machucando você,
        procure um professor, pedagogo, direção, familiar
        ou outro adulto de confiança.

        <br><br>

        <strong>
            Você não precisa enfrentar uma situação difícil sozinho(a).
        </strong>
    `;


    listeningForm.reset();

});


/* =========================================
   FRASES MOTIVACIONAIS
========================================= */

const phrases = [

    "Você merece ser tratado com respeito.",

    "Ser diferente não significa ser menos.",

    "Sua voz importa e merece ser ouvida.",

    "Empatia começa quando decidimos ouvir.",

    "Respeitar o outro também é uma forma de coragem.",

    "Ninguém deve ser diminuído por ser quem é.",

    "Pequenas atitudes podem transformar o ambiente escolar.",

    "Você não está sozinho(a). Procure alguém em quem confia.",

    "Uma escola melhor começa com nossas atitudes.",

    "Diferenças tornam nossa comunidade mais rica."

];


const motivationalPhrase =
    document.getElementById("motivationalPhrase");

const newPhrase =
    document.getElementById("newPhrase");


newPhrase.addEventListener("click", () => {

    const randomIndex =
        Math.floor(Math.random() * phrases.length);

    motivationalPhrase.style.opacity = "0";


    setTimeout(() => {

        motivationalPhrase.textContent =
            `"${phrases[randomIndex]}"`;

        motivationalPhrase.style.opacity = "1";

    }, 200);

});


/* =========================================
   QUIZ
========================================= */

const questions = [

    {
        question:
            "Uma pessoa é constantemente ridicularizada pelos colegas por sua aparência. Isso pode ser considerado bullying?",

        answers: [
            "Sim, principalmente se as agressões forem repetidas e causarem sofrimento.",
            "Não, porque brincadeiras nunca podem machucar.",
            "Só se a pessoa rir junto.",
            "Não, porque aparência não tem relação com respeito."
        ],

        correct: 0
    },


    {
        question:
            "Qual atitude demonstra respeito às diferenças?",

        answers: [
            "Fazer piadas sobre alguém diferente.",
            "Ignorar a pessoa para evitar problemas.",
            "Ouvir, respeitar e tratar a pessoa com dignidade.",
            "Tentar convencer todos a serem iguais."
        ],

        correct: 2
    },


    {
        question:
            "Você presencia um colega sendo vítima de preconceito. Qual atitude é mais adequada?",

        answers: [
            "Fingir que não viu.",
            "Compartilhar o ocorrido nas redes sociais.",
            "Apoiar a pessoa e procurar um adulto de confiança.",
            "Fazer uma piada para mudar o assunto."
        ],

        correct: 2
    },


    {
        question:
            "Qual destas atitudes contribui para uma escola mais inclusiva?",

        answers: [
            "Excluir quem pensa diferente.",
            "Criar apelidos baseados em características pessoais.",
            "Valorizar diferentes culturas, histórias e identidades.",
            "Evitar conversar com pessoas diferentes."
        ],

        correct: 2
    },


    {
        question:
            "Se você estiver passando por uma situação de violência ou preconceito na escola, o que pode fazer?",

        answers: [
            "Guardar tudo em segredo.",
            "Procurar um professor, familiar ou outro adulto de confiança.",
            "Responder com outra agressão.",
            "Abandonar a escola imediatamente."
        ],

        correct: 1
    }

];


let currentQuestion = 0;
let score = 0;
let selectedAnswer = false;


const questionElement =
    document.getElementById("question");

const answersElement =
    document.getElementById("answers");

const nextQuestion =
    document.getElementById("nextQuestion");

const questionNumber =
    document.getElementById("questionNumber");

const progress =
    document.getElementById("progress");

const quizResult =
    document.getElementById("quizResult");

const quizContent =
    document.getElementById("quizContent");


function loadQuestion() {

    selectedAnswer = false;

    nextQuestion.disabled = true;

    const question =
        questions[currentQuestion];


    questionElement.textContent =
        question.question;


    questionNumber.textContent =
        `Pergunta ${currentQuestion + 1} de ${questions.length}`;


    progress.style.width =
        `${((currentQuestion + 1) / questions.length) * 100}%`;


    answersElement.innerHTML = "";


    question.answers.forEach((answer, index) => {

        const button =
            document.createElement("button");

        button.classList.add("answer-button");

        button.textContent =
            answer;

        button.addEventListener("click", () => {

            selectAnswer(button, index);

        });

        answersElement.appendChild(button);

    });

}


function selectAnswer(button, index) {

    if (selectedAnswer) {
        return;
    }

    selectedAnswer = true;

    const correct =
        questions[currentQuestion].correct;


    const allButtons =
        document.querySelectorAll(".answer-button");


    allButtons.forEach((btn, buttonIndex) => {

        btn.disabled = true;

        if (buttonIndex === correct) {

            btn.classList.add("correct");

        }

    });


    if (index === correct) {

        score++;

        button.innerHTML =
            `✓ ${button.textContent}`;

    } else {

        button.classList.add("wrong");

        button.innerHTML =
            `✕ ${button.textContent}`;

    }


    nextQuestion.disabled = false;

}


nextQuestion.addEventListener("click", () => {

    currentQuestion++;


    if (currentQuestion < questions.length) {

        loadQuestion();

    } else {

        showResult();

    }

});


function showResult() {

    quizContent.style.display = "none";

    nextQuestion.style.display = "none";

    document.querySelector(".quiz-progress").style.display =
        "none";


    quizResult.style.display = "block";


    let message = "";

    if (score === 5) {

        message =
            "Excelente! Você demonstrou muito conhecimento sobre respeito e inclusão. 🌺";

    } else if (score >= 3) {

        message =
            "Muito bem! Você já conhece atitudes importantes para combater o preconceito.";

    } else {

        message =
            "Continue aprendendo! Conhecimento e empatia ajudam a transformar o ambiente escolar.";

    }


    quizResult.innerHTML = `

        <div style="font-size: 3rem;">
            🌺
        </div>

        <h3>
            Você acertou ${score} de ${questions.length}!
        </h3>

        <p>
            ${message}
        </p>

        <br>

        <button
            class="button primary-button"
            onclick="restartQuiz()"
        >
            <i class="fa-solid fa-rotate-right"></i>
            Refazer quiz
        </button>

    `;

}


function restartQuiz() {

    currentQuestion = 0;

    score = 0;

    quizContent.style.display = "block";

    nextQuestion.style.display = "inline-flex";

    document.querySelector(".quiz-progress").style.display =
        "block";

    quizResult.style.display = "none";

    loadQuestion();

}


loadQuestion();