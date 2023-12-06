<script>
export default {
  name: "Jumbo block",
};
</script>

<template>
  <div class="jumbo-block"><h2>npm</h2></div>
  <div class="jumbo-block"><h2>vue</h2></div>
  <div class="jumbo-block"><h2>vite</h2></div>
</template>

<style scoped>
.jumbo-block {
  border: 1px solid white;
  margin: 20px;
  width: calc(100% / 3 - 40px);
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-transform: uppercase;
}
</style>
