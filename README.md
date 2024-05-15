<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Roupas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: ;
        }

        header {
            
            background-color: #070303;
            color: hsl(0, 14%, 93%);
            padding: 20px;
            text-align: center;
            
          
            }
        .titulo{
           color: #fff;
            background: #000;
            width: 20%;
            
        }
        


        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: hwb(0 93% 6%);
            text-decoration: none;
            background-color: #030303;
          
           
        
        }

        section {
            margin-bottom: 40px;
        }

        .product {
            margin-bottom: 30px;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 2px ;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .buy-button {
            background-color: #4CAF50; 
            border: none;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
        }

        .buy-button:hover {
            background-color: #45a049;
            padding-bottom: 100px;
        }
        .custom-loader {
  --R:60px;
  --g1:#0a0caa 96%, #0000;
  --g2:#ec0cb4 96%, #0000;
  width: calc(2*var(--R));
  height:calc(2*var(--R));
  border-radius:50%;
  display: grid;
  -webkit-mask:linear-gradient(#000 0 0);
  animation: s10 25s infinite linear;
}
.custom-pattern {
	background: 
		  radial-gradient(calc(1.28*32px + 12px/2) at left 50% bottom calc(-.8*32px),#1A8FE5 calc(100% - 12px),#040405 calc(101% - 12px) 100%,#0000 101%) calc(2*32px) calc(-1*calc(1.5*32px + 12px)),
		  radial-gradient(calc(1.28*32px + 12px/2) at left 50% bottom calc(-.8*32px),#E536BC calc(100% - 12px),#030303 calc(101% - 12px) 100%,#0000 101%) calc(-1*32px) calc(calc(1.5*32px + 12px)/-2),
		  radial-gradient(calc(1.28*32px + 12px/2) at left 50% top    calc(-.8*32px),#E536BC calc(100% - 12px),#03030e calc(101% - 12px) 100%,#0000 101%) 0 calc(1.5*32px + 12px),
		  radial-gradient(calc(1.28*32px + 12px/2) at left 50% top    calc(-.8*32px),#1A8FE5 calc(100% - 12px),#04040a calc(101% - 12px) 100%,#0000 101%) 32px calc(calc(1.5*32px + 12px)/ 2),
		  linear-gradient(#1A8FE5 50%,#E536BC 0);
	background-size: calc(4*32px) calc(1.5*32px + 12px);
}
.custom-loader::before,
.custom-loader::after{
  content:"";
  grid-area: 1/1;
  width:50%;
  background:
    radial-gradient(farthest-side,var(--g1)) calc(var(--R) + 0.866*var(--R) - var(--R)) calc(var(--R) - 0.5*var(--R)   - var(--R)),
    radial-gradient(farthest-side,var(--g1)) calc(var(--R) + 0.866*var(--R) - var(--R)) calc(var(--R) - 0.5*var(--R)   - var(--R)),
    radial-gradient(farthest-side,var(--g2)) calc(var(--R) + 0.5*var(--R)   - var(--R)) calc(var(--R) - 0.866*var(--R) - var(--R)),
    radial-gradient(farthest-side,var(--g1)) 0 calc(-1*var(--R)),
    radial-gradient(farthest-side,var(--g2)) calc(var(--R) - 0.5*var(--R)   - var(--R)) calc(var(--R) - 0.866*var(--R) - var(--R)),
    radial-gradient(farthest-side,var(--g1)) calc(var(--R) - 0.866*var(--R) - var(--R)) calc(var(--R) - 0.5*var(--R)   - var(--R)),
    radial-gradient(farthest-side,var(--g2)) calc(-1*var(--R))  0,
    radial-gradient(farthest-side,var(--g1)) calc(var(--R) - 0.866*var(--R) - var(--R)) calc(var(--R) + 0.5*var(--R)   - var(--R));
   background-size:calc(2*var(--R)) calc(2*var(--R));
   background-repeat:no-repeat;
}

.custom-loader::after {
 transform:rotate(180deg);
 transform-origin:right;
}

@keyframes s10 {
  100% {transform: rotate(-1turn)}
}
.plamodefundo{
    background-image:;
}

    </style>
</head>
<body >
    <header class="custom-pattern">
        
        <h1 class="titulo">Loja de Roupas</h1>
        <br><img src="https://th.bing.com/th/id/OIP.AZQ4qVj3NzDwJywVExFOSAHaEp?w=278&h=183&c=7&r=0&o=5&pid=1.7" width="15%"><img src="https://th.bing.com/th/id/OIP.62M6xCS87M-vLSoNsOQhQQHaE7?w=264&h=180&c=7&r=0&o=5&pid=1.7" width="15%"><br><br>
        <nav>
            <ul>
                <li><a href="#masculinas">Roupas Masculinas</a></li>
                <li><a href="#femininas">Roupas Femininas</a></li>
                <li><a href="#infantis">Roupas Infantis</a></li>
                <li><a href="#acessorios">Acessórios</a></li>
            </ul>
        </nav>
    </header>
<div>
    <section id="masculinas" >
        <div class="custom-loader" >ROUPAS MASCULINAS </div>
        <div class="product">
            <img src="imagem-produto-masculino.jpg" alt="Nome do Produto Masculino">
            <h3>Nome do Produto Masculino</h3>
            <p>Descrição do produto e suas características.</p>
            <p>Preço: R$ XX,XX</p>
            <a href="#comprar" class="buy-button">Comprar</a>
        </div>
        
        <!-- Adicione mais produtos masculinos aqui -->
    </section>

    <section id="femininas">
        <div class="custom-loader" > >ROUPAS FEMININAS</div>
        <div class="product">
            <img src="imagem-produto-feminino.jpg" alt="Nome do Produto Feminino">
            <h3>Nome do Produto Feminino</h3>
            <p>Descrição do produto e suas características.</p>
            <p>Preço: R$ XX,XX</p>
            <a href="#comprar" class="buy-button">Comprar</a>
        </div>
        
        <!-- Adicione mais produtos femininos aqui -->
    </section>

    <section id="infantis">
        <h2>Roupas Infantis</h2>
        <div class="product">
            <img src="imagem-produto-infantil.jpg" alt="Nome do Produto Infantil">
            <h3>Nome do Produto Infantil</h3>
            <p>Descrição do produto e suas características.</p>
            <p>Preço: R$ XX,XX</p>
            <a href="#comprar" class="buy-button">Comprar</a>
        </div>
        
        <!-- Adicione mais produtos infantis aqui -->
    </section>
    <section id="acessorios">
        <h2>Acessórios</h2>
        <div class="product">
            <img src="imagem-produto-acessorios.jpg" alt="Nome do Produto Acessório">
            <h3>Nome do Produto Acessório</h3>
            <p>Descrição do produto e suas características.</p>
            <p>Preço: R$ XX,XX</p>
            <a href="#comprar" class="buy-button">Comprar</a>
        </div>
        
        <!-- Adicione mais produtos acessorios aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Loja de Roupas</p>
    </footer>

</div>
</body>
</html>
