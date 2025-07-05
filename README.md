# armatur.tj
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Арматура Душанбе</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/scrollreveal"></script>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-green-800 text-white p-6 shadow-lg">
    <div class="container mx-auto flex flex-col items-center">
      <h1 class="text-4xl font-bold mb-2">Арматура Душанбе</h1>
      <p class="text-lg">Продажа арматуры и металлопроката по низким ценам</p>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative">
    <img src="https://images.unsplash.com/photo-1581091012184-5c46b1747c6c" alt="Арматура" class="w-full h-[400px] object-cover">
    <div class="absolute top-0 left-0 w-full h-full bg-black bg-opacity-50 flex items-center justify-center">
      <h2 class="text-4xl text-white font-bold animate-pulse">Качественная арматура — с доставкой!</h2>
    </div>
  </section>

  <!-- Описание -->
  <section class="py-12 px-6 container mx-auto">
    <h2 class="text-2xl font-semibold mb-4 text-center">Что мы предлагаем</h2>
    <p class="text-center mb-8">У нас вы найдёте все типы арматуры: A3, A500C, гладкая и рифлёная, в наличии и под заказ.</p>

    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white p-4 rounded-xl shadow-md" data-sr>
        <img src="https://images.unsplash.com/photo-1581090700227-4c1b7f1a0a94" class="rounded-lg mb-3" alt="Склад">
        <h3 class="text-lg font-bold mb-2">Большой склад</h3>
        <p>Более 100 тонн арматуры в наличии в Душанбе.</p>
      </div>
      <div class="bg-white p-4 rounded-xl shadow-md" data-sr>
        <img src="https://images.unsplash.com/photo-1581092334021-a6fb3a8cdb66" class="rounded-lg mb-3" alt="Доставка">
        <h3 class="text-lg font-bold mb-2">Доставка</h3>
        <p>Быстрая доставка по городу и регионам Таджикистана.</p>
      </div>
      <div class="bg-white p-4 rounded-xl shadow-md" data-sr>
        <img src="https://images.unsplash.com/photo-1574269918404-9d90b3a9f4c4" class="rounded-lg mb-3" alt="Качество">
        <h3 class="text-lg font-bold mb-2">Гарантия качества</h3>
        <p>Вся арматура сертифицирована и проверена на прочность.</p>
      </div>
    </div>
  </section>

  <!-- Контакты -->
  <section class="bg-green-100 py-10 px-6">
    <div class="container mx-auto text-center">
      <h2 class="text-2xl font-semibold mb-4">Свяжитесь с нами</h2>
      <p class="mb-2">📞 <a href="tel:+992988531832" class="text-green-700 font-bold">+992 988 531 832</a></p>
      <p class="mb-6">📧 <a href="mailto:kholikov@gmail.com" class="text-green-700 font-bold">kholikov@gmail.com</a></p>
      <a href="tel:+992988531832" class="bg-green-700 hover:bg-green-800 text-white px-6 py-3 rounded-xl shadow transition">Позвонить сейчас</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center py-6">
    <p>&copy; 2025 Арматура Душанбе. Все права защищены.</p>
  </footer>

  <script>
    ScrollReveal().reveal('[data-sr]', {
      duration: 1000,
      distance: '40px',
      origin: 'bottom',
      easing: 'ease-in-out',
      interval: 200
    });
  </script>
</body>
</html>
