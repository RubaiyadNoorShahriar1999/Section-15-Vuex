<template>
  <button @click="addOne">Add 2</button>
</template>

<script>
export default {
  methods: {
    addOne() {
      //commit takes the name of the mutation as the first argument and the payload as the second argument
      this.$store.commit('increment');
    },
  },
};
</script>
