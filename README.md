<!--DOCTYPE html-->
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Perfil do Espectro</title>
  <style>
   body {
    min-height: 100%;
    margin: 0;
    padding: 0;
    font-size: 15px;
    background-color: #FFFFFF;
    color: #000000;
    font-family: sans-serif;
}
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #FFFFFF;
  padding: 10px;
}
button {
  border: none;
  background-color: #000000;
}
li {
  font-size: 18px;
  margin: 1px 1px 15px 1px;
}

main {
display: flex;
flex-direction: row;
gap: 20px;
margin: 0;
padding: 40px 20px 150px 20px;
}
h1 {
    font-size: 36px;
    color: #000000;
    font-family: Georgia, 'Times New Roman', Times, serif;
    text-align: left;
}
h2 {
  font-size: 31px;
  color: #000000;
  font-family: Arial, Helvetica, sans-serif;
  text-align: left;
}
p {
  font-size: 18px;
  color: #000000;
  font-weight: 100;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  text-align: justify;
}
footer {
margin: 0;
padding: 80px 20px 20px 20px;
color: #FFFFFF;
background-color: #424244;
text-align: center;
}


#logflux {
  width: 40px;
  height: 40px;
  padding: 0;
  border: 1px solid #FFFFFF;
  border-radius: 30%;
}
#lista {
  margin: 70px 0 0 0;
  padding: 0;
  list-style-type: none;
  text-align: center;
}
#meio{
  color: #000000;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
#Imaesp {
  width: 300px;
  height: 300px;
  text-align: center;
  margin: 0;
  border:1px solid #FFFFFF;
  border-radius: 50%;
}
#tridente {
  width: 30px;
  height: 30px;
  padding: 1px 10px 1px 1px;
  margin: 0;
}
#polvo {
width: 30px;
height: 30px;
padding: 1px 10px 1px 1px;
margin: 0;
}
#agradecimento {
  font-size: 14px;
  color: #FFFFFF;
  text-align: center;
  padding: 0;
  margin: 1px 1px 50px 1px;
}
#entre {
  margin: 0;
  padding: 0;
  list-style-type: none;
  text-align: center;
}
#direitos {
  font-size: 10px;
  color: #FFFFFF;
  text-align: center;
  font-family: Monospace;
}


.nav-links {
  display: none;
  gap: 20px;
} 
.close {
  margin: 0;
  padding: 0;
  text-align: right;
  cursor: pointer;
  }
