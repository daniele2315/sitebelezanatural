<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Login</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-size: cover;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        .login-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(214, 83, 164, 0.42);
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
            width: 320px;
        }

        .login-container h2 {
            text-align: center;
            margin-bottom: 25px;
        }

        .login-container input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 16px;
        }

        .login-container button {
            width: 100%;
            padding: 12px;
            background-color: #2c3e50;
            color: white;
            font-size: 16px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            margin-top: 10px;
        }

        .login-container button:hover {
            background-color: #34495e;
        }

        .error {
            color: red;
            text-align: center;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Área de Login</h2>
        <input type="text" id="usuario" placeholder="Usuário">
        <input type="password" id="senha" placeholder="Senha">
        <button onclick="verificarLogin()">Entrar</button>
        <p id="mensagemErro" class="error"></p>
    </div>

    <script>
        function verificarLogin() {
            const usuario = document.getElementById('usuario').value;
            const senha = document.getElementById('senha').value;
            const mensagemErro = document.getElementById('mensagemErro');

            const usuarioCorreto = "aluno";
            const senhaCorreta = "123";

            if (usuario === usuarioCorreto && senha === senhaCorreta) {
                window.location.href = "pagina-principal.html";
            } else {
                mensagemErro.textContent = "Usuário ou senha incorretos!";
            }
        }
    </script>
</body>
</html>
