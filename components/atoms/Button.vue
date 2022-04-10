<template>
  <button
    type="button"
    :class="
      variant === 'primary'
        ? 'btn-primary'
        : variant === 'accent'
        ? 'btn-accent'
        : variant === 'secondary'
        ? 'btn-secondary'
        : ''
    "
  >
    <slot></slot>
  </button>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "ButtonAtom",
  props: {
    variant: {
      type: String,
      default: "primary",
      validator: (value: string) => {
        return ["primary", "secondary", "accent"].includes(value);
      },
    },
  },
});
</script>

<style lang="postcss" scoped>
button {
  @apply shadow-md py-3 px-6 rounded-md transition duration-300 uppercase;

  &.btn-primary {
    @apply bg-bookmark-purple text-white hover:bg-bookmark-white hover:text-bookmark-purple;
  }

  &.btn-secondary {
    @apply bg-bookmark-white hover:bg-bookmark-purple hover:text-white;
  }

  &.btn-accent {
    @apply bg-bookmark-red text-white hover:bg-bookmark-white hover:text-bookmark-red;
  }
}
</style>
