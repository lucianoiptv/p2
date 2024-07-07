
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Obtenha 10% de desconto - [Nome do seu Negócio]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333333;
        }
        form {
            margin-top: 20px;
        }
        input[type="text"], input[type="email"] {
            width: calc(100% - 20px);
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #cccccc;
            border-radius: 4px;
            font-size: 16px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 4px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Ganhe 10% de desconto!</h1>
        <p>Cadastre-se e receba um cupom exclusivo para utilizar em sua primeira compra.</p>
        
        <form action="https://api.whatsapp.com/send" method="GET">
            <input type="hidden" name="phone" value="5522999931187">
            <input type="hidden" name="text" value="Olá! Gostaria de receber meu cupom de 10% de desconto.">
            
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="name" required><br>
            
            <label for="telefone">Telefone:</label><br>
            <input type="text" id="telefone" name="phone" required><br>
            
            <label for="email">E-mail:</label><br>
            <input type="email" id="email" name="email" required><br>
            
            <input type="submit" value="Receber meu cupom">
        </form>
    </div>
</body>
</html>