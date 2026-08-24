:root {
    --red: #b91c3c;
    --dark-red: #74152b;
    --light-red: #e94d6d;
    --pink: #f48fb1;
    --soft-pink: #ffe0e9; /* Rosa suave atualizado */
    --orange: #f28c28;
    --purple: #8e5aa8;

    --cream: #fff0f5; /* Fundo principal em tom rosa claro (LavenderBlush) */
    --white: #ffffff;
    --black: #211b1d;
    --gray: #686063;
    --light-gray: #fce4ec;

    --shadow: 0 15px 45px rgba(96, 24, 45, 0.13);
    --radius: 24px;
    --font-size: 16px;
}

body {
    font-family: "Segoe UI", Arial, sans-serif;
    color: var(--black);
    background: var(--cream); /* Aplicação do tom rosa claro */
    line-height: 1.7;
    overflow-x: hidden;
    transition: background 0.3s ease, color 0.3s ease;
}

/* Fundo do Hero atualizado para degradê em tons de rosa */
.hero {
    min-height: 720px;
    position: relative;
    overflow: hidden;
    background: radial-gradient(
        circle at 85% 20%,
        rgba(244, 143, 177, 0.4),
        transparent 30%
    ),
    linear-gradient(
        135deg,
        #fff0f5 0%,
        #fce4ec 50%,
        #f8bbd0 100%
    );
    display: flex;
    align-items: center;
}<div class="hero-character">
    <div class="flower-circle">
        <img src="https://encrypted-tbn2.gstatic.com/licensed-image?q=tbn:ANd9GcS0c1WCB8wVQ3a5TX5tQVlttXOOPO4IYUK09wN2vA_XF5W-LfbtA1FnOknAX2FoJp3p6tiAv80gyKR9ZZE" alt="Flores de cerejeira" class="flower-icon-img" style="width: 40px; height: auto;">
    </div>

    <div class="character-card">
        <div class="character-glow"></div>

        <!-- Imagem principal da Kushina Uzumaki -->
        <img
            src="https://encrypted-tbn3.gstatic.com/licensed-image?q=tbn:ANd9GcTHKrNjHnm2xufdIY34UCRFKv1CLvtPKJuy-nXbTfcM8WwlKDozwWXff-wRAU0QbOtkE9jJYT6WXtYhriQ"
            alt="Kushina Uzumaki sorrindo"
            class="kushina-image"
        >

        <div class="character-caption">
            <strong>Kushina Uzumaki</strong>
            <span>Representação de força, carinho e proteção</span>
        </div>
    </div>
</div>