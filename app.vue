<template>
  <div>
    <NuxtPage />
  </div>
</template>
<style>
@font-face {
  font-family: 'neopixel';
  src: url('/assets/font/NEOPIXEL-Regular.otf') format('opentype');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

html {
  font-family: 'neopixel';
}


.main-container {
  @apply box-border flex w-full justify-center overflow-x-hidden px-4 lg:px-[60px];
}

.max-container {
  @apply w-full max-w-[1800px];
}
</style>