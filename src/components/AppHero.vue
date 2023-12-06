<script>
import AppHeroBlock from "./AppHeroBlock.vue";
export default {
  name: "Jumbo app",
  data() {
    return {
      author: "Luca Caldato",
    };
  },
  components: {
    AppHeroBlock,
  },
};
</script>

<template>
  <div class="container">
    <AppHeroBlock />
  </div>
  <h3>By {{ author }}</h3>
</template>

<style scoped>
.container {
  display: flex;
  border: 1px solid white;
}
</style>
