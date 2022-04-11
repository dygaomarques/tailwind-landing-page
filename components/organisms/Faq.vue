<template>
  <section class="relative overflow-hidden">
    <div class="container flex flex-col items-center gap-12 my-14 lg:my-28">
      <header class="sm:w-3/4 lg:w-5/12 mx-auto mb-16">
        <h2 class="text-3xl text-center text-bookmark-blue">
          Frequently Asked Questions
        </h2>
        <p class="text-center text-bookmark-grey mt-4">
          Here are some of our FAQs. If you have any other questions you’d like answered
          please feel free to email us.
        </p>
      </header>

      <!-- FAQ Items -->
      <div class="flex flex-col sm:w-3/4 lg:w-5/12 mx-auto">
        <div class="flex items-center border-b py-4">
          <span class="flex-1">What is a Bookmark?</span>
          <solid-chevron-down-icon class="w-8 h-8 text-bookmark-purple" />
        </div>
        <div class="flex items-center border-b py-4">
          <span class="flex-1">How can I request a new browser?</span>
          <solid-chevron-down-icon class="w-8 h-8 text-bookmark-purple" />
        </div>
        <div class="flex items-center border-b py-4">
          <span class="flex-1">Is there a mobile app?</span>
          <solid-chevron-down-icon class="w-8 h-8 text-bookmark-purple" />
        </div>
        <div class="flex items-center border-b py-4">
          <span class="flex-1">What about other Chromium browsers?</span>
          <solid-chevron-down-icon class="w-8 h-8 text-bookmark-purple" />
        </div>
      </div>

      <Button variant="primary">More info</Button>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "FaqOrganism",
});
</script>
