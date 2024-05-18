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
            background-image: url(../projetodaniel/plano-de-fundo-transparente-com-lindas-roupas-femininas-de-verao_257845-1811.avif);
        }

        header {
            background-color: hsl(0, 2%, 20%);
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
            background-color: ;
        }

        section {
            margin-bottom: 40px;
        }

        .product {
            margin-bottom: 30px;
            display: inline-block;
        }

        .product,img {
            max-width: 100%;
            height: auto;           
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            margin: 0;
        }

        .buy-button {
            background-color: #4d524d; 
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
        .menu-button {
            background-color: #4d524d; 
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
            font-family: fantasy;
        }
        .menu-button:hover {
            background-color: #262926;
        }
        
          .planodefundo{
              background-image:;
          }

        .buy-button:hover {
            background-color: #262926;
        }

        #formulario {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #fff;
            z-index: 9999;
            display: none;
        }

        #formulario input {
            width: 92%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        #formulario button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: block;
            width: 98%;
            font-size: 16px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
        }

        #formulario button:hover {
            background-color: #45a049;
        }
        div.body {
            display: inline-block;
            border: 2px solid black;
            border-radius: 2px;
            background-color: white;

        }
        
        .content {
            background-color: white;
            max-width: 1500px;
            margin: 50px auto;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }

        .header_color {
            background-image: linear-gradient(to bottom, grey, rgb(51, 51, 51)
            );
        } 
        footer {
            width: 100%;
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: auto;
        }
        .product_infantil {
            margin-bottom: 60px; 
        }

        .product img {
            margin-right: 30px;
        }
        .product_infantil2 {
            margin-bottom: 60px;
        }

        .product_infantil2 img {
            margin-right: 30px;
        }
        .product_infantil3 {
            margin-bottom: 60px;
        }

        .product_infantil3 img {
            margin-right: 30px;
        }
        #infantil {
            margin-right: 60px;
            margin-left: 60px;
            margin-top: 20px;
            margin-bottom: 20px;
            display: flex;
        }
        .groove {border-style: groove;
        
        }
        .ull {
            background-color: #292c29; 
            border: none;
            color: white;
            padding: 10px 10px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 15px;
            margin-top: 9px;
            cursor: pointer;
            border-radius: 5px;
        }

    </style>
