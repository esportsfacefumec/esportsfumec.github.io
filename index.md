<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

body, html {
  height: 100%;
  line-height: 1.8;
  
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("BrainTeam.png");
  min-height: 50%;
}

.w3-bar .w3-button {
  padding: 16px;
}

.a {text-shadow:1px 1px;}

.mySlides {display:none}

</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    
	<img src="FUMEC-logo-small.png" style="height:60px;float: right;" alt="logo_fumec"> 
	<img src="FUMEC_E_Sports_LOGO.png" style="height:60px;float: left;" alt="logo_esportsfumec"> 
	
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">SOBRE</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> EQUIPE</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i> WORK</a>
      <!-- 
	  <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTATO</a>-->
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->

<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">SOBRE</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">EQUIPE</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTATO</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">Equipe Oficial de E-Sports da Universidade FUMEC</span><br>
    <span class="w3-large">\em busca dos msid altos padrões de competitividade nos E-Sports</span>
   <!-- <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Learn more and start today</a></p> -->
  </div> 
  <div class="w3-display-bottomleft w3-text-white w3-xxlarge" style="padding:24px 48px">
    
	<a href="https://www.youtube.com/@e-sportsfumec/featured" class="fa fa-youtube w3-hover-opacity"></a>
	<a href="https://www.youtube.com/@e-sportsfumec/featured" class="fa fa-facebook w3-hover-opacity"></a>
    <a href="https://www.instagram.com/esportsfacefumec" class="fa fa-instagram w3-hover-opacity"></a>
    <a href="https://twitter.com/esportsfumec" class="fa fa-twitch w3-hover-opacity"></a>
	
  </div>
</header>

<!-- About Section -->
<hr>
<div class="w3-container" style="padding:0px 16px" id="about">
  <h3 class="w3-center w3-light-grey">SOBRE A BRAIN TEAM</h3>
  <p class="w3-center w3-large">Principais características da nossa equipe</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-universal-access w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">Respeito</p>
      <p>Respeitamos nossos adversários e apoiamos todos os tipos de diversidades!</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-heart w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Paixão</p>
      <p>Amamos os esportes eletrônicos!</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-diamond w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Habilidade</p>
      <p>Estamos sempre evoluindo e estudando para atingir os mais altos padrões.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa  fa-graduation-cap w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Treinamento</p>
      <p>A Brain Team treina incansavelmente para vencer!</p>
    </div>
  </div>
</div>


<!--Videos section -->
<hr>
<div class="w3-container">
  <h2 class="w3-center w3-light-grey" >SHORTS do 1º Campeonato de League of Legends da FACE/FUMEC de 2023</h2>
  
</div>
	
		<div class="w3-content" style="max-width:80%">
		<center>
			<iframe width="560" height="315" class="mySlides" src="https://www.youtube.com/embed/Tm8s1afBqX8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share; allowfullscreen"></iframe> 
			<iframe width="560" height="315" class="mySlides" src="https://www.youtube.com/embed/q_rdyWPPNfw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share; allowfullscreen"></iframe>
			<iframe width="560" height="315" class="mySlides"src="https://www.youtube.com/embed/m2ddfxVL8jU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share; allowfullscreen"></iframe>
			<iframe width="560" height="315" class="mySlides" src="https://www.youtube.com/embed/rxyCWjLCEyE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
		</center>	
		</div>
	
<div class="w3-center">
  <div class="w3-section">
    <button class="w3-button w3-light-grey" onclick="plusDivs(-1)">❮ Prev</button>
    <button class="w3-button w3-light-grey" onclick="plusDivs(1)">Next ❯</button>
  </div>
  <button class="w3-button demo" onclick="currentDiv(1)">1</button> 
  <button class="w3-button demo" onclick="currentDiv(2)">2</button> 
  <button class="w3-button demo" onclick="currentDiv(3)">3</button> 
  <button class="w3-button demo" onclick="currentDiv(4)">4</button> 
</div>


