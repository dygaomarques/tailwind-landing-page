<template>
  <div>
    <section class="relative overflow-hidden">
      <div class="container flex flex-col lg:flex-row items-center gap-12 my-14 lg:my-28">
        <!-- Image -->
        <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
          <img src="@/assets/img/illustration-features-tab-1.png" alt="" />
        </div>

        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <h1 class="text-3xl text-bookmark-blue">Bookmark in one click</h1>
          <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">
            Organize your bookmarks however you like. Our simple drag-and-drop interface
            gives you complete control over how you manage your favorite sites.
          </p>
          <Button variant="primary">More info</Button>
        </div>
      </div>
      <!-- Rectangle -->
      <div
        class="hidden md:block overflow-hidden bg-bookmark-purple rounded-r-full h-80 w-2/4 absolute top-32 left-0 lg:bottom-0 lg:top-auto lg:-right-36"
      ></div>
    </section>

    <section class="relative overflow-hidden">
      <div
        class="container flex flex-col lg:flex-row-reverse items-center gap-12 my-14 lg:my-28"
      >
        <!-- Image -->
        <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
          <img src="@/assets/img/illustration-features-tab-2.png" alt="" />
        </div>

        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <h1 class="text-3xl text-bookmark-blue">Inteligent search</h1>
          <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">
            Our powerful search feature will help you find saved sites in no time at all.
            No need to crawl through all of your bookmarks.
          </p>
          <Button variant="primary">More info</Button>
        </div>
      </div>
      <!-- Rectangle -->
      <div
        class="hidden md:block overflow-hidden bg-bookmark-purple rounded-l-full h-80 w-2/4 absolute top-32 right-0 lg:bottom-0 lg:top-auto lg:-right-36"
      ></div>
    </section>

    <section class="relative overflow-hidden">
      <div class="container flex flex-col lg:flex-row items-center gap-12 my-14 lg:my-28">
        <!-- Image -->
        <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
          <img src="@/assets/img/illustration-features-tab-3.png" alt="" />
        </div>

        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <h1 class="text-3xl text-bookmark-blue">Share your bookmarks</h1>
          <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">
            Easily share your bookmarks and collections with others. Create a shareable
            link that you can send at the click of a button.
          </p>
          <Button variant="primary">More info</Button>
        </div>
      </div>
      <!-- Rectangle -->
      <div
        class="hidden md:block overflow-hidden bg-bookmark-purple rounded-r-full h-80 w-2/4 absolute top-32 left-0 lg:bottom-0 lg:top-auto lg:-right-36"
      ></div>
    </section>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "FeaturesOrganism",
});
</script>
