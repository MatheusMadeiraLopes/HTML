Criando um formulario HTML

..Formulario.HTML..

 <html>
<html lang="pt-BR">
<head>
	<title>Formulário de Cadastro</title>
	<link rel="stylesheet" type="text/css" href="css\estilo.css">
</head>
<body>
	<div class="container">
		<h2>Formulário de Cadastro</h2>
		<form action="#" method="post">
			<div class="form-group">
				<label for="nome">Nome:</label>
				<input type="text" id="nome" name="nome" required>
			</div>
			<div class="form-group">
				<label for="CPF">CPF:</label>
				<input type="text" id="cpf" name="cpf" required>
			</div>
			<div class="form-group">
				<label for="email">E-mail:</label>
				<input type="email" id="email" name="email" required>
			</div>
			<div class="form-group">
				<label for="celular">Celular:</label>
				<input type="text" id="celular" name="celular" required>
			</div>
			<div class="form-group">
				<label for="senha">Senha:</label>
				<input type="password" id="senha" name="senha" required>
			</div>
			<button type="submit">Cadastrar</button>
		</form>
	</div>
</body>
</html>

..css/estilo.css..

body {
	font-family: Arial, sans-serif;
	background-color: #f4f4f4;
	margin: 0;
	padding: 0;
}

.container {
	max-width: 500px;
	background-color: #fff;
	margin: 20px auto;
	padding: 20px;
	border-radius: 5px;
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
	text-align: center;
}

.form-group {
	margin-bottom: 20px;
}

.form-group label {
	display: block;
	font-weight: bold;
}

.form-group input[type="text"],
.form-group input[type="email"],
.form-group input[type="password"] {
	width: 100%;
	padding: 10px;
	margin: 5px 0;
	border: 1px solid #ccc;
	border-radius: 3px;
}

.form-group button {
	background-color: #007BFF;
	color: #fff;
	padding: 10px 20px;
	border: none;
	border-radius: 3px;
	cursor: pointer;
}

#nome, #cpf, #email, #celular, #senha {
	width: 95%;
	padding: 10px;
	margin: 5px 0;
	border: 1px solid #ccc;
	border-radius: 3px;
}

button[type="submit"] {
	background-color: #007BFF;
	color: #fff;
	padding: 10px 20px;
	border: none;
	border-radius: 3px;
	cursor: pointer;
}

label[for="cpf"], label[for="celular"] {
	display: block;
	font-weight: bold;
}
