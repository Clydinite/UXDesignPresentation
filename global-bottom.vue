<!-- an example footer for pages -->
<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute bottom-0 right-1 p-2 text-sm text-gray-500"
  >
    {{ $nav.currentPage }}
  </footer>
</template>