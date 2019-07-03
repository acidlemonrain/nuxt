<template>
  <div class="row">
    <div class="main col-lg-6">
      <h1>
        <i>{{card.title}}</i>
      </h1>
      <div class="x" style="margin-top:8px; margin:auto">
        <img :src="card.src" />
      </div>
      <div class="des">{{card.des}}</div>
    </div>
  </div>
</template>

<script>
import ScrollReveal from "scrollreveal";
export default {
  props: ["card"],

  mounted() {
    ScrollReveal().reveal(".main", {
      interval: 12,
      reset: true
    });
  }
};
</script>

 <style scoped>
.main {
  margin: auto;
  padding: 2rem;
  border-color: #ccc;
  text-align: center;
}
.x {
  margin: auto;
  margin-top: 3rem;
}
img {
  height: 38vh;
  margin: 3rem;
}
</style>
 