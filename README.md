# Projeto-Web-Site-Série2

<!DOCTYPE html>

<html lang="pt-br">
<head>
	<meta charset="UTF-8"/>
	<title>SUPERNATURAL</title>
	<style>
		@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:wght@200&display=swap');
		@font-face {
			font-family: 'fonte-logo';
			scr: url("_projeto/bubblegum-sans-regular");
		}
		h1 {
			font-family: Arial;
			font-size: 30pt;
			color: blue;
			text-shadow: 2px 2px 2px black;
		}
		h2 {
			font-family: Arial;
			font-size: 20pt;
			color: black;
		}
		h3 {
			font-family: Arial;
			font-size: 15pt;
			color: black;
		}
		p {
			text-align: justify;
			text-indent: 50px;
		}
		body {
			font-family: Aria, sans-serif;
			background-color: gray;
			color: rgba(0,0,0,1);
			padding: 130px;
			margin: 150px;
			width: -50px;
		}
		div#interface {
			background-color: whitesmoke;
			margin: -310px -310px -333px -253px;
			padding: 10px;
			bottom: -1075px;
			width: 1200px;
			left: 315px;
			position: absolute;
			box-shadow: 0px 0px 10px black;
			border-radius: 10px;
		}
		header#cabecalho img#icone {
			width: 90px;
			top: -58px;
			left: 1105px;
			border-radius: 10px;
			position: relative;
		}
		header#cabecalho {
			border-bottom: 1px black solid;
			height: 185px;
			margin: auto auto -1px;
			background: url("_imagens2/logo-supernatural.PNG") no-repeat -13px -20px;
		}
		header#cabecalho h1 {
			font-family: 'fonte-logo', sans-serif;
			font-size: 30pt;
			color: red;
			text-shadow: 2px 2px 2px rgba(0,0,0,.6);
			padding: 0px;
			margin-top: 10px;
			margin-bottom: 10px;
		}
		header#cabecalho h2 {
			font-family: 'Titillium Web', sans-serif;
			font-size: 20pt;
			color: gray;
			padding: 0px;
			margin-top: -10px;
			margin-bottom: 10px;
		}
		table#tabelaspec td.ce {
			background-color: rgba(0, 0, 0, .7);
			color: white;
		}
		table#tabelaspec td.cd {
			background-color: rgba(0, 0, 0, .4);
			color: black;
		}
		table#tabelaspec caption {
			color: rgba(0, 0, 0, .8);
			font-size: 13pt;
			font-weight: bolder;
		}
		table#tabelaspec {
			border: 1px solid black;
			border-spacing: 0px;
			margin-left: auto;
			margin-right: auto;
		}
		table#tabelaspec td {
			border: 1px solid black;
			padding: 10px;
			text-align: center;
		}
		table#tabelaspec caption span {
			display: block;
			float: right;
			color: black;
			font-size: 8pt;
			margin-top: 10px;
		}
		figure.fonte {
			position: relative;
			border: 4px solid white;
			box-shadow: 1px 1px 4px black;
			border-radius: 10px;
		}
		figure.fonte img {
			width: 100%;
			height: 100%;
		}
		figure.fonte figcaption {
			opacity: 0;
			position: absolute;
			top: 0;
			background-color: white;
			color: black;
			box-sizing: border-box;
			padding: 10px;
			width: 100%;
			height: 100%;
			transition: 1s;
		}
		figure.fonte figcaption:hover {
			opacity: 1;
		}
		nav#menu ol {
			list-style: none;
			text-transform: uppercase;
			position: absolute;
			margin: -2px;
			top: 5px;
			left: 550px;
		}
		nav#menu li {
			display: inline-block;
			background-color: gray;
			padding: 10px;
			margin: 2px;
			border-radius: 10px;
		}
		nav#menu li:hover {
			background-color: #606060;
		}
		nav#menu {
			display: block;
		}
		nav#menu h2 {
			display: none;
		}
		nav#menu a { 
		color: black; 
		text-decoration: none;
		}
		nav#menu a:hover {
			color: white;
		}
		section#corpo {
			display: block;
			width: 580px;
			float: left;
			border-right: 1px solid black;
			padding-right: 15px;
		}
		article#noticia-principal h2 {
			font-size: 12pt;
			color: white;
			background-color: gray;
			padding: 10px 10px 10px 10px;
			margin: 10px 0px 10px 0px;
		}
		header#cabecalho-artigo h2 {
			font-family: 'fonte-logo', sans-serif;
			font-size: 15pt;
			color: rgba(0, 0, 0, .8);
			background-color: white;
			margin-bottom: -10px;
		}
		header#cabecalho-artigo h3 {
			font-size: 11pt;
			color: rgba(0, 0, 0, .8);
			margin: 10px;
		}
		.direita {
			text-align: right; 
		}
		a {
			text-decoration: none;
			color: rgba(0, 0, 0, .8);
		}
		a:hover {
			text-decoration: underline;
		}
		aside#lateral {
			background-color: darkgray;
			padding: 10px;
			display: block;
			width: 563px;
			float: right;
			margin: 10px 5px 0px;
			box-shadow: 2px 2px 2px rgba(0, 0, 0, .7);
		}
		aside#lateral h2 {
			font-family: 'fonte-logo' sans-serif;
			font-size: 12pt;
			color: white;
			background-color: gray;
			padding: 10px 10px 10px 10px;
			margin: 10px 10px -5px 15px;
		}
		footer#rodape {
			clear: both;
			border-top: 1px solid black;
		}
		footer#rodape p {
			text-align: center;
		}
	</style>
	<script>
		function mudaFoto (foto) {
			document.getElementById("icone").src = foto;
		}
	</script>
