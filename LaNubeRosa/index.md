<!DOCTYPE html>
<html>
	<head>
		<title>La Nube Rosa</title>
		<!-- Latest compiled and minified CSS -->
		<link rel="stylesheet"href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">		
		<link rel="stylesheet" type="text/css" href="css/css.css">
		
		<script src="https://kit.fontawesome.com/6a23ce6539.js" crossorigin="anonymous"></script>

	</head>
	<body>
		<header>

			<!-- NavBar -->

			<nav class="navbar navbar-expand fixed-top navbar-light" style="background-color: #7c7776; font-family: thin; font-size: 20px;">
				<div class="container-fluid justify-content-center nav-fill">
					<ul class="navbar-nav">
						<li class="nav-item">
							<a class="nav-link active" aria-current="page" href="#">Inicio</a>
						</li>
						<li class="nav-item">
							<a class="nav-link" href="galeria.html">Galería</a>
						</li>
						<li class="nav-item">
							<a class="nav-link" href="sobreMi.html">Sobre mí</a>
						</li>
						<!-- button trigger modal -->
						<li>
							<a id="modalLink" class="nav-link" data-toggle="modal" data-target="#formulario">Contacto</a>
						</li>
					</ul>
				</div>
			</nav>

			<!-- /NavBar -->

		</header>
		
		
		<main>
		<!-- carrusel -->
			
		<div id="carrusel" class="carousel slide" data-ride="carousel">
		  <div class="carousel-inner">
			<div class="carousel-item active">
			  <img class="d-block w-100" src="img/Peque2.jpg" alt="First slide">
			</div>
			<div class="carousel-item">
			  <img class="d-block w-100" src="img/PeterPan2.jpg" alt="Second slide">
			</div>
			<div class="carousel-item">
			  <img class="d-block w-100" src="img/Pirata2.jpg" alt="Third slide">
			</div>
		  </div>
		  
		  <!-- controles carrusel -->
		  <a class="carousel-control-prev" href="#carrusel" role="button" data-slide="prev">
			<span class="carousel-control-prev-icon" aria-hidden="true"></span>
			<span class="sr-only">Previous</span>
		  </a>
		  <a class="carousel-control-next" href="#carrusel" role="button" data-slide="next">
			<span class="carousel-control-next-icon" aria-hidden="true"></span>
			<span class="sr-only">Next</span>
		  </a>
		</div>	
			
		<!-- /carrusel -->
		
		<h2 class="text-center" style="margin-top: 40px; font-size: 26px;">bienvenid@ a</h2>
			<h1 id="NubeRosa" class="text-center">La Nube Rosa</h1>

			<div class="contenedor" align="center">
				
				<!-- presentación -->
				<div class="separador"></div>
				<div class="presentacion row" style="max-width: 768px;">
					<article class="col-12 col-md-6">
						<h2 style="padding-top: 20px;">Hola, soy Miriam</h2>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
					</article>
					<a href="sobreMi.html"><img class=""src="img/0_Higuerita.jpg" height="200px" width="186px"></a>
				</div>
				<!-- presentación -->
				
				<!-- exposición -->
				<div class="separador"></div>
				<div class="presentacion row" style="max-width: 992px";>
					<h2 style="margin-bottom: 20px; font-size: 26px; padding-top= 20px;">Te invito a que conozcas mi trabajo</h2>
					<div style="display: flex; justify-content: space-around; flex-flow: row wrap;">
						<a href="galeria.html"><img src="img/Peque1.jpg" height="170px" width="255px" style="padding: 5px;"></a>
						<a href="galeria.html"><img src="img/PeterPan1.jpg" height="170px" width="255px" style="padding: 5px;"></a>
						<a href="galeria.html"><img src="img/Hermanas3.jpg" height="170px" width="255px" style="padding: 5px;"></a>
					</div>
				</div>
				<!-- exposición -->

				<!-- contacto -->				
				<div class="separador"></div>
					<div class="presentacion row">
						<h2 style="font-size: 26px; padding-top= 20px;">¿Quieres que sea tu fotógrafa?</h2>
						
					</div>
					<a id="modalLink" class="nav-link" data-toggle="modal" data-target="#formulario" style="font-size: 29px; font-family: NeverLetGo;">Contáctame</a>
				<div class="separador"></div>
			</div>
		</main>
		
		
		<footer>	  
			<div class="social">
				<a href="errorContacto.html"><i class="fa fa-instagram"></i></a>        
				<a href="errorContacto.html"><i class="fa fa-whatsapp"></i></a>
				<a href="errorContacto.html"><i class="fab fa-facebook-square"></i></a>
			</div>
		</footer>
		
		<!-- modal -->
		<div class="modal fade" id="formulario" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
		  <div class="modal-dialog" role="document">
			<div class="modal-content">
			  <div class="modal-header">
				<h5 class="modal-title" id="exampleModalLabel">Recuerda decirme quién eres</h5>
				<button type="button" class="close" data-dismiss="modal" aria-label="Close">
				  <span aria-hidden="true">&times;</span>
				</button>
			  </div>
			  <div class="modal-body">
				<form>
				  <div class="form-group">
				    <label for="recipient-name" class="col-form-label">Escribe aquí tu e-mail:</label>
				    <input type="text" class="form-control" id="recipient-name">
				  </div>
				  <div class="form-group">
				    <label for="message-text" class="col-form-label">Mensaje:</label>
				    <textarea class="form-control" id="message-text"></textarea>
				  </div>
				</form>
			  </div>
			  <div class="modal-footer">
				<button type="button" class="btn btn-secondary" data-dismiss="modal">Cerrar</button>
				<button type="button" class="btn btn-primary">Enviar mensaje</button>
			  </div>
			</div>
		  </div>
		</div>
		<!-- /modal -->
		
		<!-- jQuery library -->
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

		<!-- Popper JS -->
		<scriptsrc="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>

		<!-- Latest compiled JavaScript -->
		<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>

	</body>
</html>
