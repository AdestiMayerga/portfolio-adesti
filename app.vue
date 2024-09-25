<template>
  <div class="container mx-auto p-4 md:p-8">
    <!-- Profile Card Container -->
    <div class="bg-pink-100 shadow-lg rounded-lg p-4 md:p-6 flex flex-col md:flex-row hover:shadow-2xl transition duration-300 ease-in-out">
      
      <!-- Left Side: Profile Picture -->
      <div class="md:w-1/3 flex justify-center md:justify-start mb-4 md:mb-0">
        <img src="@/assets/image.png" alt="Profile Photo" class="rounded-lg w-32 h-32 md:w-48 md:h-48 object-cover transform hover:scale-105 transition duration-300 ease-in-out" />
      </div>

      <!-- Right Side: Profile Info -->
      <div class="md:w-2/3 md:ml-8 mt-4 md:mt-0 flex flex-col justify-between">
        
        <!-- Name and Job Title -->
        <div>
          <h1 class="text-2xl md:text-4xl font-bold text-pink-800">Adesti Mayerga</h1>
          <p class="text-md md:text-lg text-pink-500">Teknologi Informasi - 2023</p>
        </div>

        <!-- Profile Section -->
        <div class="mt-4">
          <h2 class="font-bold text-lg md:text-xl text-pink-700">Profil</h2>
          <p class="text-gray-600 mt-2 text-sm md:text-base">
            Saya sedang menempuh program studi Teknologi Informasi 2023, saya sedang mencari pekerjaan yang berhubungan dengan aplikasi android, saya ingin merasakan bekerja dengan orang yang sudah sangat ahli dalam pemrograman.
          </p>
        </div>

        <!-- Education Section -->
        <div class="mt-4">
          <h2 class="font-bold text-lg md:text-xl text-pink-700">Edukasi</h2>
          <p class="text-gray-600 mt-2 text-sm md:text-base">Universitas Brawijaya</p>
          <p class="text-gray-500 text-sm md:text-base">D3 Teknologi Informasi (2023)</p>
        </div>

        <!-- Experience Section -->
        <div class="mt-4">
          <h2 class="font-bold text-lg md:text-xl text-pink-700">Pengalaman</h2>
          <ul class="mt-2">
            <li class="hover:bg-pink-200 rounded-lg p-2 transition duration-300 ease-in-out">
              <p class="font-semibold text-gray-600 text-sm md:text-base">Apotek Sehat Farma</p>
              <p class="text-gray-500 text-xs md:text-sm">Admin (2022)</p>
            </li>
          </ul>
        </div>

        <!-- Contact Info Section -->
        <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="hover:text-pink-600 transition duration-300 ease-in-out">
            <p class="font-bold text-gray-700">Telepon</p>
            <p class="text-gray-500 text-sm md:text-base">0821-2245-1234</p>
          </div>
          <div class="hover:text-pink-600 transition duration-300 ease-in-out">
            <p class="font-bold text-gray-700">Email</p>
            <p class="text-gray-500 text-sm md:text-base">adestimayerga97@gmail.com</p>
          </div>
          <div class="hover:text-pink-600 transition duration-300 ease-in-out">
            <p class="font-bold text-gray-700">Alamat</p>
            <p class="text-gray-500 text-sm md:text-base">Jl. Bandulan 08</p>
          </div>
        </div>

        <!-- Languages Section -->
        <div class="mt-4">
          <h2 class="font-bold text-lg md:text-xl text-pink-700">Bahasa</h2>
          <p class="text-gray-500 text-sm md:text-base">Inggris, Indonesia, Jawa</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// No additional scripts required for this static design.
</script>

<style scoped>
/* Add any custom CSS if needed */
</style>
