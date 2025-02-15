<!--DOCTYPE html-->
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil do Espectro</title>
    <style>
      /* Estilos Gerais */
body {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    margin: 0;
    padding: 0;
    background: #FFFFFF;
    color: #333;
}

/* Cabeçalho */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #004080;
    width: 100%;
    margin: 0px;
    padding: 0px;
    color: white;
}

.logo {
    width: 40px;
    height: 40px;
    padding: 0;
    border: 1px solid #FFFFFF;
    border-radius: 30%;
}

.menu-icon {
    font-size: 30px;
    cursor: pointer;
}

/* Barra de Menu */
.menu {
    position: fixed;
    top: 0;
    left: -60%;
    width: 60%;
    height: 100%;
    background: #000000CC;
    padding-top: 50px;
    transition: 0.3s;
}

.menu ul {
    list-style: none;
    padding: 0;
}

.menu li {
    padding: 15px;
    text-align: center;
}

.menu a {
    text-decoration: none;
    color: #FFFFFF;
    font-size: 18px;
}

/* Corpo Principal */
main {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    margin: 0px;
    padding: 0px;
}

h1, h2, h3 {
  font-family: Georgia, 'Times New Roman', Times, serif;
}

.descricao {
  text-align: justify;
}

.detalhes {
  text-align: left;
}

section {
    width: 100%;
    margin: 0px;
    padding: 0px;
    background: #FFFFFF;
    text-align: center;
}

.imagem img {
    width: 300px;
    height: 300px;
    border-radius: 50%;
}

.icons img {
    width: 30px;
    height: 30px;
    margin: 5px;
}

/* Rodapé */
footer {
    font-family: monospace;
    font-size: 10px;
    text-align: center;
    background: #333;
    width: 100%;
    color: #FFFFFF;
    margin: 0px;
    padding: 0px;
}

.perna ul {
  list-style: none;
  padding: 0;
}

.perna li {
  padding: 15px;
  text-align: center;
}

.perna a {
  color: #FFFFFF;
  font-size: 16px;
}

/* Responsividade */
@media (min-width: 768px) {
    main {
        flex-direction: row;
        justify-content: space-around;
    }

    .menu {
        width: 30%;
        left: -30%;
    }
}
    </style>
</head>
<body onclick="closeMenu()">
    <!-- Barra de Menu -->
    <nav id="menu" class="menu">
        <ul>
            <li><a href="#">Pág 1</a></li>
            <li><a href="#">Pág 2</a></li>
            <li><a href="#">Pág 3</a></li>
        </ul>
    </nav>

    <!-- Cabeçalho -->
    <header>
        <div>
          <img class="logo" src="playlistCropperBoomPlayer.jpg">
        </div>
        <div class="menu-icon" onclick="toggleMenu()">☰</div>
    </header>

    <!-- Corpo Principal -->
    <main>
        <!-- Primeira Seção -->
        <section class="descricao">
            <h1>Perfil</h1>
            <p>Espectro: O Herói de Aço e Guardião de Telethra</p>
            <h2>Sobre o Espectro</h2>
            <p>Espectro é um robô lendário, criado ao lado de seu irmão X-Tron com o propósito nobre de proteger os habitantes de Telethra. Juntos, eles representavam o auge da tecnologia e da esperança. No entanto, o conceito de proteção de X-Tron foi distorcido, transformando-o em uma ameaça catastrófica que colocaria todo o universo à beira do caos.<br /><br />Para salvar Telethra, Espectro foi forçado a tomar a decisão mais difícil de sua existência: confrontar e destruir seu próprio irmão. O ato o consagrou como um herói, mas também deixou uma marca indelével em sua essência. Mal sabia Espectro que essa batalha era apenas o prelúdio de desafios ainda maiores, e que o destino de Telethra continuaria a depender de sua força e sacrifício.</p>
        </section>

        <!-- Segunda Seção -->
        <section class="imagem">
            <img src="3e9cc9b4-9f78-4884-ba76-288df1fa6a23.jpeg" alt="Imagem do Espectro">
            <a href="https://zonflux070.github.io/Perfil-do-Espectro/">Everso</a>
        </section>

        <!-- Terceira Seção -->
        <section class="detalhes">
            <h3>Detalhes</h3>
            <p><strong>Nome:</strong><br /> Espectro</p><br />
            <p><strong>Habilidade:<br /></strong> Inatingibilidade</p><br />
            <p><strong>Localização:<br /></strong> Telethra</p>
            <div class="icons">
                <a href="#"><img src="Blooming Trident, Serhii Tsymbal.jpeg" alt="Ícone 1"></a>
                <a href="https://zonflux070.github.io/Mikasa-mi-Nzolu-/"><img src="Aquatic Silhouette PNG Images, Octopus Logo Abstract Aggressive Aquatic, Insignia, Mascot, Creature PNG Image For Free Download.jpeg" alt="Ícone 2"></a>
            </div>
        </section>
    </main>

    <!-- Rodapé -->
    <footer>
        <p>A você, visitante, nosso mais sincero agradecimento por embarcar nesta jornada fascinante sobre o Espectro. Sua curiosidade e dedicação nos motivam a continuar explorando os mistérios deste universo tão único. Esperamos que cada secção lida tenha despertado sua imaginação e lhe oferecido momentos de reflexão e inspiração.</p>
        <nav class="perna">
        <ul>
          <li><a href="https://zonflux070.github.io/Telethra/">Telethra</a></li>
          <li><a href="https://zonflux070.github.io/Emu/">Emu</a></li>
        </ul>
        </nav>
        <p>© 2025 Universo Zônflux. Todos os direitos reservados.</p>
    </footer>
    <script>
    /* function toggleMenu() {
    const menu = document.getElementById('menu');
    if (menu.style.left === "0px") {
        menu.style.left = "-60%";
    } else {
        menu.style.left = "0px";
    }
}*/
function toggleMenu() {
    const menu = document.getElementById('menu');
    if (menu.style.left === "0px") {
        menu.style.left = "-60%";
        document.removeEventListener("click", closeMenuOnClickOutside);
    } else {
        menu.style.left = "0px";
        setTimeout(() => {
            document.addEventListener("click", closeMenuOnClickOutside);
        }, 100);
    }
}

function closeMenuOnClickOutside(event) {
    const menu = document.getElementById('menu');
    const menuIcon = document.querySelector(".menu-icon");

    if (!menu.contains(event.target) && !menuIcon.contains(event.target)) {
        menu.style.left = "-60%";
        document.removeEventListener("click", closeMenuOnClickOutside);
    }
}
    </script>
</body>
</html>
