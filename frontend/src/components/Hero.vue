<template>
<section id="profil" class="relative container mx-auto px-6 py-20 flex flex-col md:flex-row items-center overflow-hidden bg-gradient-to-br from-blue-50 via-white to-blue-100 rounded-3xl shadow-2xl">
  <!-- Animasi partikel dekoratif -->
  <div class="pointer-events-none absolute inset-0 z-0">
    <span class="absolute animate-pulse bg-blue-300 opacity-40 rounded-full blur-2xl" style="width:60px;height:60px;top:10%;left:20%"></span>
    <span class="absolute animate-ping bg-pink-300 opacity-30 rounded-full blur-2xl" style="width:40px;height:40px;top:70%;left:10%"></span>
    <span class="absolute animate-pulse bg-yellow-200 opacity-40 rounded-full blur-2xl" style="width:32px;height:32px;top:60%;right:20%"></span>
    <span class="absolute animate-ping bg-green-200 opacity-30 rounded-full blur-2xl" style="width:48px;height:48px;top:30%;right:10%"></span>
  </div>
  <div class="absolute -top-10 -left-10 w-72 h-72 bg-blue-200 opacity-30 rounded-full blur-3xl z-0"></div>
  <div class="absolute -bottom-16 -right-16 w-96 h-96 bg-blue-400 opacity-20 rounded-full blur-3xl z-0"></div>
  <div class="md:w-1/2 mb-10 md:mb-0 relative z-10">
    <div class="inline-flex items-center mb-4 px-4 py-2 bg-white/80 rounded-full shadow-lg border border-blue-200 gap-2 animate-fade-in">
      <svg class="w-6 h-6 text-blue-500" fill="currentColor" viewBox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>
      <span class="font-semibold text-blue-700">Dhimas</span>
    </div>
    <h1 class="text-5xl font-bold text-gray-800 mb-4 animate-slide-in-left drop-shadow-lg" style="animation-delay:200ms;">
      Halo, Saya <span class="text-blue-600">Dhimas</span>
    </h1>
    <p class="text-xl text-gray-600 mb-8 animate-slide-in-left" style="animation-delay: 400ms;">
      Mahasiswa Teknik Informatika yang bersemangat dalam pengembangan web dan desain antarmuka dan antarpunggung.
    </p>
    <div class="flex space-x-4 mb-8 animate-slide-in-left" style="animation-delay: 500ms;">
      <a href="#" target="_blank" class="text-blue-600 hover:text-blue-800 transition-transform transform hover:-translate-y-1 text-3xl" aria-label="GitHub">
        <svg fill="currentColor" viewBox="0 0 24 24" class="w-8 h-8"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.3 3.438 9.8 8.205 11.387.6.113.82-.263.82-.582 0-.288-.012-1.243-.017-2.252-3.338.726-4.042-1.61-4.042-1.61-.546-1.387-1.333-1.756-1.333-1.756-1.09-.745.083-.729.083-.729 1.205.085 1.84 1.237 1.84 1.237 1.07 1.834 2.807 1.304 3.492.997.108-.775.418-1.305.762-1.606-2.665-.304-5.466-1.332-5.466-5.93 0-1.31.468-2.38 1.236-3.22-.124-.303-.535-1.523.117-3.176 0 0 1.008-.322 3.3 1.23a11.5 11.5 0 0 1 3.003-.404c1.02.005 2.047.138 3.003.404 2.29-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.873.118 3.176.77.84 1.235 1.91 1.235 3.22 0 4.61-2.803 5.624-5.475 5.92.43.37.823 1.102.823 2.222 0 1.606-.015 2.898-.015 3.293 0 .322.218.699.825.58C20.565 21.796 24 17.297 24 12c0-6.63-5.37-12-12-12z"/></svg>
      </a>
      <a href="#" target="_blank" class="text-blue-400 hover:text-blue-600 transition-transform transform hover:-translate-y-1 text-3xl" aria-label="LinkedIn">
        <svg fill="currentColor" viewBox="0 0 24 24" class="w-8 h-8"><path d="M19 0h-14c-2.76 0-5 2.24-5 5v14c0 2.76 2.24 5 5 5h14c2.76 0 5-2.24 5-5v-14c0-2.76-2.24-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.28c-.97 0-1.75-.79-1.75-1.75s.78-1.75 1.75-1.75 1.75.79 1.75 1.75-.78 1.75-1.75 1.75zm15.5 11.28h-3v-5.6c0-1.34-.03-3.07-1.87-3.07-1.87 0-2.16 1.46-2.16 2.97v5.7h-3v-10h2.88v1.36h.04c.4-.75 1.38-1.54 2.84-1.54 3.04 0 3.6 2 3.6 4.59v5.59z"/></svg>
      </a>
    </div>
    <a href="#kontak" class="bg-blue-600 text-white font-bold py-3 px-6 rounded-lg hover:bg-blue-700 transition-colors duration-300 inline-block animate-slide-in-left shadow-lg" style="animation-delay:600ms;">
      Hubungi Saya
    </a>
  </div>
  <div class="md:w-1/2 flex justify-center animate-slide-in-right relative z-10">
    <div class="relative group p-2 bg-gradient-to-tr from-pink-300 via-blue-200 to-yellow-200 rounded-full shadow-xl">
      <span class="absolute inset-0 z-10 pointer-events-none">
        <span class="block w-full h-full rounded-full animate-spin-sinar hero-sinar"></span>
      </span>
      <img src="https://osccdn.medcom.id/images/content/2024/08/04/a11f5e30bf8f4c3f3df0433143408c77.jpg" alt="Kucing Lucu" class="w-80 h-80 rounded-full object-cover shadow-2xl border-8 border-white group-hover:scale-110 transition-transform duration-500 ring-4 ring-blue-200 relative z-20">
      <span class="absolute bottom-4 right-4 bg-blue-600 text-white px-4 py-1 rounded-full text-sm font-semibold shadow-lg animate-bounce z-30">Tersedia untuk Kolaborasi!</span>
    </div>
  </div>
</section>
</template>
