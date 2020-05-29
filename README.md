<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">

<script>
  <style>
   body,h1,h2{font-family: "Raleway", sans-serif}
   body, html {height: 100%}
   p {line-height: 2}
   .bgimg, .bgimg2 {
    min-height: 100%;
    background-position: center;
    background-size: cover;
  }
  .bgimg {background-image: url("images/fotoprincipal.jpeg")}
  .bgimg2 {background-image: url("images/fotonova.jpg")}

 </style>
 <body>
 <!-- Header / Home-->
 <header class="w3-display-container w3-wide bgimg w3-grayscale-min" id="home">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">Luiz Felippe é Anny Bianca</h1>
    <h2>Eternos Namorados</h2>
    <h2><b>19.06.2018</b></h2>
  </div>
 </header>

 <!-- Navbar (sticky bottom) -->
 <div class="w3-bottom w3-hide-small">
  <div class="w3-bar w3-white w3-center w3-padding w3-opacity-min w3-hover-opacity-off">
    <a href="#home" style="width:25%" class="w3-bar-item w3-button">Home</a>
    <a href="#us" style="width:25%" class="w3-bar-item w3-button">Luiz é Bia</a>
    <a href="#wedding" style="width:25%" class="w3-bar-item w3-button">Agora nessa nova fase da vida precisamos de</a>
    <a href="#rsvp" style="width:25%" class="w3-bar-item w3-button w3-hover-black">Finalzinho</a>
  </div>
 </div>

 <!-- About / Jane And John -->
 <div class="w3-container w3-padding-64 w3-pale-red w3-grayscale-min" id="us">
  <div class="w3-content">
    <h1 class="w3-center w3-text-grey"><b>Um pouco sobre nossa Historia</b></h1>
     <p>
      <i>Muita coisa aconteceu desde quando te conheci. O sentimento chamado 'amor' estava surgindo dentro de mim.. claro que de uma forma totalmente diferente, algo que nunca tinha acontecido.. e foi assim que comecei a ficar apaixonado por você. A primeira vez que eu te vi foi muito surreal é eu não imaginava que aquele sentimento que estava sentindo naquele momento iria me fazer estar aonde estou hoje. então te agradeço por tudo oque você fez e ainda faz por mim e pelo nosso relacionamento.</i>
     </p>
     <br>
    <p class="w3-center">
      <a href="#wedding" class="w3-button w3-black w3-round w3-padding-large w3-large">Clica aqui bb</a>
    </p>
   </div>
 </div>

 <!-- Background photo -->
 <div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo"> Saudades desse dia </h1>
    <h2>e de você tbm é claro</h2>
  </div>
 </div>

 <!-- Wedding information -->
 <div class="w3-container w3-padding-64 w3-pale-red w3-grayscale-min w3-center" id="wedding">
  <div class="w3-content">
    <h1 class="w3-text-grey"><b>Agora nessa nova fase da vida precisamos de:</b></h1>
    <div class="w3-row">
      <div class="w3-half">
        <h2>Primeira fase:</h2>
        <p>Confiar no outro idependente de qualquer circunstâncias.</p>
        <p>Não morrer com o coração a -1.000bpm por causa da ansiedade.</p>
      </div>
      <div class="w3-half">
        <h2>Segunda Fase:</h2>
        <p>Respeitar é sempre fazer de tudo pra apoiar e ajudar nas decisões que o outro fizer.</p>
        <p>Aconteça oque acontecer... cuidar um do outro até a morte.</p>
      </div>
    </div>
  </div>
 </div>

 <!-- RSVP section -->
 <div class="w3-container w3-padding-64 w3-pale-red w3-center w3-wide" id="rsvp">
  <h1>Claro que isso não e nada comparado ao meu amor infinito que tenho por você.. mas ta aqui uma demonstração de amor, carinho e afeto</h1>
  <p class="w3-large">Projeto terminado dia 27/02/2020 </p>
  <p class="w3-xlarge">
    <button onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-round w3-red w3-opacity w3-hover-opacity-off" style="padding:8px 60px">A.. e deixe aqui a sua opnião sobre essa coisa linda kk</button>
  </p>
 </div>
 <!-- RSVP modal -->
 <div id="id01" class="w3-modal">
  <div class="w3-modal-content w3-card-4 w3-animate-zoom" style="padding:32px;max-width:600px">
    <div class="w3-container w3-white w3-center">
      <h1 class="w3-wide">Eai?? gostou ?</h1>
      <p>Conta pra mim pelo whatts kk</p>
      <form>
        <input class="w3-input w3-border" type="text" placeholder="Deixa alguma coisa ai tbm kk" name="name">
      </form>
      <p><i>Do seu amor para Anny Bianca </i></p>
      <div class="w3-row">
        <div class="w3-half">
          <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-green">Curtiu </button>
        </div>
        <div class="w3-half">
          <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-red">Não curtiu</button>
        </div>
      </div>
    </div>
  </div>
 </div>
 </div>

 <!-- Footer -->
 <footer class="w3-center w3-black w3-padding-16">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">Luiz Felippe Silva Fagundes</a></p>
 </footer>
 div class="w3-hide-small" style="margin-bottom:32px"> </div>

 <script src="//www.google-analytics.com/analytics.js"></script>
 <script>
    !function(f,o,d,a,s,e){f.GoogleAnalyticsObject=d;f[d]||(f[d]=function(){
    (f[d].q=f[d].q||[]).push(arguments)});f[d].l=+new Date;s=o.createElement(a);
     e=o.getElementsByTagName(a)[0];s.src='//www.google-analytics.com/analytics.js';
    e.parentNode.insertBefore(s,e)}(window,document,'ga','script');

    ga('create', 'UA-36549695-14', 'auto');
    ga('send', 'pageview');
</script>
</body>
</html>

