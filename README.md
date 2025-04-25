
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hogarmax</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100">
  <!-- Navbar -->
  <header class="bg-white shadow p-4 flex items-center justify-between sticky top-0 z-50">
    <div class="flex items-center space-x-4">
      <img src="https://i.pinimg.com/736x/94/c3/fd/94c3fd4659dbcd871829b834f8b21d95.jpg" alt="Logo" class="w-10 h-10">
      <h1 class="text-2xl font-bold">Hogarmax</h1>
    </div>
    <nav class="space-x-4">
      <a href="#destacados" class="text-gray-700 hover:text-blue-600">Destacados</a>
      <a href="#tecnologia" class="text-gray-700 hover:text-blue-600">Tecnología</a>
      <a href="#moda" class="text-gray-700 hover:text-blue-600">Moda</a>
      <a href="#belleza" class="text-gray-700 hover:text-blue-600">Belleza</a>
      <a href="#entretenimiento" class="text-gray-700 hover:text-blue-600">Entretenimiento</a>
      <a href="#hogar" class="text-gray-700 hover:text-blue-600">Hogar</a>
    </nav>
    <div class="flex items-center space-x-4">
      <input id="searchInput" type="text" placeholder="Buscar productos..." class="border p-1 rounded">
      <a href="#cuenta" class="text-gray-700">Cuenta</a>
      <a href="#" id="carritoBtn" class="text-gray-700 relative">
        Carrito <span id="carritoCantidad" class="absolute -top-2 -right-2 bg-red-500 text-white rounded-full text-xs px-1">0</span>
      </a>
    </div>
  </header>

  <!-- Contenedor principal -->
  <main id="productContainer">
    <!-- Sección: Productos Destacados -->
    <section id="destacados" class="p-6">
      <h2 class="text-2xl font-semibold mb-4">Productos Destacados</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <!-- Producto 1: Consola de videojuegos -->
        <div class="bg-white p-4 rounded shadow product-card" data-name="Consola de videojuegos">
          <img src="https://www.alkosto.com/medias/711719570875-001-750Wx750H?context=bWFzdGVyfGltYWdlc3wyMjQ5OHxpbWFnZS93ZWJwfGFEWXdMMmd4Tnk4eE5EWTNOVEF6TWpNM05UTXlOaTgzTVRFM01UazFOekE0TnpWZk1EQXhYemMxTUZkNE56VXdTQXxhMDY5ZDYwMDAwODlhOTljMGY0OGZlODQxMGViZmNhODIzZDMzMWUxY2EyZDE1NDZjNTM3ZTMwNGRmYzI2NWMy" alt="Consola de videojuegos" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Consola PS5 Estándar 1TB Slim Blanco|Negro + 1 Control inalámbrico + Juego PS5 Returnal + Juego PS5 Ratchet & Clank: Rift Apart</h3>
 <h4>$2.599.900</h4>

          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <!-- Producto 2: Reloj inteligente -->
        <div class="bg-white p-4 rounded shadow product-card" data-name="Reloj inteligente">
          <img src="https://www.alkosto.com/medias/7707278178853-001-750Wx750H?context=bWFzdGVyfGltYWdlc3wyNTk5OHxpbWFnZS93ZWJwfGFESmlMMmcyTXk4eE5ETTJOREV4TlRNek56STBOaTgzTnpBM01qYzRNVGM0T0RVelh6QXdNVjgzTlRCWGVEYzFNRWd8ODI2OTQzZTE4NzkzMGRmM2JkZDQzNmY1YzA2ZDM5NDQzM2NiMDFkNWQwZGFlNjc3YzZmOWM5NzM2NjhiN2E3MQ" alt="Reloj inteligente" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Reloj Inteligente ESENSES 44.3 mm SW-10 Negro + Cargador de pared USB-C + Cable de carga tipo C</h3>
 <h4>$249.900</h4>

          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <!-- Producto 3: Air fryer -->
        <div class="bg-white p-4 rounded shadow product-card" data-name="Air fryer">
          <img src="https://www.alkosto.com/medias/6941812776704-001-750Wx750H?context=bWFzdGVyfGltYWdlc3w1OTI0fGltYWdlL3dlYnB8YUROaUwyaGpaUzh4TkRreE1qY3pNREF3TlRVek5DODJPVFF4T0RFeU56YzJOekEwWHpBd01WODNOVEJYZURjMU1FZ3w4MjVjMGI0N2ZmMmNiOGE4YzFlNjQwZTQ3YWM1YzFiZjUyNzM1ODUyODZmYmY0YjZjN2IwMmM4M2E3YWZiNjVi" alt="Air fryer" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Freidora de Aire XIAOMI Essential 6L Blanco</h3>
