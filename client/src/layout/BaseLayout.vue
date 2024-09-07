<template>
  <div class="max-w-[430px] mx-auto h-screen bg-red-500">
    <div class="relative h-full flex flex-col p-4">
      <NavBar />
      <slot></slot>
     <AppFooter />
    </div>
  </div>
</template>

<script>
import { NavBar, AppFooter } from '@/components';

export default {
  components: { NavBar, AppFooter }
}
</script>