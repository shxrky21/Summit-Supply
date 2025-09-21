<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Summit Supply</title>
  <link rel="icon" type="image/x-icon" href="/static/favicon.ico" />
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
  <style>
    html { scroll-behavior: smooth; }
    .section { scroll-margin-top: 70px; }
    .btn-primary {
      background: linear-gradient(to right, #4facfe 0%, #00f2fe 100%);
      transition: all 0.3s ease;
    }
    .btn-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    }
    .card { transition: all 0.3s ease; }
  </style>
</head>
<body class="font-sans antialiased">

  <!-- Navigation -->
  <nav class="bg-white shadow-sm fixed w-full top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between h-16">
        <div class="flex">
          <div class="flex-shrink-0 flex items-center">
            <span class="text-xl font-bold text-blue-600">Summit Supply</span>
          </div>
          <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
            <a href="#home" class="nav-link text-gray-500 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Home</a>
            <a href="#shop" class="nav-link text-gray-500 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Shop</a>
            <a href="#reviews" class="nav-link text-gray-500 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Reviews</a>
            <a href="#contact" class="nav-link text-gray-500 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Contact</a>
          </div>
        </div>
        <div class="hidden sm:ml-6 sm:flex sm:items-center">
          <button class="bg-white p-1 rounded-full text-gray-400 hover:text-gray-500 focus:outline-none">
            <i data-feather="shopping-cart"></i>
          </button>
        </div>
        <div class="-mr-2 flex items-center sm:hidden">
          <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none" id="mobile-menu-button">
            <i data-feather="menu"></i>
          </button>
        </div>
      </div>
    </div>
    <!-- Mobile menu -->
    <div class="sm:hidden hidden" id="mobile-menu">
      <div class="pt-2 pb-3 space-y-1">
        <a href="#home" class="block pl-3 pr-4 py-2 text-base font-medium">Home</a>
        <a href="#shop" class="block pl-3 pr-4 py-2 text-base font-medium">Shop</a>
        <a href="#reviews" class="block pl-3 pr-4 py-2 text-base font-medium">Reviews</a>
        <a href="#contact" class="block pl-3 pr-4 py-2 text-base font-medium">Contact</a>
      </div>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="section bg-gray-50 pt-24 pb-16">
    <div class="max-w-7xl mx-auto px-4 text-center">
      <h1 class="text-4xl font-extrabold text-gray-900" data-aos="fade-up">Welcome to Summit Supply</h1>
      <p class="mt-4 text-lg text-gray-600" data-aos="fade-up" data-aos-delay="100">Premium outdoor gear for your next adventure.</p>
      <a href="#shop" class="mt-6 inline-block px-6 py-3 text-white font-medium rounded-lg btn-primary">Shop Now</a>
    </div>
  </section>

  <!-- Shop Section -->
  <section id="shop" class="section bg-white py-16">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-gray-900 mb-8" data-aos="fade-right">Our Products</h2>
      <div class="grid grid-cols-1 gap-y-10 sm:grid-cols-2 gap-x-6 lg:grid-cols-3 xl:grid-cols-4 xl:gap-x-8">
        <!-- Example Product -->
        <div class="card bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
          <img src="http://static.photos/outdoor/640x360/1" alt="Alpine Backpack" class="rounded-lg w-full h-48 object-cover" />
          <h3 class="mt-4 text-lg font-medium text-gray-900">Alpine Backpack 45L</h3>
          <p class="mt-1 text-sm text-gray-700">Lightweight yet durable backpack</p>
          <div class="mt-4 flex justify-between items-center">
            <p class="text-lg font-semibold text-gray-900">$129.99</p>
            <button class="px-3 py-1 bg-blue-50 text-blue-600 text-sm rounded-full hover:bg-blue-100">Add to cart</button>
          </div>
        </div>
        <!-- You can copy more products here from your shop file -->
      </div>
    </div>
  </section>

  <!-- Reviews Section -->
  <section id="reviews" class="section bg-gray-50 py-16">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-gray-900 mb-8" data-aos="fade-right">Customer Reviews</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Example Review -->
        <div class="card bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
          <div class="flex items-center mb-4">
            <img src="http://static.photos/people/200x200/1" class="w-10 h-10 rounded-full mr-4" alt="Sarah J" />
            <div>
              <h3 class="font-medium text-gray-900">Sarah J.</h3>
              <div class="flex text-yellow-400">
                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                <i data-feather="star" class="w-4 h-4 fill-current"></i>
              </div>
            </div>
          </div>
          <p class="text-gray-600">"The Alpine Backpack exceeded my expectations!"</p>
        </div>
        <!-- Copy more reviews here from your reviews file -->
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section bg-white py-16">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-gray-900 mb-8" data-aos="fade-right">Contact Us</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="card bg-white p-6 rounded-lg shadow-md" data-aos="fade-up">
          <i data-feather="mail" class="text-blue-500"></i>
          <h3 class="mt-4 text-lg font-medium text-gray-900">Email Us</h3>
          <p class="text-gray-500">teamsummitsupply@gmail.com</p>
        </div>
        <div class="card bg-white p-6 rounded-lg shadow-md" data-aos="fade-up" data-aos-delay="100">
          <i data-feather="message-circle" class="text-indigo-500"></i>
          <h3 class="mt-4 text-lg font-medium text-gray-900">Join Our Discord</h3>
          <p class="text-gray-500"><a href="https://discord.gg/UbSgA86ddC" target="_blank">Click here</a></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-50 py-8">
    <div class="max-w-7xl mx-auto text-center text-gray-500">
      <p>&copy; 2023 Summit Supply. All rights reserved.</p>
    </div>
  </footer>

  <script>
    // Mobile menu toggle
    document.getElementById('mobile-menu-button').addEventListener('click', function() {
      const menu = document.getElementById('mobile-menu');
      menu.classList.toggle('hidden');
    });

    // Init AOS + Feather icons
    document.addEventListener('DOMContentLoaded', function() {
      AOS.init({ duration: 800, easing: 'ease-in-out', once: true });
      feather.replace();
    });
  </script>
</body>
</html>
