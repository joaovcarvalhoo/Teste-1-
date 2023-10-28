# Teste-1-
minha primeira tentativa 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leão do Norte</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Additional CSS for interactive pricing */
        .product {
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        .price {
            font-size: 16px;
            color: #ff5733;
            cursor: pointer;
            text-decoration: underline;
        }

        .price:hover {
            color: #ff0000; /* Change color on hover */
        }
    </style>
</head>
<body>
    <header>
        <div class="top-header">
            <div class="logo">
                <img src="leao-do-norte-logo.png" alt="Leão do Norte">
            </div>
            <div class="search">
                <input type="text" placeholder="Pesquisar produtos">
                <button type="button">Buscar</button>
            </div>
            <div class="user-menu">
                <a href="#">Entrar</a>
                
                <
<a href="#">Carrinho</a>
            
            </
</div>
        </div>
        <nav>
            <ul>
                <li><a href="/">Página Inicial</a></li>
                <li><a href="/produtos">Produtos</a></li>
                <li><a href="/ofertas">Ofertas</a></li>
                <li><a href="/supermercado">Supermercado</a></li>
            </ul>
        </nav>
    
    </
</header>
    <main>
        
       
<section id="informacoes">
            
            <
<h2>Ofertas e Descontos</h2>
            <p>Encontre as melhores ofertas e descontos em nosso supermercado.</p>
        </section>
        <section id="produtos">
            <h2>Produtos em Destaque</h2>
            <ul id="listaProdutos">
                <li class="product">
                    <img src="custom-image1.jpg" alt="Produto 1">
                    <h3>Produto 1</h3>
                    <p>Descrição do Produto 1</p>
                    <p class="price">Preço: R$ <span id="price1">10.99</span></p>
                    <button type="button">Adicionar ao Carrinho</button>
                </li>
                <li class="product">
                    <img src="custom-image2.jpg" alt="Produto 2">
                    <h3>Produto 2</h3>
                    <p>Descrição do Produto 2</p>
                    <p class="price">Preço: R$ <span id="price2">19.99</span></p>
                    <button type="button">Adicionar ao Carrinho</button>
                </li>
                <li class="product">
                    <img src="custom-image3.jpg" alt="Produto 3">
                    <h3>Produto 3</h3>
                    <p>Descrição do Produto 3</p>
                    
                   
<p class="price">Preço: R$ <span id="price3">15.49</span></p>
                    <button type="button">Adicionar ao Carrinho</button>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Leão do Norte. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