<!-- Team Section -->
<div class="w3-container" style="padding:32px 16px;" id="team">
<hr>
  <h3 class="w3-center w3-light-grey" style="color:white">A EQUIPE DE E-ATLETAS</h3>
  <p class="w3-center w3-light-grey w3-large">Um por todos e todos por um!</p>
  <div class="w3-row-padding w3-black" style="margin-top:16px">
    
	<div class="w3-col m4 w3-center">
      <div class="w3-card">
        <img src="/w3images/team1.jpg" alt="Marcos" >
        <div class="w3-container w3-border w3-padding  m4 l3">
          <h3>Daniel de Souza Filho, "Danas"</h3>
          <p class="w3-opacity">Capitão da Equipe e ADC matador!</p>
          <p>Aluno do Curso de Computação Gráfica, lidera a equipe em ação! Campeão do "1ºCampeonato de League of Legends da FACE/FUMEC 2023"</p>
		  <font face = "Arial" size = "8" color = "red">Active</font><br />
          <img src="LOL-RANKED.png" alt="Marcos" style="width:20%">
		  <a href="https://www.op.gg/summoners/br/Danas" class="w3-button w3-light-grey w3-hover-red w3-block" target="_blank" title="Go to OP.GG" >Stats no OP.GG</a>  
		  </div>
      </div>
    </div>
	<div class="w3-col m4 w3-center">
      <div class="w3-card">
        <img src="/w3images/team3.jpg" alt="Mike" >
        <div class="w3-container w3-border w3-padding  m4 l3">
          <h3>André Barroso Rocha, "Ice Tea"</h3>
          <p class="w3-opacity">Top Laner sem coração!</p>
          <p>Aluno do Curso de Ciência da Computação. Duro feito pedra!</p>
		   <font face = "octin spraypaint a rg"  src="url(octin spraypaint a rg.otf)" size = "8" color = "red">MIA- Missing in Action</font><br />
          <img src="LOL-RANKED.png" alt="Marcos" style="width:20%">
		  <a href="https://www.op.gg/summoners/br/Ice Tea" class="w3-button w3-light-grey w3-hover-red w3-block" target="_blank" title="Go to OP.GG">Stats no OP.GG</a>  
		  </div>
        </div>
      </div>
    <div class="w3-col m4 w3-center">
      <div class="w3-card">
        <img src="/w3images/team4.jpg" alt="Dan" >
        <div class="w3-container w3-border w3-padding  m4 l3">
          <h3>RAFAEL COLEPÍCOLO GAMA, "Huy"</h3>
          <p class="w3-opacity">Mid Lane pulverizer!</p>
          <p>Aluno da Ciência da Computação. Aparece quando menos se espera!</p>
		  <font face = "Arial" size = "8" color = "red">Active</font><br />
          <img src="LOL-RANKED.png" alt="Marcos" style="width:20%">
		  <a href="https://www.op.gg/summoners/br/huy" class="w3-button w3-light-grey w3-hover-red w3-block" target="_blank" title="Go to OP.GG">Stats no OP.GG</a>  
		  </div>
        </div>
      </div>
    <div class="w3-col m4 w3-center">
      <div class="w3-card">
        <img src="/w3images/team4.jpg" alt="Dan">
        <div class="w3-container w3-border w3-padding  m4 l3">
          <h3>ERICK ELOY DOS SANTOS CRUZ, "Chrollo"</h3>
          <p class="w3-opacity">Jungler destruído!</p>
          <p>Aluno da Ciência da Computação. Os creeps fogem quando ele chega!</p>   
			<font face = "Arial" size = "8" color = "red">Active</font><br />		  
		 <img src="LOL-RANKED.png" alt="Marcos"  style="width:20%" >
		  <a href="https://www.op.gg/summoners/br/Chrollo" class="w3-button w3-light-grey w3-hover-red w3-block" target="_blank" title="Go to OP.GG">Stats no OP.GG</a>  
        </div>
      </div>
    </div>
	<div class="w3-col m4 w3-center">
      <div class="w3-card">
        <img src="/w3images/team4.jpg" alt="Dan" >
        <div class="w3-container w3-border w3-padding  m4 l3">
          <h3>JÚLIO NATAN COUTO NOGUEIRA, "Banana Segredin"</h3>
          <p class="w3-opacity">Suporte salvador!</p>
          <p>Aluno de Jogos Digitais. Mantêm a moral da equipe! Campeão do "1ºCampeonato de League of Legends da FACE/FUMEC 2023"</p>
			<font face = "Arial" size = "8" color = "red">Active</font><br />
          <img src="LOL-RANKED.png" alt="Marcos" style="width:20%">
		  <a href="https://www.op.gg/summoners/br/Danas" class="w3-button w3-light-grey w3-hover-red w3-block" target="_blank" title="Go to OP.GG">Stats no OP.GG</a>  
		  </div>
        </div>
      </div>
    </div>
	
	</div>
  </div>
