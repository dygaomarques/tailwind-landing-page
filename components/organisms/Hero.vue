<template>
  <section class="relative overflow-hidden">
    <div
      class="container flex flex-col-reverse lg:flex-row items-center gap-12 my-14 lg:my-28"
    >
      <!-- Content -->
      <div class="flex flex-1 flex-col items-center lg:items-start">
        <h2 class="text-bookmark-blue text-3xl lg:text-5xl text-center lg:text-left mb-6">
          A simple Bookmark Manager
        </h2>
        <p class="text-bookmark-grey text-lg text-center lg:text-left mb-6">
          A clean and simple interface to organize your favorite websites. Open a new
          browser tab and see load instantly. try it for free.
        </p>
        <div class="flex justify-center flex-wrap gap-6">
          <Button> Get it on Chrome</Button>
          <Button variant="secondary"> Get it on Firefox</Button>
        </div>
      </div>

      <!-- Image -->
      <div class="flex justify-center flex-1 mb-10 md:mb-16 lg:mb-0 z-10">
        <img
          src="@/assets/img/hero-bg.png"
          alt=""
          class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-5/6 md:h-full"
        />
      </div>
    </div>
    <!-- Rectangle -->
    <div
      class="hidden md:block overflow-hidden bg-bookmark-purple rounded-l-full h-80 w-2/4 absolute top-32 right-0 lg:bottom-0 lg:-right-36"
    ></div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "HeroOrganism",
});
</script>