</head>
<body>
    <header class="header_color">
        <h1>Moda Front-end</h1>
        <br><img src="https://th.bing.com/th/id/OIP.AZQ4qVj3NzDwJywVExFOSAHaEp?w=278&h=183&c=7&r=0&o=5&pid=1.7" width="15.5%"><img src="https://th.bing.com/th/id/OIP.62M6xCS87M-vLSoNsOQhQQHaE7?w=264&h=180&c=7&r=0&o=5&pid=1.7" width="15%"><br><br>
        <nav>
            
            <ul class="ull">
                <li class="menu-button"><a href="#masculinas">Roupas Masculinas</a></li>
                <li class="menu-button"><a href="#femininas">Roupas Femininas</a></li>
                <li class="menu-button"><a href="#infantis">Roupas Infantis</a></li>
                <li class="menu-button"><a href="#acessorios">Acessórios</a></li>
            </ul>
                   
        </nav>
    </header>
    <div class="content">
    <section id="masculinas">
        <div class="custom-loader" >ROUPAS MASCULINAS </div>
        <div class="product">
            <img src="imagem-produto-masculino.jpg" alt="Nome do Produto Masculino">
            <h3>Nome do Produto Masculino</h3>
            <p>Descrição do produto e suas características.</p>
            <p>Preço: R$ XX,XX</p>
            <button class="buy-button" onclick="exibirFormulario()">Comprar</button>
        </div>
        
        <!-- Adicione mais produtos masculinos aqui -->
    </section>

    <section id="femininas">
        <div class="product">
            <h4 style="font-family: Arial, Helvetica, sans-serif;">Roupas Femininas</h4>
            <p style="font-family: Arial, Helvetica, sans-serif;">Categoria</p>
            <section class="div.body">
            <img width=300px src="https://i.pinimg.com/564x/12/52/79/125279262ed7e8fe624f28b3ea15f1a7.jpg">
 
               <h5  style="font-family: sans-serif;"><a href="file:///C:/Users/heloi/OneDrive/Documentos/croppeds.loja.html">CROPPEDS</h5></a>
               <img width=300px src="https://i.pinimg.com/564x/ee/bf/11/eebf117663a56b14cc17eb1b7dfe1bff.jpg">
               <h5 style="font-family: sans-serif;" ><a href="file:///C:/Users/heloi/OneDrive/Documentos/camisetas.loja.html">CAMISETAS</h5></a>
               <img width=300px src="https://i.pinimg.com/564x/e2/f3/20/e2f320528d5719e028fe584aaf3144b1.jpg">
               <h5 style="font-family: sans-serif;" > <a href="file:///C:/Users/heloi/OneDrive/Documentos/casacos.loja.html">Casacos</h5></a>
               <div>
              <img width=300px src="https://i.pinimg.com/564x/8e/ea/fb/8eeafb46fa84d7a90d9a26bef7015c6a.jpg">
                   <label><a href="file:///C:/Users/heloi/OneDrive/Documentos/vestidos.loja.html">Vestidos</label></a>
               <select name="vestidos">
                   <option value="selecione">selecione</option>
                   <option value="longos">longos</option>
                   <option value="curtos">curtos</option>
               </select>
           </div>
           <img width=300px src="https://i.pinimg.com/564x/e0/15/46/e015468643ed648b36359293cca82faf.jpg">
           <h5 style="font-family: sans-serif;" > <a href="file:///C:/Users/heloi/OneDrive/Documentos/shorts.loja.html">Shorts</h5></a>
              <img width=300px src="https://i.pinimg.com/564x/74/0b/5f/740b5f82b2ccc12c9c58280aef5755d1.jpg">
           <h5 style="font-family: sans-serif;"> <a href="file:///C:/Users/heloi/OneDrive/Documentos/cal%C3%A7as.loja.html">Calças</h5></a>
           <div>
              <img width=300px  src="https://i.pinimg.com/564x/d9/3e/bc/d93ebc9e3ccf317d5cd8f4db0bfeacd6.jpg">
               <label> <a href="file:///C:/Users/heloi/OneDrive/Documentos/saias.loja.html" style="text-decoration:none;" >Saias</label></a>
               <select name="saias">
                   <option value="selecione">Selecione</option>
                   <option value="longas">Longas</option>
                   <option value="curtas">Curtas</option>
               </select>
           </div>
            <button class="buy-button" onclick="exibirFormulario()">Comprar</button>
        </div>       
        <!-- Adicione mais produtos femininos aqui -->
    </section>

    <section id="infantil" class="product_infantil">
        <h2>Roupas Infantis</h2>
            <div class="product">
    
            <a href="conjutos.html"> 
                <h3>Conjutos</h3>
                <img src="shopping.png" alt="Conjuntos Infantis" style="border: 5px solid black;" >
            </a>
            </div>
    
            <div class="product_infantil2">
            <a href="sapatos.html">
                <h3>Sapatos</h3>
                <img src="baixados.png" alt="Sapatos" style="border: 5px solid black;">
            </a>
            </div>
    
            <div class="product_infantil3">
            <a href="acessorios.html">
                <h3>Acessorios</h3>
                <img src="baixadosp.png" alt="Acessorios" style="border: 5px solid black;">
            </a>
            </div>
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
    </section>    
        <br><br><br>

    <div id="formulario">
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefone">Telefone:</label>
            <input type="tel" id="telefone" name="telefone" required>
            <h3>Informações do cartão</h3>
            <label for="numero_cartao">Número do cartão:</label>
            <input type="text" id="numero_cartao" name="numero_cartao" required>
            <label for="validade_cartao">Validade:</label>
            <input type="text" id="validade_cartao" name="validade_cartao" required>
            <label for="cvv">CVV:</label>
            <input type="text" id="cvv" name="cvv" required>

            <button type="button" onclick="confirmarCompra()">Confirmar Compra</button>
        </form>
    </div>
    </div>
    <footer>
        <p>&copy; 2024 Loja de Roupas</p>
    </footer>
    <script>
        function exibirFormulario() {
            document.getElementById('formulario').style.display = 'block';
        }

        function confirmarCompra() {
            var nome = document.getElementById('nome').value;
            var email = document.getElementById('email').value;
            var telefone = document.getElementById('telefone').value;

            

            alert("Compra realizada com sucesso!\nNome: " + nome + "\nEmail: " + email + "\nTelefone: " + telefone);
            document.getElementById('formulario').style.display = 'none';
        }
    </script>
</body>
</html>
