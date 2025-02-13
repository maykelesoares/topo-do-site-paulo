<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<title>Criação de sites com HTML e CSS | Paulo Silva</title>
		<meta charset="UTF-8">
		<script scr="../html5shiv.js"></script>
		<link rel="stylesheet" type="text/css" href="../normalize.css" media="all"></link>
		<style rel="stylesheet">
			html{
				box-sizing:border-box;
			}
			*, *:before, *:after{
				box-sizing:inherit;
			}
			body{
				font: 18px/1.4 arial, sans-serif;
				background: #ddd;
				color: #333;
			}
			.tudo{
				width: 100%;
				max-width: 960px;
				margin: 0 auto;
				background: #fff;
			}
			.topo{ 
				width: 100%;
			}
			.topo h1{
				font-size: 36px;
			}
			.topo h2{
				font-size: 27px;
				}
			.topo{
				width: 100%;
				line-height:1;
				padding: 1px 20px 10px 20px;
			}
			.topo h1{
				font-size:36px;
				margin: 4px 0 2px 0;
				text-align: right;
			}
			.topo a{
				color: #900;
				text-decoration: none;
			}
			.topo h2{
				font-size: 20px;
				margin: 2px 0 4px 0;
				text-align:right;
			}			
		</style>
	</head>
	<body class="home">
		<div class="tudo">
			<header class="topo">
				<hgroup>
					<h1><a href="">Site do Paulo</a></h1>
					<h2>Site destinado a divulgar o trabalho do Paulo na criação de sites</h2>
				</hgroup>
				<nav>
					<ul>
						<li><a class="corrente" href="home.html">Home</a></li>
						<li><a href="portfolio.html">Portfólio</a></li>
						<li><a href="artigos-html.html">Artigos HTML</a></li>
						<li><a href="artigos-css.html">Artigos CSS</a></li>
						<li><a href="contato.html">Contato</a></li>
						<div class="clear"></div> <!-- Capítulo 6 - "limpar floats" -->
					</ul>
				</nav>
			</header>
				<!-- mais conteúdo -->
			<footer class="rodape">
				<!-- mais conteúdo do site -->
			</footer>
		</div>
	</body>
</html>
