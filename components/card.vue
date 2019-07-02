<template>
  <div class="card">
    <i>{{card.title}}</i>
    <div class="img" style="margin-top:8px">
      <img :src="card.src" />
    </div>
    <div class="des">{{card.des}}</div>
  </div>
</template>

<script>
export default {
  props: ["card"]
};
</script>

<style scoped>
.card {
  text-align: center;
  color: rgb(231, 58, 58);
  background-color: rgba(87, 61, 36, 0.746);
  margin: 1rem;
  padding: 1rem;
  box-shadow: inset 2px 2px 20px black;
}
.des {
  padding: 2rem;
  border: 4px dotted rgb(221, 209, 41);
  margin-top: 1rem;
  color: rgb(221, 209, 41);
}
</style>
