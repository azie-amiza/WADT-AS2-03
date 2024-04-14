<!-- <script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(10)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style> -->

<!-- <template>
  <div class="relative isolate overflow-hidden bg-gray-900 py-24 sm:py-32">
    <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&crop=focalpoint&fp-y=.8&w=2830&h=1500&q=80&blend=111827&sat=-100&exp=15&blend-mode=multiply" alt="" class="absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center" />
    <div class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl" aria-hidden="true">
      <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
    </div>
    <div class="absolute -top-52 left-1/2 -z-10 -translate-x-1/2 transform-gpu blur-3xl sm:top-[-28rem] sm:ml-16 sm:translate-x-0 sm:transform-gpu" aria-hidden="true">
      <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
    </div>
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Work with us</h2>
        <p class="mt-6 text-lg leading-8 text-gray-300">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
      </div>
      <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
        <div class="grid grid-cols-1 gap-x-8 gap-y-6 text-base font-semibold leading-7 text-white sm:grid-cols-2 md:flex lg:gap-x-10">
          <a v-for="link in links" :key="link.name" :href="link.href">{{ link.name }} <span aria-hidden="true">&rarr;</span></a>
        </div>
        <dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4">
          <div v-for="stat in stats" :key="stat.name" class="flex flex-col-reverse">
            <dt class="text-base leading-7 text-gray-300">{{ stat.name }}</dt>
            <dd class="text-2xl font-bold leading-9 tracking-tight text-white">{{ stat.value }}</dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>

<script setup>
const links = [
  { name: 'Open Roles', href: '#'},
  { name: 'Internship Program', href: '#'},
  { name: 'Our values', href: '#'},
  { name: 'Meet our leadership', href: '#'},
]
const stats = [
  { name: 'Offices worldwide', href: '#'},
  { name: 'Full-time colleagues', href: '#'},
  { name: 'Hours per week', href: '#'},
  { name: 'Paid time off', href: '#'},
]
</script> -->

<!-- <template>
  <div>
    <nav class="bg-gray-800 py-4">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center">
        <div>
          <a href="#" class="text-white font-bold text-xl">Your Name</a>
        </div>
        <div>
          <a href="#" class="text-white hover:text-gray-400 px-3 py-2">About</a>
          <a href="#" class="text-white hover:text-gray-400 px-3 py-2">Portfolio</a>
          <a href="#" class="text-white hover:text-gray-400 px-3 py-2">Contact</a>
        </div>
      </div>
    </nav>

    <header class="bg-gray-900 h-screen flex items-center justify-center text-white">
      <div class="text-center">
        <h1 class="text-5xl font-bold">Hello, I'm Your Name</h1>
        <p class="mt-4 text-lg">Welcome to my website</p>
      </div>
    </header>

    <section class="py-16">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold mb-6">About Me</h2>
        <p class="text-lg leading-relaxed">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.</p>
      </div>
    </section>

    <footer class="bg-gray-800 py-8 text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
/* This empty style block is required to process Tailwind CSS classes */
</style> -->


<template>
  <div class="min-h-screen">
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

    <header class="bg-gray-900 h-screen flex items-center justify-center text-white">
      <div class="text-center">
        <h1 class="text-5xl font-bold">Hello, I'm Azie Amiza</h1>
        <p class="mt-4 text-lg">Welcome to my website</p>
      </div>
    </header>

    <section class="py-16">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold mb-6">About Me</h2>
        <p class="text-lg leading-relaxed">I am a student from Politeknik Brunei taking Web Development Course with the School ID (22FTT1497), and this is where I made a website of myself for the assignment and future use.</p>
      </div>
    </section>

    <footer class="bg-gray-800 py-8 text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
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
/* This empty style block is required to process Tailwind CSS classes */
</style>
