<template>
  <section class="my-14 lg:my-28">
    <div class="container mx-auto">
      <header class="sm:w-3/4 lg:w-5/12 mx-auto mb-16">
        <h2 class="text-3xl text-center text-bookmark-blue">Download the extension</h2>
         <p class="text-center text-bookmark-grey mt-4">
          We’ve got more browsers in the pipeline. Please do let us know if you’ve got a favorite you’d like us to
          prioritize.
        </p>
      </header>
      <div
        class="container grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16 max-w-screen-lg"
      >
        <Card
          :card-image="require('@/assets/img/logo-chrome.svg')"
          card-title="Add to Chrome"
          card-text="Minimum version 62"
        />
        <Card
          :card-image="require('@/assets/img/logo-firefox.svg')"
          card-title="Add to Firefox"
          card-text="Minimum version 62"
        />
        <Card
          :card-image="require('@/assets/img/logo-opera.svg')"
          card-title="Add to Opera"
          card-text="Minimum version 62"
        />
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "DownloadMolecule",
});
</script>
