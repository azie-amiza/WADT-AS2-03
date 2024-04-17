<template>
  <div class="min-h-screen">

    <!-- navigation -->
    <nav class="bg-gray-800 py-4">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center">
        <div>
          <a href="#" class="text-white font-bold text-xl">Azie Amiza</a>
        </div>
        <div class="hidden sm:block">
          <a href="#" class="text-white hover:text-gray-400 px-3 py-2">About</a>
          <a href="#" class="text-white hover:text-gray-400 px-3 py-2">Portfolio</a>
          <a href="#" class="text-white hover:text-gray-400 px-3 py-2">Contact</a>
        </div>
        <div class="sm:hidden">
          <button @click="toggleMenu" class="text-white hover:text-gray-400 px-3 py-2 focus:outline-none">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
            </svg>
          </button>
        </div>
      </div>
      <div :class="{'block': isMenuOpen, 'hidden': !isMenuOpen}" class="sm:hidden">
        <a href="#" class="text-white hover:text-gray-400 block px-3 py-2">About</a>
        <a href="#" class="text-white hover:text-gray-400 block px-3 py-2">Portfolio</a>
        <a href="#" class="text-white hover:text-gray-400 block px-3 py-2">Contact</a>
      </div>
    </nav>


    <!-- header -->
    <header class="bg-gray-900 h-screen flex items-center justify-center text-white">
      <div class="text-center">
        <h1 class="text-5xl font-bold">Hello, I'm Azie Amiza</h1>
        <p class="mt-4 text-lg">Welcome to my website</p>
      </div>
    </header>

    <!-- about me -->
    <section class="py-16">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold mb-6">About Me</h2>
        <div class="flex justify-center items-center mb-6">
          <img src="/images/myself2-optimized.jpg" alt="Azie Amiza" class="w-64 h-auto object-scale-down" />
        </div>
        <p class="text-lg leading-relaxed">Hello! My name is Azie Amiza-22FTT1497, and I'm currently pursuing a diploma in Web Development at Politeknik Brunei. I have a passion for creating beautiful and functional websites, and I'm constantly learning and exploring new technologies in the field of web development. This portfolio showcases some of my projects and assignments, and I hope you enjoy exploring my work!</p>
      </div>
    </section>

    <!-- footer -->
    <footer class="bg-gray-800 py-8 text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <p>&copy; 2024 Azie Amiza. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      isMenuOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }
}
</script>

<style>

/* img{
  width: 10rem;
  height: 10rem;
} */
</style>
