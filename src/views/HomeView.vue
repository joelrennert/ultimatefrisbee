<script setup>
import SquareDiv from '../components/SquareDiv.vue'
</script>

<template>
  <main>
    <SquareDiv v-for="n in 1450" v-bind:key="n" class="" />
  </main>
</template>
<style scoped>
.square {
  width: 30px;
  height: 30px;
}

main {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  width: 100vw;
  height: 100vh;
  align-items: center;
  align-content: flex-start;
  overflow-y: hidden;
  overflow-x: hidden;
  background: linear-gradient(
    90deg,
    rgba(132, 99, 174, 0.582) 0%,
    rgba(253, 29, 29, 0.485) 40%,
    rgba(252, 176, 69, 0.5858937324929971) 100%
  );
}
</style>