<h4>$299.900</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <!-- Producto 4: Zapatillas -->
        <div class="bg-white p-4 rounded shadow product-card" data-name="Zapatillas">
          <img src="https://exitocol.vteximg.com.br/arquivos/ids/24645021/image-63295cdd4b2c41999e83d9cf11bada33.jpg?v=638618358889600000" alt="Zapatillas" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Zapatilla Ciclismo Ruta GW PEAK Gris/Verde Talla: 39</h3>
 <h4>$210.500</h4>

          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
      </div>
    </section>

    <!-- Sección: Tecnología -->
    <section id="tecnologia" class="p-6">
      <h2 class="text-2xl font-semibold mb-4">Tecnología</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="bg-white p-4 rounded shadow product-card" data-name="Consola de videojuegos">
          <img src="https://www.alkosto.com/medias/711719570875-001-750Wx750H?context=bWFzdGVyfGltYWdlc3wyMjQ5OHxpbWFnZS93ZWJwfGFEWXdMMmd4Tnk4eE5EWTNOVEF6TWpNM05UTXlOaTgzTVRFM01UazFOekE0TnpWZk1EQXhYemMxTUZkNE56VXdTQXxhMDY5ZDYwMDAwODlhOTljMGY0OGZlODQxMGViZmNhODIzZDMzMWUxY2EyZDE1NDZjNTM3ZTMwNGRmYzI2NWMy" alt="Consola de videojuegos" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Consola PS5 Estándar 1TB Slim Blanco|Negro + 1 Control inalámbrico + Juego PS5 Returnal + Juego PS5 Ratchet & Clank: Rift Apart</h3>
 <h4>$2.599.900</h4>

          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Reloj inteligente">
          <img src="https://www.alkosto.com/medias/7707278178853-001-750Wx750H?context=bWFzdGVyfGltYWdlc3wyNTk5OHxpbWFnZS93ZWJwfGFESmlMMmcyTXk4eE5ETTJOREV4TlRNek56STBOaTgzTnpBM01qYzRNVGM0T0RVelh6QXdNVjgzTlRCWGVEYzFNRWd8ODI2OTQzZTE4NzkzMGRmM2JkZDQzNmY1YzA2ZDM5NDQzM2NiMDFkNWQwZGFlNjc3YzZmOWM5NzM2NjhiN2E3MQ" alt="Reloj inteligente" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Reloj Inteligente ESENSES 44.3 mm SW-10 Negro + Cargador de pared USB-C + Cable de carga tipo C</h3>
