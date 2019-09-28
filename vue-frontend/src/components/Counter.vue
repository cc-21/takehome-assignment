<template>
  <div>
    <p>Episodes seen: {{count}} times!</p>
    <button v-on:click="count += 1">Add</button>
    <button v-on:click="count -= 1">Delete</button>
  </div>
</template>

<script>
export default {
  props: {
    count: {
      type: Number,
      default: 0
    }
  },

  data() {
    return count;
  }
};
</script>

<style>
</style>