</div>

<!-- Coordination Section -->
<div class="w3-container" style="padding:32px 16px" id="team">
  <h3 class="w3-center w3-border w3-padding">COORDENAÇÃO GERAL</h3>
  <p class="w3-center w3-large">Trabalhamos para formar uma equipe vencedora!</p>
	<div class="w3-container" style="padding:16px 16px" id="team">
	  <div class="w3-row-padding w3-grayscale" style="margin-top:32px">
		<div class="w3-col w3-container w3-border w3-padding m4 l3">
			<div class="w3-card">
			<img src="ProfaRenata.jpg" alt="Renata" style="width:64px">
				<div class="w3-container">
				<h3>Profa.Dra. Renata de Sousa da Silva Tolentino</h3>
				  <p class="w3-opacity">Diretora da Faculdade de Ciências Empresarias (2020- 2023) e Coordenadora Geral do E-Sports</p>
				  <p>Doutora em Administração, Conselheira Executiva da FUMEC, Diretora, Pesquisadora e Professora</p>
				  <p><button class="w3-button w3-light-grey w3-hover-red w3-block" href="https://www.op.gg/summoners/br/Danas"><i class="fa fa-envelope"></i> Contato</button></p>
				</div>
			</div>
		</div>
			<div class="w3-col w3-container w3-border w3-padding m4 l3">
			  <div class="w3-card">
				<img src="ProfMarcos.jpg" alt="Marcos" style="width:64px">
				<div class="w3-container">
				 <h3>Prof.Dr. Marcos André Penna Coutinho</h3>
					<p class="w3-opacity">Coordenador do E-Sports</p>
					<p>Professor nos cursos de Tecnólogo em Jogos Digitais, Graduação em Game Design e Graduação em Computação Gráfica.</p>
					<p><button class="w3-button w3-light-grey w3-hover-red w3-block"><i class="fa fa-envelope"></i> Contato</button></p>
				</div>
			  </div>
			</div>
			<div class="w3-col w3-container w3-border w3-padding m4 l3 ">
			  <div class="w3-card">
				<img src="ProfMarcos.jpg" alt="Marcos" style="width:64px">
				<div class="w3-container">
				 <h3>Prof.Dr. Air Rabelo</h3>
					<p class="w3-opacity">Coordenador dos cursos Bacharelado em Ciência da Computação e Tecnológico em Gestão da Tecnologia da Informação</p>
					<p>Professor Titular dos cursos Bacharelado em Ciência da Computação e Tecnológico em Gestão da Tecnologia da Informação</p>
					<p><button class="w3-button w3-light-grey  w3-hover-red w3-block"><i class="fa fa-envelope"></i> Contato</button></p>
				</div>
			  </div>
			</div>
			<div class="w3-col w3-container w3-border w3-padding m4 l3">
			  <div class="w3-card">
				<img src="ProfMarcos.jpg" alt="Marcos" style="width:64px">
				<div class="w3-container">
				 <h3>Prof. Me. Becsom Salles de Carvalho</h3>
					<p class="w3-opacity">Coordenador dos Cursos de Ciência da Computação e Gestão da Tecnologia da Informação (TGTI)</p>
					<p>Professor titular dos Cursos de Ciência da Computação e Gestão da Tecnologia da Informação (TGTI)</p>
					<p><button class="w3-button w3-light-grey w3-hover-red  w3-block"><i class="fa fa-envelope"></i> Contato</button></p>
				</div>
			  </div>
			</div>
		</div>		
	</div>
	  
</div>

<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">325/245</span>
    <br>Kills/Dies
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">55.000</span>
    <br>Média de Dano por Partida
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">2</span>
    <br>1º Colocação em Campeonatos
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">154/32</span>
    <br>Wins/Loose
  </div>
</div>

<!-- Work Section -->
<!--
<div class="w3-container" style="padding:128px 16px" id="work">
  <h3 class="w3-center">OUR WORK</h3>
  <p class="w3-center w3-large">What we've done for people</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_mic.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A microphone">
    </div>
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_phone.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A phone">
    </div>
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_drone.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A drone">
    </div>
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_sound.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Soundbox">
    </div>
  </div>

  <div class="w3-row-padding w3-section">
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_tablet.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A tablet">
    </div>
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_camera.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A camera">
    </div>
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_typewriter.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A typewriter">
    </div>
    <div class="w3-col l3 m6">
      <img src="/w3images/tech_tableturner.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A tableturner">
    </div>
  </div>
