<template>
  <div>
    <a href="https://www.electronjs.org/" target="_blank" class="flex-center">
      <img
        src="./assets/electron.svg"
        class="logo electron"
        alt="Electron logo"
      />
    </a>

    <a href="https://vitejs.dev/" target="_blank" class="flex-center">
      <img src="./assets/vite.svg" class="logo" alt="Vite logo" />
    </a>

    <a href="https://vuejs.org/" target="_blank" class="flex-center">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>

  <HelloWorld msg="Electron + Vite + Vue + TailwindCSS" />

  <div class="flex-center">
    Place static files into the <code>/public</code> folder
    <img style="width: 2.4em; margin-left: 0.4em" src="/logo.svg" alt="Logo" />
  </div>
</template>

<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
</script>

<style>
.flex-center {
  display: flex;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo.electron:hover {
  filter: drop-shadow(0 0 2em #9feaf9);
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
