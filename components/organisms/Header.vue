<template>
  <header>
    <nav class="container flex items-start py-4 mt-4 sm:mt-12">
      <div class="py-1"><img src="@/assets/img/logo-bookmark.svg" alt="" /></div>
      <ul
        class="hidden sm:flex flex-1 justify-end items-center gap-12 text-bookmark-blue uppercase text-xs"
      >
        <li class="cursor-pointer">Features</li>
        <li class="cursor-pointer">Pricing</li>
        <li class="cursor-pointer">Contact</li>
        <Button variant="accent">Login</Button>
      </ul>
      <div class="flex sm:hidden flex-1 justify-end">
        <solid-menu-icon class="w-8 h-8" />
      </div>
    </nav>
  </header>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "HeaderOrganism",
});
</script>
