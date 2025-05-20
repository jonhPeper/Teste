<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Login</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: flex-start; /* Alinha ao topo */
      padding-top: 80px;        /* Espaço do topo até o conteúdo */
      background: linear-gradient(120deg, #2980b9, #6dd5fa);
    }

    .login-container {
      background: rgba(32, 63, 166, 0.678);
      padding: 30px 40px;
      border-radius: 10px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      width: 300px;
      text-align: center;
    }

    .login-container h2 {
      margin-bottom: 20px;
      color: #333;
    }

    .login-container input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .login-container button {
      width: 100%;
      padding: 10px;
      background-color: #2980b9;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    .login-container button:hover {
      background-color: #2573a6;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form>
      <input type="email" placeholder="E-mail" required>
      <input type="password" placeholder="Senha" required>
      <button type="submit">Entrar</button>
    </form>
  </div>
</body>
</html>
---------------
2° PARTE:
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title> Faça seu login</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #6d9ce1;
      display: flex;
      height: 100vh;
      align-items: center;
      justify-content: center;
    }

    .login-container {
      background-color: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      width: 300px;
      text-align: center;
    }

    .login-container h2 {
      margin-bottom: 20px;
      color: #333;
    }

    .login-container input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .login-container button {
      width: 100%;
      padding: 10px;
      background-color: #3b82f6;
      color: white;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .login-container button:hover {
      background-color: #2563eb;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form>
      <input type="text" placeholder="Usuário" required />
      <input type="password" placeholder="Senha" required />
      <button type="submit">Entrar</button>
    </form>
  </div>
</body>
</html>
