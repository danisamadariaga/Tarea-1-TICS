# Tarea-1-TICS

<!DOCTYPE html>
<html>
<head> 
		<title> Login Abruzzi </title>
</head>
<body>
	<div align="center">
		<form action="./index.php" method="POST">
	  	<h1> Creación de nueva cuenta</h1>
			Nombre Completo:<input type="text" name="nombre" placeholder='Su nombre'/>
			<br>
			Nombre de Usuario:<input type="text" name="usuario"  placeholder='Usuario'/>
			<br>
			Contraseña:<input type="password" name="contrasena" placeholder='Contraseña'/>
			<br>
			<input type="submit" value="Enviar!" />
		</form>
		<br>
		<hr>
		<h1> Login cuenta antigua</h1>
		<hr>
		<br>
		<form action="./inicio.php" method="POST">
			Nombre de Usuario:<input type="text" name="usuario"  placeholder='Usuario'/>
			<br>
			Contraseña:<input type="password" name="contrasena" placeholder='Contraseña'/>
			<br>
			<input type="submit" value="Iniciar Sesión"/>
		</form>
	</div>
</body>
</html>
