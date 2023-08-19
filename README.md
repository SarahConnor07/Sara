# Sara
<!DOCTYPE html>
<html>
<head>
  <title>Vôlei life</title>
  <style>
  
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      color: #333;
    }

    header {
      background-color: #333;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 32px;
      font-weight: bold;
      color: #fff;
    }

    p {
      font-size: 18px;
      color: #fff;
    }

    section {
      padding: 80px;
      text-align: center;
    }

    h2 {
      font-size: 24px;
      font-weight: bold;
      color: #333;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 20px;
    }

    .product {
      background-color: #fff;
      padding: 20px;
      text-align: center;
      border-radius: 4px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .product img {
      max-width: 100%;
      height: auto;
    }

    .product h3 {
      margin: 10px 0;
      font-size: 18px;
      font-weight: bold;
    }

    .product p {
      font-size: 16px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Vôlei life</h1>
    <p>Seu destino para compras online</p>
  </header>

  <section id="vitrine">
    <h2>Produtos em Destaque</h2>
    <div class="product-grid">
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/61i3l4yD0AL._AC_SX425_.jpg" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>R$199,99</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/41kIeDm-2yL._AC_SX425_.jpg" alt="Produto 2">
        <h3>Produto 2</h3>
        <p>R$46,50</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/51X3wCBfa2L._AC_SX425_.jpg" alt="Produto 3">
        <h3>Produto 3</h3>
        <p>R$19,99</p>
      </div>
    </div>
  </section>

</body>
</html>
CSS
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
}

/* Estilos do header */
header {
  background-color: #333;
  padding: 20px;
  text-align: center;
}

h1 {
  margin: 0;
  font-size: 32px;
  font-weight: bold;
  color: #fff;
}

p {
  font-size: 18px;
  color: #fff;
}

/* Estilos do section principal */
section {
  padding: 80px;
  text-align: center;
}

h2 {
  font-size: 24px;
  font-weight: bold;
  color: #333;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
}

.product {
  background-color: #fff;
  padding: 20px;
  text-align: center;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.product img {
  max-width: 100%;
  height: auto;
}

.product h3 {
  margin: 10px 0;
  font-size: 18px;
  font-weight: bold;
}

.product p {
  font-size: 16px;
}
Para usar esse arquivo CSS separado, salve-o com a extensão ".css" (por exemplo, "estilos.css") e adicione uma referência a ele no seu arquivo HTML usando a tag <link> no <head> do documento:

html
Copy code
<!DOCTYPE html>
<html>
<head>
  <title>Minha Loja de Vôlei</title>
  <link rel="stylesheet" type="text/css" href="estilos.css">
</head>
<body>
  <!-- Conteúdo HTML da sua loja -->

</body>
</html>



