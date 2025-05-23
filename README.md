<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ekonos | Mobiliario Urbano Sostenible</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Encabezado -->
  <header class="bg-green-700 text-white p-6 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">Ekonos</h1>
      <nav>
        <a href="#beneficios" class="mx-4 hover:underline">Beneficios</a>
        <a href="#producto" class="mx-4 hover:underline">Producto</a>
        <a href="#contacto" class="mx-4 hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-white py-12 text-center">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold mb-4">Mobiliario urbano ecológico para un futuro sostenible</h2>
      <p class="mb-6 text-lg">Desde La Ceja, Antioquia, creamos soluciones con materiales reciclados y energía solar.</p>
      <a href="#producto" class="bg-green-600 text-white py-2 px-6 rounded hover:bg-green-700">Conoce nuestro producto</a>
    </div>
  </section>

  <!-- Beneficios -->
  <section id="beneficios" class="bg-gray-100 py-12">
    <div class="container mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-8">¿Por qué elegir Ekonos?</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="text-center">
          <img src="https://img.icons8.com/ios-filled/50/4caf50/recycle.png" class="mx-auto mb-4" alt="Reciclaje" />
          <h4 class="font-bold">Sostenibilidad</h4>
          <p>Usamos madera plástica reciclada y acero reutilizado.</p>
        </div>
        <div class="text-center">
          <img src="https://img.icons8.com/ios-filled/50/4caf50/solar-panel.png" class="mx-auto mb-4" alt="Energía solar" />
          <h4 class="font-bold">Energía solar</h4>
          <p>Incorporamos iluminación LED con energía renovable.</p>
        </div>
        <div class="text-center">
          <img src="https://img.icons8.com/ios-filled/50/4caf50/toolbox.png" class="mx-auto mb-4" alt="Durabilidad" />
          <h4 class="font-bold">Durabilidad</h4>
          <p>Diseñados para resistir el clima y el uso constante.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Producto -->
  <section id="producto" class="py-12">
    <div class="container mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-8">Nuestro Producto</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <img src="https://via.placeholder.com/500x300" alt="Imagen del producto" class="rounded-lg shadow-md">
        <div>
          <h4 class="text-xl font-bold mb-2">Banco modular ecológico</h4>
          <p class="mb-4">Hecho con madera plástica reciclada, tubos de acero recuperados y tecnología de iluminación solar. Ideal para parques, senderos y zonas rurales.</p>
          <ul class="list-disc pl-6">
            <li>Medidas: 180 x 45 x 40 cm</li>
            <li>Peso estimado: 35 kg</li>
            <li>Panel solar integrado con batería de respaldo</li>
            <li>Diseño 100% reciclado y reciclable</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonios -->
  <section class="bg-gray-100 py-12">
    <div class="container mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-8">Lo que dicen nuestros primeros clientes</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <blockquote class="p-6 bg-white rounded shadow">
          <p class="italic">“Nos encantó ver cómo nuestros residuos plásticos pueden convertirse en un banco útil y bonito. ¡Una gran idea local!”</p>
          <footer class="mt-4 text-sm text-right">— Ana, vecina de La Ceja</footer>
        </blockquote>
        <blockquote class="p-6 bg-white rounded shadow">
          <p class="italic">“Es ideal para mi finca, me gusta que no necesita electricidad y da luz por la noche.”</p>
          <footer class="mt-4 text-sm text-right">— Jorge, usuario rural</footer>
        </blockquote>
      </div>
    </div>
  </section>

  <!-- Preguntas Frecuentes -->
  <section class="py-12">
    <div class="container mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-8">Preguntas Frecuentes</h3>
      <div class="space-y-6">
        <div>
          <h4 class="font-semibold">¿De qué materiales está hecho?</h4>
          <p>Madera plástica reciclada, acero reutilizado y componentes solares.</p>
        </div>
        <div>
          <h4 class="font-semibold">¿Dónde puedo instalarlo?</h4>
          <p>En fincas, parques, escuelas rurales y zonas comunes.</p>
        </div>
        <div>
          <h4 class="font-semibold">¿Cuánto cuesta?</h4>
          <p>Desde $850.000 COP, dependiendo de personalización y transporte.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Misión y valores -->
  <section class="bg-green-600 text-white py-12">
    <div class="container mx-auto px-6 text-center">
      <h3 class="text-3xl font-bold mb-4">Nuestra Misión</h3>
      <p class="text-lg">Transformar residuos en soluciones urbanas útiles, sostenibles y con identidad local para el Oriente Antioqueño.</p>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="py-12 bg-gray-50">
    <div class="container mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-8">Contáctanos</h3>
      <form class="max-w-xl mx-auto bg-white p-6 rounded shadow">
        <label class="block mb-2">Nombre</label>
        <input type="text" class="w-full mb-4 p-2 border rounded" required>
        <label class="block mb-2">Correo electrónico</label>
        <input type="email" class="w-full mb-4 p-2 border rounded" required>
        <label class="block mb-2">Mensaje</label>
        <textarea class="w-full mb-4 p-2 border rounded" rows="4"></textarea>
        <button type="submit" class="bg-green-700 text-white py-2 px-4 rounded hover:bg-green-800">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-200 text-center p-4">
    <p>&copy; 2025 Ekonos - La Ceja, Antioquia</p>
  </footer>

</body>
</html>
