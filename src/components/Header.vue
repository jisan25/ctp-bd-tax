<template>
  <header class="flex items-center justify-between py-4 app-container bg-white shadow-md">
    <!-- Logo -->
    <div class="flex items-center space-x-2">
      <div class="w-8 h-8 bg-primary rounded-full flex items-center justify-center">
        <div class="w-4 h-4 bg-secondary rounded-full"></div>
      </div>
    </div>

    <!-- Navigation Links -->
    <nav class="flex space-x-8">
      <a href="#" class="text-primary text-md font-medium hover:text-primary-800">Home</a>
      <a href="#" class="text-gray-900 font-medium text-md hover:text-primary">About</a>
      <a href="#" class="text-gray-900 font-medium text-md hover:text-primary">Pricing</a>
      <a href="#" class="text-gray-900 font-medium text-md hover:text-primary">Services</a>
      <a href="#" class="text-gray-900 font-medium text-md hover:text-primary">Knowledge</a>
      <a href="#" class="text-gray-900 font-medium text-md hover:text-primary">Contact</a>
    </nav>

    <!-- Right Side (Contact Info & Buttons) -->
    <div class="flex items-center space-x-4">
      <!-- Contact Information -->
      <div class="flex items-center space-x-2">
        <div class="w-10 h-10 flex items-center justify-center bg-green-100 rounded-full">
          <a href="mailto:example@example.com" class="text-gray-900"
            ><i class="fa fa-envelope-o text-xl"></i
          ></a>
        </div>
        <a href="tel:02039605080" class="text-gray-900 font-medium">020 3960 5080</a>
      </div>

      <!-- Callback Button -->
      <button
        class="px-4 py-2 border-2 border-primary font-medium text-primary rounded-lg hover:bg-green-100 hover:text-black"
      >
        Callback
      </button>

      <!-- Buy Now Dropdown -->
      <div class="relative">
        <button
          class="px-4 py-2 font-medium bg-primary text-white rounded-lg hover:bg-green-600 flex items-center space-x-1"
        >
          <span>Buy Now</span>
        </button>
        <!-- Dropdown Menu (Hidden by default, shown on click) -->
        <!-- Add dropdown functionality here -->
      </div>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style></style>
