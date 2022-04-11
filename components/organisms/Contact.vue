<template>
  <section class="bg-bookmark-purple text-white my-14 lg:my-28">
    <div class="container py-20">
      <div class="sm:w-3/4 lg:w-2/4 mx-auto">
        <p class="font-light uppercase text-center mb-8">35,000+ ALREADY JOINED</p>
        <h2 class="text-3xl text-center">Stay up-to-date with what we’re doing</h2>
        <div class="flex flex-col sm:flex-row gap-6 mt-8">
          <input
            type="text"
            placeholder="Enter your email address"
            class="focus:outline-none flex-1 px-3 py-3 rounded-md text-black"
          />
          <Button variant="accent">Contact Us</Button>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "ContactOrganism",
});
</script>
