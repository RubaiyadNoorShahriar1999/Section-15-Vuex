<template>
  <h3>{{ counter }}</h3>
</template>
<script>
export default {
  computed: {
    counter() {
      // This is the initial counter value
      return this.$store.state.counter;
    },
  },
};
</script>
