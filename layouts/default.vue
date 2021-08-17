<template>
  <transition name="layouts" mode="out-in">
    <Nuxt />
  </transition>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@200;300;400;500;700;800;900&display=swap');

* {
  font-family: 'Tajawal', sans-serif !important;
}

.page-enter-active,
.page-leave-active {
  transition: all 0.3s ease-out;
}
.page-enter,
.page-leave-active {
  opacity: 0;
  transform-origin: 50% 50%;
}
</style>
