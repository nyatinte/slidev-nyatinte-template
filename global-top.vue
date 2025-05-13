<template>
  <footer v-if="$slidev.nav.currentLayout !== 'cover'" class="absolute bottom-0 right-0 p-4 text-3xl">
    {{ $slidev.nav.currentPage }}
  </footer>
</template>