</head>	
<body>
	<hgroup>
		<div id="interface">
			<header id="cabecalho">
				<h1>Supernatural</h1>
				<h2>Série com as cenas mais emocionantes:</h2>
				
				<img id="icone" src="_imagens2/ínicio2.JPG">
				
				<hgroup>
					<nav id="menu">
						<ol type="disc">
							<h2>Menu Principal:</h2>
								<li><a href="file:///C:/Users/mathe/OneDrive/Documentos/PROGRAMANDO/PROJETO%20SUPERNATURAL/home.html.html" target="_blank">Home</a></li>
								<li><a href="file:///C:/Users/mathe/OneDrive/Documentos/PROGRAMANDO/PROJETO%20SUPERNATURAL/introdu%C3%A7%C3%A3o.html.html" target="_blank">Especificações</a></li>
								<li><a href="file:///C:/Users/mathe/OneDrive/Documentos/PROGRAMANDO/PROJETO%20SUPERNATURAL/foto.html.html" target="_blank">Fotos</a></li>
								<li><a href="file:///C:/Users/mathe/OneDrive/Documentos/PROGRAMANDO/PROJETO%20SUPERNATURAL/multimidia.html.html" target="_blank">Multimídia</a></li>
								<li><a href="file:///C:/Users/mathe/OneDrive/Documentos/PROGRAMANDO/PROJETO%20SUPERNATURAL/fale-conosco.html.html" target="_blank">Fale-Conosco</a></li>
						</ol>		
					</nav>
				</header>				

				<section id="corpo">
					<article id="noticia-principal">
						<header id="cabecalho-artigo">
				<h3>histórias > emoções</h3>
				<h2>Saíba tudo sobre o Supernatural</h2>
				<h3>por Matheus Santos Peixoto</h3>
				<h3 class="direita">Atualizado no ano de 2023;</h3>
				</header>

				<h2>O surgimento do Supernatural:</h2>
				<p>Superna&shy;tural (Sobrena&shy;tural no Brasil e em Portugal) é uma série de tele&shy;visão da CW, rede de tele&shy;visão dos Estados Unidos. É exibida no Brasil pelo canal a cabo Warner Channel. Em Portugal a série é exibida pelos canais pago e aberto, AXN e RTP2, respecti&shy;vamente. Criada por Eric Kripke, Superna&shy;tural conta a história dos irmãos Sam e Dean Winche&shy;ster, que viajam pelos Estados Unidos num Chevy Impala preto de 1967 inves&shy;tigando eventos sobrena&shy;turais e caçando cria&shy;turas como fantasmas, demônios e vampiros. A série conta com diversos eleme&shy;ntos obtidos em lendas urbanas, em crenças comuns e em mitologia antiga. A família Winche&shy;ster, residente de Lawrence (Kansas), passou por uma tragédia quando Mary Winche&shy;ster, mãe de Sam e Dean, morreu num incêndio causado por circuns&shy;tâncias sobrena&shy;turais. Como resul&shy;&shy;tado, o seu pai, John, dedicou a sua vida a viajar por todo o país para tentar descobrir o que causou a morte da sua mulher e procurar vingança. Ele levou os seus filhos consigo, treinando-&shy;os para lutar contra o mal. Anos mais tarde, Dean continuou com John para o ajudar, enquanto Sam os deixou para estudar na Univer&shy;sidade Stan&shy;ford. Quando o seu pai desa&shy;parece de repente, o seu irmão o procura pedindo ajuda, pois o pai teria desapa&shy;recido. Sam abandona seus projetos pessoais, inclusive a bela namorada, e o acompanha numa busca alucinante. Nesta perigosa jornada, além de tentarem superar as diferenças pessoais, terão pela frente um perigoso trabalho sobrena&shy;tural: encontrarão criaturas que a maioria das pessoas acredi&shy;tavam existir apenas no folclore, supers&shy;tição e pesadelos.</p>														
				<figure class="fonte">
				<img id="icone" src="_imagens2/ft1.JPG">
				<figcaption>
					<h2>Supernatural</h2>
					<p>Disponível no mundo todo.</p>
				</figcaption>
				</figure>

				<h2>Data do Lançamento:</h2>
				<p>A partir desde terça-&shy;feira (22) no Brasil, os Irmãos Sam e Dean Winche&shy;ster embarcam em uma última aventura com o início da 15ª tempo&shy;rada. Conside&shy;rando que o programa está no ar há mais de uma década e já ultra&shy;passou a marca de 300 episó&shy;dios, é meio difícil de acreditar. O segredo do sucesso foi focar em seus perso&shy;nagens e mitologia, que só cresceu ao longo dos anos - mas o começo não poderia ter sido mais diferente. Quando a primeira temporada foi ao ar em 2005, o programa era focado no horror.</p>

				<h2>Especificações Técnicas:</h2>
	 			<table id="tabelaspec">
	 			<caption>Tabela técnica de Supernatural <span>Abri/2023</span></caption>

	 			<tr><td class="ce">Tela</td><td class="cd">Resolução equivalente a tela de 25"</td></tr>
	 			<tr><td rowspan="2" class="ce">Camera</td> <td class="cd">5MP para fotos</td></tr>
	 			<tr><td class="cd">720p para vídeos</td></tr>
	 			<tr><td rowspan="2" class="ce">Conectividade</td><td class="cd">Wi-Fi</td></tr>
	 			<tr><td class="cd">Bluetooth</td></tr>
	 			<tr><td class="ce">Memória Interna</td> <td class="cd">12GB</td></tr>
	 			</table>

				<figure class="fonte">
				<img src="_imagens2/ft3.JPG">
				<figcaption>
					<h2>Supernatural</h2>
					<p>A únião entre irmãos.</p>
				</figcaption>
				</figure>	
				</article>
				
				</section>

				<aside id="lateral">
				<h2>A únião entre os irmãos Sam e Dean:</h2>

				<figure class="fonte">
				<img src="_imagens2/ft2.JPG">
				<figcaption>
					<h2>Supernatural</h2>
					<p>Vídeo demonstrativo sobre a História da série. Acesse o link a seguir: <a href="https://www.youtube.com/watch?v=d0fIMujzZV0" target="_blank"></a>.</p>
				</figcaption>
				</figure>

				<h2>Novídades no Supernatural:</h2>
				<p>Meses após as primeiras notícias sobre o seu desenvo&shy;lvimeto, a série Os Winchesters (The Winches&shy;ters no original) está próxima de ser lançada no Brasil pela HBO Max. E com isso, agora reunimos então os princi&shy;pais detalhes sobre a sua trama e produção em um único texto.</p> 

				</aside>

				<footer id="rodape">
				<p>Copy&shy;right 2023 &copy; by Matheus Peixoto <br/><a href="https://instagram.com/matt_peixotoo/" target="_blank">Instagram</a> | Telefone: (11)985980593.</p>
				</footer>
				</div>		
</body>
</html>
