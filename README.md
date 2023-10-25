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
