# E-commerce-products-
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tea Bliss - E-commerce</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-green-50">
  <!-- Navbar -->
  <header class="bg-green-700 text-white p-4 flex justify-between items-center">
    <h1 class="text-xl font-bold">Tea Bliss</h1>
    <nav>
      <input type="text" placeholder="Search tea..." class="p-1 rounded text-black" />
      <button class="ml-4">Cart (0)</button>
    </nav>
  </header>

  <!-- Product Table -->
  <section class="p-6">
    <h2 class="text-2xl font-bold mb-4">Our Teas</h2>
    <table class="w-full table-auto border-collapse">
      <thead>
        <tr class="bg-green-100">
          <th class="border px-4 py-2">Product</th>
          <th class="border px-4 py-2">Description</th>
          <th class="border px-4 py-2">Price</th>
          <th class="border px-4 py-2">Action</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="border px-4 py-2">Green Tea</td>
          <td class="border px-4 py-2">Organic loose leaf green tea</td>
          <td class="border px-4 py-2">Ksh.1650</td>
          <td class="border px-4 py-2"><button class="bg-green-600 text-white px-3 py-1 rounded">Add to Cart</button></td>
        </tr>
        <tr>
          <td class="border px-4 py-2">Black Tea</td>
          <td class="border px-4 py-2">Bold and full-bodied black tea</td>
          <td class="border px-4 py-2">Ksh 1050</td>
          <td class="border px-4 py-2"><button class="bg-green-600 text-white px-3 py-1 rounded">Add to Cart</button></td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Customer Registration Form -->
  <section class="p-6 bg-white max-w-md mx-auto rounded shadow mt-8">
    <h2 class="text-xl font-bold mb-4">Customer Registration</h2>
    <form class="space-y-4">
      <div>
        <label class="block">Full Name</label>
        <input type="text" class="w-full border px-3 py-2 rounded" required />
      </div>
      <div>
        <label class="block">Email</label>
        <input type="email" class="w-full border px-3 py-2 rounded" required />
      </div>
      <div>
        <label class="block">Password</label>
        <input type="password" class="w-full border px-3 py-2 rounded" required />
      </div>
      <div>
        <button type="submit" class="bg-green-700 text-white px-4 py-2 rounded">Register</button>
      </div>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-green-700 text-white text-center p-4 mt-10">
    &copy; 2025 Tea Bliss. All rights reserved.
  </footer>
</body>
</html>


