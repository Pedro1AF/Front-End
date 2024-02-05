# Front-End
Retomada HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon-Like</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #232f3e;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin: 10px;
            width: 300px;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background-color: #232f3e;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Amazon-Like</h1>
</header>

<section>
    <div class="product">
        <img src="produto1.jpg" alt="Produto 1">
        <h2>Nome do Produto 1</h2>
        <p>Descrição do Produto 1.</p>
        <p>R$ 99,99</p>
        <button onclick="adicionarAoCarrinho(1)">Adicionar ao Carrinho</button>
    </div>

    <div class="product">
        <img src="produto2.jpg" alt="Produto 2">
        <h2>Nome do Produto 2</h2>
        <p>Descrição do Produto 2.</p>
        <p>R$ 149,99</p>
        <button onclick="adicionarAoCarrinho(2)">Adicionar ao Carrinho</button>
    </div>

    <!-- Adicione mais produtos conforme necessário -->

</section>

<footer>
    &copy; 2024 Amazon-Like
</footer>

<script>
    function adicionarAoCarrinho(idProduto) {
        // Lógica para adicionar o produto ao carrinho
        alert("Produto adicionado ao carrinho!");
    }
</script>

</body>
</html>
