<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Red Social de Trabajo Social</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900">
  <!-- Navbar -->
  <header class="bg-white shadow">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">Trabajadores Sociales</h1>
      <nav class="space-x-4">
        <a href="#buscar" class="text-gray-700 hover:text-blue-600">Buscar</a>
        <a href="#login" class="text-gray-700 hover:text-blue-600">Login</a>
        <a href="#registro" class="text-gray-700 hover:text-blue-600">Registro</a>
        <a href="#blog" class="text-gray-700 hover:text-blue-600">Blog</a>
        <a href="#contacto" class="text-gray-700 hover:text-blue-600">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero section -->
  <section class="bg-blue-50 py-20">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl font-bold mb-4">Conecta con profesionales del trabajo social</h2>
      <p class="mb-8 text-lg text-gray-600">Encuentra trabajadores sociales por área de especialización, ubicación o necesidad específica.</p>
      <a href="#buscar" class="bg-blue-600 text-white px-6 py-3 rounded-lg text-lg hover:bg-blue-700">Buscar profesionales</a>
    </div>
  </section>

  <!-- Página de Búsqueda de Profesionales -->
  <section id="buscar" class="py-16 bg-white">
    <div class="container mx-auto px-6">
      <h3 class="text-2xl font-bold mb-6">Buscar profesionales</h3>
      <form class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-8">
        <input type="text" placeholder="Nombre o palabra clave" class="border p-2 rounded">
        <select class="border p-2 rounded">
          <option value="">Área de trabajo</option>
          <option value="salud">Salud</option>
          <option value="educacion">Educación</option>
          <option value="comunidad">Comunidad</option>
        </select>
        <input type="text" placeholder="Ciudad o región" class="border p-2 rounded">
        <button type="submit" class="md:col-span-3 bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Buscar</button>
      </form>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-gray-100 p-4 rounded shadow">
          <h4 class="text-lg font-semibold">María González</h4>
          <p class="text-sm text-gray-600">Área: Salud</p>
          <p class="text-sm text-gray-600">Ubicación: Santiago</p>
          <a href="#perfil-maria" class="text-blue-600 hover:underline text-sm">Ver perfil</a>
        </div>
        <div class="bg-gray-100 p-4 rounded shadow">
          <h4 class="text-lg font-semibold">Carlos Pérez</h4>
          <p class="text-sm text-gray-600">Área: Educación</p>
          <p class="text-sm text-gray-600">Ubicación: Valparaíso</p>
          <a href="#perfil-carlos" class="text-blue-600 hover:underline text-sm">Ver perfil</a>
        </div>
        <div class="bg-gray-100 p-4 rounded shadow">
          <h4 class="text-lg font-semibold">Laura Díaz</h4>
          <p class="text-sm text-gray-600">Área: Comunidad</p>
          <p class="text-sm text-gray-600">Ubicación: Concepción</p>
          <a href="#perfil-laura" class="text-blue-600 hover:underline text-sm">Ver perfil</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Perfiles Individuales -->
  <section id="perfil-maria" class="py-16 bg-gray-50">
    <div class="container mx-auto px-6 max-w-3xl">
      <div class="bg-white p-6 rounded shadow">
        <h3 class="text-2xl font-bold mb-4">María González</h3>
        <p class="mb-2 text-gray-700">👩‍⚕️ <strong>Especialidad:</strong> Salud</p>
        <p class="mb-2 text-gray-700">📍 <strong>Ubicación:</strong> Santiago, Chile</p>
        <p class="mb-4 text-gray-700">📝 <strong>Biografía:</strong> Profesional con más de 10 años de experiencia en el ámbito de la salud pública. Comprometida con el bienestar integral de las comunidades vulnerables.</p>
        <a href="mailto:maria.gonzalez@email.com" class="inline-block bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Contactar</a>
      </div>
    </div>
  </section>
  <section id="perfil-carlos" class="py-16 bg-gray-50">
    <div class="container mx-auto px-6 max-w-3xl">
      <div class="bg-white p-6 rounded shadow">
        <h3 class="text-2xl font-bold mb-4">Carlos Pérez</h3>
        <p class="mb-2 text-gray-700">👨‍🏫 <strong>Especialidad:</strong> Educación</p>
        <p class="mb-2 text-gray-700">📍 <strong>Ubicación:</strong> Valparaíso, Chile</p>
        <p class="mb-4 text-gray-700">📝 <strong>Biografía:</strong> Educador social con amplia experiencia en programas de reinserción escolar y prevención de deserción en jóvenes. Enfocado en el desarrollo de habilidades sociales y emocionales.</p>
        <a href="mailto:carlos.perez@email.com" class="inline-block bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Contactar</a>
      </div>
    </div>
  </section>
  <section id="perfil-laura" class="py-16 bg-gray-50">
    <div class="container mx-auto px-6 max-w-3xl">
      <div class="bg-white p-6 rounded shadow">
        <h3 class="text-2xl font-bold mb-4">Laura Díaz</h3>
        <p class="mb-2 text-gray-700">👩‍💼 <strong>Especialidad:</strong> Comunidad</p>
        <p class="mb-2 text-gray-700">📍 <strong>Ubicación:</strong> Concepción, Chile</p>
        <p class="mb-4 text-gray-700">📝 <strong>Biografía:</strong> Líder comunitaria con experiencia en desarrollo territorial y fortalecimiento de organizaciones sociales. Especialista en participación ciudadana y gestión de proyectos comunitarios.</p>
        <a href="mailto:laura.diaz@email.com" class="inline-block bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Contactar</a>
      </div>
    </div>
  </section>

  <!-- Login -->
  <section id="login" class="py-16 bg-white">
    <div class="container mx-auto px-6 max-w-md">
      <div class="bg-gray-100 p-6 rounded shadow">
        <h2 class="text-2xl font-bold mb-6 text-center">Iniciar Sesión</h2>
        <form class="space-y-4">
          <input type="email" placeholder="Correo electrónico" class="w-full p-2 border rounded">
          <input type="password" placeholder="Contraseña" class="w-full p-2 border rounded">
          <button class="w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Entrar</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Registro -->
  <section id="registro" class="py-16 bg-gray-50">
    <div class="container mx-auto px-6 max-w-md">
      <div class="bg-white p-6 rounded shadow">
        <h2 class="text-2xl font-bold mb-6 text-center">Crear Cuenta</h2>
        <form class="space-y-4">
          <input type="text" placeholder="Nombre completo" class="w-full p-2 border rounded">
          <input type="email" placeholder="Correo electrónico" class="w-full p-2 border rounded">
          <input type="password" placeholder="Contraseña" class="w-full p-2 border rounded">
          <select class="w-full p-2 border rounded">
            <option>Selecciona tu especialidad</option>
            <option value="salud">Salud</option>
            <option value="educacion">Educación</option>
            <option value="comunidad">Comunidad</option>
          </select>
          <button class="w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Registrarse</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white mt-20 shadow-inner">
    <div class="container mx-auto px-6 py-4 text-center text-gray-600">
      &copy; 2025 Red de Trabajadores Sociales. Todos los derechos reservados.
    </div>
  </footer>
</body>
</html>
