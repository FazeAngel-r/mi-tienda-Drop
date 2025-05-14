# mi-tienda-Drop
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tienda Flash</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800 font-sans">

  <!-- Encabezado -->
  <header class="bg-gradient-to-r from-blue-600 to-purple-600 text-white p-6">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">Tienda Flash</h1>
      <nav class="space-x-6">
        <a href="#productos" class="hover:underline">Productos</a>
        <a href="#beneficios" class="hover:underline">Beneficios</a>
        <a href="#testimonios" class="hover:underline">Opiniones</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="text-center py-20 bg-gray-100">
    <h2 class="text-4xl font-bold mb-4">Encuentra lo último en tendencias, ¡con envío gratis!</h2>
    <p class="text-lg mb-8">Productos únicos, precios irresistibles.</p>
    <a href="#productos" class="bg-blue-600 text-white px-6 py-3 rounded-full hover:bg-blue-700 transition">Ver productos</a>
  </section>

  <!-- Productos -->
  <section id="productos" class="max-w-6xl mx-auto py-16">
    <h3 class="text-2xl font-bold text-center mb-10">Productos Destacados</h3>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
      <!-- Producto 1 -->
      <div class="border rounded-xl shadow-lg overflow-hidden">
        <img src="https://via.placeholder.com/300x200" alt="Producto 1" class="w-full">
        <div class="p-4">
          <h4 class="text-lg font-semibold mb-2">Reloj Minimalista</h4>
          <p class="text-gray-600 mb-2">Elegante y moderno.</p>
          <p class="font-bold text-blue-600 mb-4">$29.99</p>
          <button class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700 w-full">Agregar al carrito</button>
        </div>
      </div>

      <!-- Puedes duplicar más productos similares -->
    </div>
  </section>

  <!-- Beneficios -->
  <section id="beneficios" class="bg-blue-50 py-16">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-2xl font-bold mb-6">¿Por qué elegirnos?</h3>
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
        <div>
          <h4 class="text-blue-600 font-semibold text-lg">Envío Gratis</h4>
          <p>En todos los pedidos sin mínimo de compra.</p>
        </div>
        <div>
          <h4 class="text-blue-600 font-semibold text-lg">Pago Seguro</h4>
          <p>Protegemos tus datos con cifrado SSL.</p>
        </div>
        <div>
          <h4 class="text-blue-600 font-semibold text-lg">Soporte 24/7</h4>
          <p>Siempre listos para ayudarte.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonios -->
  <section id="testimonios" class="py-16 bg-gray-100">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-2xl font-bold mb-10">Lo que dicen nuestros clientes</h3>
      <div class="space-y-6">
        <blockquote class="italic">“Excelente calidad y envío rápido. ¡Volveré a comprar sin duda!” – <strong>Laura G.</strong></blockquote>
        <blockquote class="italic">“Gran atención al cliente y productos muy originales.” – <strong>Carlos M.</strong></blockquote>
      </div>
    </div>
  </section>

  <!-- CTA final -->
  <section class="text-center py-12 bg-purple-600 text-white">
    <h3 class="text-2xl font-bold mb-4">¡Aprovecha nuestras ofertas por tiempo limitado!</h3>
    <a href="#productos" class="bg-white text-purple-600 px-6 py-3 rounded-full font-semibold hover:bg-gray-100">Ir a tienda</a>
  </section>

  <!-- Pie de página -->
  <footer class="bg-gray-800 text-white text-center py-4">
    <p>&copy; 2025 Tienda Flash - Todos los derechos reservados.</p>
  </footer>

</body>
</html>
