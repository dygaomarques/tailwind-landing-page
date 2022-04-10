<template>
  <div class="flex flex-col rounded-md shadow-md lg:mb-16">
    <div class="p6 flex flex-col items-center">
      <img :src="cardImage" alt="" />
      <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">{{ cardTitle }}</h3>
      <p v-if="cardText" class="mb-2 text-bookmark-grey font-light">{{ cardText }}</p>
    </div>
    <hr class="border-b border-bookmark-white" />
    <div class="flex p-6">
      <Button class="flex-1" variant="primary">Add & Install Extension</Button>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "CardMolecule",
  props: {
    cardImage: {
      type: String,
      required: true,
    },
    cardTitle: {
      type: String,
      required: true,
    },
    cardText: {
      type: String,
      default: "",
    },
  },
});
</script>
