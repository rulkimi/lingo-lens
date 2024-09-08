<template>
  <div class="max-w-[430px] mx-auto h-screen bg-red-500">
    <div class="relative h-full">
      <NavBar />
      <div class="flex flex-col p-4">
        <slot></slot>
      </div>
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