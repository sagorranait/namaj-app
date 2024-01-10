<script setup>
</script>

<template>
  <div class="home-screen p-4">
    <header>
      <div class="header-area mt-5 flex items-center justify-between">
        <p class="font-medium text-base	">Salat Schedule - Bangladesh</p>
        <img src="../assets/images/setting.svg" alt="setting">
      </div>
    </header>
    <div class="calender mt-6 flex items-center justify-between">
      <div class="date">
        <div class="arabic-date flex items-center gap-3 pb-1">
          <p class="text-base font-normal">8 Jilhazz 1444</p>
          <img class="w-5 h-5" src="../assets/images/up-arrow.svg" alt="up-arrow">
        </div>
        <p class="text-primary text-xs">27 June 2023 | 13 Ashar 1430</p>
      </div>
      <div class="location px-4 py-2 border-2 border-solid border-primary rounded-3xl	">
        <span class="text-sm font-normal">Pabna</span>
      </div>
    </div>
    <div class="next-salat mt-3 px-6 py-4 border-2 border-solid border-primary rounded-lg">
      <label class="text-primary text-base pb-2">Next Salat</label>
      <p class="flex items-center justify-between uppercase text-primary">
        <span class="font-bold text-lg">Tahajjud</span>
        <span class="font-bold text-lg">12:50 am - 03:48 am</span>
      </p>
    </div>
    <div class="social-media mt-3 py-3 px-4 rounded-lg bg-secondary flex items-center justify-between gap-3">
      <img src="../assets/images/logo.svg" alt="social-logo">
      <p class="text-xs text-center">Join our Facebook page to give your original feedback about the app.</p>
      <a href="#">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 text-white">
          <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3" />
        </svg>
      </a>
    </div>
  </div>
</template>