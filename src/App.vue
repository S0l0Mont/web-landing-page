<script setup>
  import ButtonVue from './components/Button.vue';
</script>

<style>
.speed-150ms {
  animation-delay: 150ms;
}

.speed-300ms {
  animation-delay: 300ms;
}

.speed-450ms {
  animation-delay: 450ms;
}
</style>

<template>
  <div class="flex h-screen justify-center items-center bg-gray-800">
    <div class="text-center">
      <h1 class="text-6xl font-bold text-white animate__animated animate__fadeInDown">THIS IS A WONG</h1>
      <div class="flex justify-center m-3 text-white animate__animated animate__fadeInDown">
        <h2 class="mx-3 animate__animated animate__fadeIn speed-150ms">Coffee ☕</h2> <i class="fa-solid fa-slash-forward flex items-center"></i>
        <h2 class="mx-3 animate__animated animate__fadeIn speed-300ms">Leetcode 📃</h2> <i class="fa-solid fa-slash-forward flex items-center"></i>
        <h2 class="mx-3 animate__animated animate__fadeIn speed-450ms">Codeforces 💻</h2>
      </div>
      <div class="grid gap-4 grid-cols-1 grid-rows-12 md:grid-cols-3 animate__animated animate__fadeInDown">
        <ButtonVue url="https://github.com/S0l0Mont">
          <i class="fab fa-github mr-3"></i> 
          GitHub
        </ButtonVue>
        <ButtonVue url="https://www.youtube.com/channel/UCLvTyyE9i0xvVGxCt7X716A">
          <i class="fab fa-youtube mr-3"></i> 
          YouTube
        </ButtonVue>
        <ButtonVue url="mailto:wong@thisisawong.wang">
          <i class="fas fa-envelope mr-3"></i> 
          E-mail
        </ButtonVue>        
      </div>
      <div class="text-white my-5 animate__animated animate__fadeIn ">
        Made with 😂 by <a href="https://m307.dev">M-307</a>
      </div>
    </div>
  </div>
</template>