</div>
-->
<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Skills Section -->
<div class="w3-container w3-light-grey w3-padding-64">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Nossas habilidades</h3>
      <p>Podcasts com dicas de jogadas brutais!<br>
      Streaming de partidas todas as semanas...</p>
      <p>Estamos presentes, prontos e atuantes.</p>
    </div>
    <div class="w3-col m6">
      <p class="w3-wide"><i class="fa fa-camera w3-margin-right"></i>Eficiência</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:90%">90%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>Streamings</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:85%">85%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-photo w3-margin-right"></i>Campeonatos</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:75%">75%</div>
      </div>
    </div>
  </div>
</div>

<!-- Pricing Section -->
<!--
<div class="w3-container w3-center w3-dark-grey" style="padding:128px 16px" id="pricing">
  <h3>PRICING</h3>
  <p class="w3-large">Choose a pricing plan that fits your needs.</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Basic</li>
        <li class="w3-padding-16"><b>10GB</b> Storage</li>
        <li class="w3-padding-16"><b>10</b> Emails</li>
        <li class="w3-padding-16"><b>10</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">$ 10</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large">Sign Up</button>
        </li>
      </ul>
    </div>
    <div class="w3-third">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-red w3-xlarge w3-padding-48">Pro</li>
        <li class="w3-padding-16"><b>25GB</b> Storage</li>
        <li class="w3-padding-16"><b>25</b> Emails</li>
        <li class="w3-padding-16"><b>25</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">$ 25</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large">Sign Up</button>
        </li>
      </ul>
    </div>
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Premium</li>
        <li class="w3-padding-16"><b>50GB</b> Storage</li>
        <li class="w3-padding-16"><b>50</b> Emails</li>
        <li class="w3-padding-16"><b>50</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">$ 50</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large">Sign Up</button>
        </li>
      </ul>
    </div>
  </div>
</div>
-->
<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center w3-black">CONTATO</h3>
  <p class="w3-center w3-large">Quer conversar conosco? Mande uma mensagem:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Belo Horizonte, Minas Gerais, Brasil</p>
    <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Cel: 55 31 </p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: esportsfacefumec@gmail.com</p>
    <br>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-black" type="submit">
          <i class="fa fa-paper-plane"></i> MANDAR MESSAGEM
        </button>
      </p>
    </form>
	<form action="mailto:esportsfacefumec@gmail.com" method="post" enctype="text/plain">
		Name:<br>
		<input type="text" name="name"><br>
		E-mail:<br>
		<input type="text" name="mail"><br>
		Comment:<br>
		<input type="text" name="comment" size="50"><br><br>
		<input type="submit" value="Send">
		<input type="reset" value="Reset">
	</form>
	
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">

	<p>Campus Cruzeiro (FACE, FCH, FEA e Pós-graduação)	Rua Cobre, 200, bairro Cruzeiro -> Ônibus: 104 1170 2152 4103 4108 5101 </p>
	<a href="#home" class="w3-bar-item w3-button w3-wide">Central de Atendimento FUMEC: 0800 0300 200 (atendimento de segunda a sexta-feira, das 9h às 19h)</a>
    
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>Voltar ao topo</a>
  <div class="w3-xxlarge w3-section">
    
	<a href="https://www.youtube.com/@e-sportsfumec/featured" class="fa fa-youtube w3-hover-opacity"></a>
	<a href="https://www.youtube.com/@e-sportsfumec/featured" class="fa fa-facebook w3-hover-opacity"></a>
    <a href="https://www.instagram.com/esportsfacefumec" class="fa fa-instagram w3-hover-opacity"></a>
    <a href="https://twitter.com/esportsfumec" class="fa fa-twitch w3-hover-opacity"></a>
	
  </div>
  <p>Criado por Prof.Dr.Marcos André Penna Coutinho para a FACE/FUMEC (2023)</p>
</footer>
 
<script>

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}

//slider
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function currentDiv(n) {
  showDivs(slideIndex = n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" w3-red", "");
  }
  x[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " w3-red";
}
//google maps

</script>

</body>
</html>