.fenu div {
width: 35px;
height: 3px;
background-color: #FFFFFF;
margin: 5px;
}
.fechar:nth-child(1) {
  transform: rotate(45deg) translate(6px, 6px);
}
.fechar:nth-child(2) {
  transform: rotate(-45deg);
}
.top {
  color: #FFFFFF;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  text-decoration: none;
}
.burger {
  display: block;
}
.burger div {
  width: 25px;
  height: 3px;
  background-color: #333;
  margin: 5px;
}
.Omega {
  padding: 0;
  margin: 1px 1px 80px 1px
}
.sou {
  padding: 0;
  margin: 40px 1px 80px 1px;
}
.lose {
  font-size: 10px;
  color: #FFFFFF;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}


.overlay.active {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #00000080; /* Cor preta com 50% de opacidade */
  z-index: 10;
  display: block;
}
  .logo.active {
    display: none;
  }
 .nav-links.active {
  display: flex;
  flex-direction: column;
  position: fixed;
  top: 0;
  left: 0;
  width: 60%;
  height: 100vh;
  box-shadow: 5px 3px 5px #464646;
  background-color: #000000;
  transition: left 0.3s ease-in-out;
  z-index: 999;
}  
.burger.active  {
  display: none;
}


/* Estilos para telas menores */
@media (max-width: 768px) {
  .nav-links {
  display: none;
  }
  main {
  padding: 40px 20px 40px 20px;
  flex-direction: column;
  }
}
  </style>
</head>

<body>
  <header>
   <nav>
    <div class="logo">
      <div class="overlay"></div>
      <img id="logflux" src="playlistCropperBoomPlayer.jpg" alt="Zônflux">
    </div>
    <div class="nav-links">
      <div class="close">
        <button class="fenu">
          <div class="fechar"></div>
          <div class="fechar"></div>
        </button>
      </div>
      <ul id="lista">
        <li><a class="top" href="#">Pág 1</a></li>
        <li><a class="top" href="#">Pág 2</a></li>
        <li><a class="top" href="#">Pág 3</a></li>
      </ul>
    </div>
    <div class="burger">
      <div class="line"></div>
      <div class="line"></div>
      <div class="line"></div>
    </div>
  </nav>
  </header>
  
  <main>
  <section>
    <div class="Omega">
      <h1>Perfil</h1>
      <p>Espectro: O Herói de Aço e Guardião de Telethra</p>
    </div>
    
    <h2>Sobre Esprctro</h2>

    <p>Espectro é um robô lendário, criado ao lado de seu irmão X-Tron através de uma pedra mistica chamada (Emu) com o propósito nobre de proteger os habitantes de Telethra. Juntos, eles representavam o auge da tecnologia e da esperança. No entanto, o conceito de proteção de X-Tron foi distorcido, transformando-o em uma ameaça catastrófica que colocaria todo o universo à beira do caos. <br /><br />Para salvar Telethra, Espectro foi forçado a tomar a decisão mais difícil de sua existência: confrontar e destruir seu próprio irmão. O ato o consagrou como um herói, mas também deixou uma marca indelével em sua essência. Mal sabia Espectro que essa batalha era apenas o prelúdio de desafios ainda maiores, e que o destino de Telethra continuaria a depender de sua força e sacrifício.</p>
    <a id="meio" href="#">Everso</a>
  </section>
  <section>
    <img id="Imaesp" src="3e9cc9b4-9f78-4884-ba76-288df1fa6a23.jpeg" alt="Espectro">
  </section>
  <section>
    <h2>Detalhes</h2>
    <p>
      <b>Nome:</b><br />
        Espectro <br /><br />
      <b>Habilidade:</b><br />
        Intangibilidade<br /><br />
      <b>Localização</b><br />
        Telethra 
    </p>
    <div class="sou">
      <a href="#">
        <img id="tridente" src="Blooming Trident, Serhii Tsymbal.jpeg" alt="ícone de X-tron">
      </a>
      <a href="#">
        <img id="polvo" src="Aquatic Silhouette PNG Images, Octopus Logo Abstract Aggressive Aquatic, Insignia, Mascot, Creature PNG Image For Free Download.jpeg" alt="ícone do Scott">
      </a>
    </div>
  </section>
  </main>
  <footer>
    <p id="agradecimento">A você, visitante, nosso mais sincero agradecimento por embarcar nesta jornada fascinante sobre o Espectro. Sua curiosidade e dedicação nos motivam a continuar explorando os mistérios deste universo tão único. Esperamos que cada secção lida tenha despertado sua imaginação e lhe oferecido momentos de reflexão e inspiração.</p>
    <ul id="entre">
      <li><a class="lose" href="#">Telethra</a></li>
      <li><a class="lose" href="#">Emu</a></li>
    </ul>
    <p id="direitos">© 2025 Universo Zônflux. Todos os direitos reservados.</p>
    <script>
     const burger = document.querySelector('.burger');
const navLinks = document.querySelector('.nav-links');
const closeButton = document.querySelector('.close');
const overlay = document.querySelector('.overlay');
const body = document.body;


burger.addEventListener('click', () => {
  navLinks.classList.toggle('active');
  burger.classList.toggle('active');
  overlay.classList.toggle('active');
  closeButton.classList.toggle('active');
});

closeButton.addEventListener('click', () => {
  navLinks.classList.remove('active');
  burger.classList.remove('active');
  overlay.classList.remove('active');
});

body.addEventListener('click', (event) => {
  if (!event.target.closest('.nav-links') && !event.target.closest('.burger')) {
      navLinks.classList.remove('active');
      burger.classList.remove('active');
      overlay.classList.remove('active');
  }
});
    </script>
  </footer>
</body>
</html>