<h4>$249.900</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Auriculares inalámbricos">
          <img src="https://http2.mlstatic.com/D_NQ_NP_779146-MLA53778959612_022023-O.webp" alt="Auriculares inalámbricos" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">AirPods Pro 2ª generación 1.1 454dfs Blanco</h3>
          <h4>$1.012.000</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Tableta">
          <img src="https://http2.mlstatic.com/D_NQ_NP_643420-MLU77346186066_072024-O.webp" alt="Tableta" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Tablet Xiaomi Redmi Pad Se 8gb 256gb Gris</h3>
          <h4>$800.000</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
      </div>
    </section>

    <!-- Sección: Moda -->
    <section id="moda" class="p-6">
      <h2 class="text-2xl font-semibold mb-4">Moda</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="bg-white p-4 rounded shadow product-card" data-name="Camisa básica">
          <img src="https://http2.mlstatic.com/D_NQ_NP_720722-MCO81250388898_122024-O.webp" alt="Camisa básica" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Camisetas X 3 Unidades Blancas Cuello Redondo Algodón Paquete</h3>
  <h4>$60.900</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Zapatillas deportivas">
          <img src="https://exitocol.vteximg.com.br/arquivos/ids/24645021/image-63295cdd4b2c41999e83d9cf11bada33.jpg?v=638618358889600000" alt="Zapatillas deportivas" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Zapatilla Ciclismo Ruta GW PEAK Gris/Verde Talla: 39</h3>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Bolso casual">
          <img src="https://http2.mlstatic.com/D_NQ_NP_805846-MLA83053758036_032025-O.webp" alt="Bolso casual" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Crossover Para Mujer Porta Tablet Totto Logar 2.0 Color Violeta oscuro Diseño de la tela Diseños</h3>
  <h4>$81.000</h4>

          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Pulsera de moda">
          <img src="https://http2.mlstatic.com/D_NQ_NP_762721-MLU78086039145_072024-O.webp" alt="Pulsera de moda" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Pulsera Tejida Azabache Pirita Ojo De Tigre Cuarzo Citrino Piedras Naturales Equilibrio Proteccion</h3>
  <h4>$28.759</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
      </div>
    </section>

    <!-- Sección: Belleza -->
    <section id="belleza" class="p-6">
      <h2 class="text-2xl font-semibold mb-4">Belleza</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="bg-white p-4 rounded shadow product-card" data-name="Crema hidratante">
          <img src="https://http2.mlstatic.com/D_NQ_NP_813264-MLU72567981042_112023-O.webp" alt="Crema hidratante" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Crema Hidratante Hydrance Aqua Gel Avene 50 Ml Tipo de piel Normal</h3>
 <h4>$102.950</h4>

          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Base de maquillaje">
          <img src="https://http2.mlstatic.com/D_NQ_NP_842466-MLU78219438282_082024-O.webp" alt="Base de maquillaje" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Serum con Color True Match Medium 4-5 L'Oreal Paris 30ml</h3>
 <h4>$102.950</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Perfume (50ml)">
          <img src="https://http2.mlstatic.com/D_NQ_NP_929559-MLA80591868886_112024-O.webp" alt="Perfume (50ml)" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Perfume Lattafa Yara Candy Edp 100 Ml</h3>
 <h4>$177.660</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Shampoo nutritivo">
          <img src="https://http2.mlstatic.com/D_NQ_NP_866630-MCO74244287953_012024-O.webp" alt="Shampoo nutritivo" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Shampoo Nutritivo E Hidratante Etniker X 250ml</h3>
 <h4>$27.930</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
      </div>
    </section>

    <!-- Sección: Entretenimiento -->
    <section id="entretenimiento" class="p-6">
      <h2 class="text-2xl font-semibold mb-4">Entretenimiento</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="bg-white p-4 rounded shadow product-card" data-name="Control de videojuegos">
          <img src="https://http2.mlstatic.com/D_NQ_NP_643183-MLU78470820931_082024-O.webp" alt="Control de videojuegos" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Control Para Ps5 Azul Metalizado Cobalt Blue</h3>
 <h4>$300.200</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Juego de mesa">
          <img src="https://http2.mlstatic.com/D_NQ_NP_944693-MLA80591987789_112024-O.webp" alt="Juego de mesa" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Juego De Mesa Basta Interactivo Palabras Agilidad Mental</h3>
 <h4>$60.000</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Apple Pencil 2nd">
          <img src="https://http2.mlstatic.com/D_NQ_NP_740278-MLA78112779147_082024-O.webp" alt="Apple Pencil 2nd" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Apple Pencil Blanco</h3>
 <h4>$599.800</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
      </div>
    </section>

    <!-- Sección: Hogar -->
    <section id="hogar" class="p-6">
      <h2 class="text-2xl font-semibold mb-4">Hogar</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="bg-white p-4 rounded shadow product-card" data-name="Licuadora">
          <img src="https://http2.mlstatic.com/D_NQ_NP_655024-MLU74720986114_032024-O.webp" alt="Licuadora" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Licuadora Oster Xpert Series Roja Con Vaso Personal Rpg Color Rojo</h3>
 <h4>$499.900</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Airfryer">
          <img src="https://www.alkosto.com/medias/6941812776704-001-750Wx750H?context=bWFzdGVyfGltYWdlc3w1OTI0fGltYWdlL3dlYnB8YUROaUwyaGpaUzh4TkRreE1qY3pNREF3TlRVek5DODJPVFF4T0RFeU56YzJOekEwWHpBd01WODNOVEJYZURjMU1FZ3w4MjVjMGI0N2ZmMmNiOGE4YzFlNjQwZTQ3YWM1YzFiZjUyNzM1ODUyODZmYmY0YjZjN2IwMmM4M2E3YWZiNjVi" alt="Airfryer" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Freidora de Aire XIAOMI Essential 6L Blanco</h3>
 <h4>$299.900</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Juego de cucharones">
          <img src="https://http2.mlstatic.com/D_NQ_NP_745956-MCO79075591992_092024-O.webp" alt="Juego de cucharones" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Juego De Cucharones Cocina Cuchillos Tabla Tijera 21 Piezas</h3>
 <h4>$179.900</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
        <div class="bg-white p-4 rounded shadow product-card" data-name="Cuadro decorativo">
          <img src="https://http2.mlstatic.com/D_NQ_NP_642230-MCO79380922258_092024-O.webp" alt="Cuadro decorativo" class="mb-2 w-full h-40 object-cover">
          <h3 class="font-bold">Lienzo Cuadro Atardeceres Otoño Estilo Pintura Al Oleo</h3>
 <h4>$102.950</h4>
          <button class="add-to-cart mt-2 bg-blue-500 text-white px-3 py-1 rounded">Agregar al carrito</button>
        </div>
      </div>
    </section>
  </main>

  <!-- Script para funcionalidad del carrito y búsqueda -->
  <script>
    document.getElementById("searchInput").addEventListener("input", function () {
      const search = this.value.toLowerCase();
      document.querySelectorAll(".product-card").forEach(card => {
        const name = card.getAttribute("data-name").toLowerCase();
        card.style.display = name.includes(search) ? "block" : "none";
      });
    });

    let carrito = [];
    function actualizarCarrito() {
      document.getElementById("carritoCantidad").innerText = carrito.length;
    }

    document.addEventListener("click", function (e) {
      if (e.target.classList.contains("add-to-cart")) {
        const nombreProducto = e.target.closest(".product-card").getAttribute("data-name");
        carrito.push(nombreProducto);
        actualizarCarrito();
      }
    });
  </script>
</body>
</html>
