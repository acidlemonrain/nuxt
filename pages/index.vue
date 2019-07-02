<template>
  <div class="container-flex">
    <div class="row">
      <div class="col-lg-3 r"></div>
      <div class="col-lg-6 z">
        <maincard />
      </div>
      <div class="col-lg-3 l"></div>
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import maincard from "~/components/indexCard.vue";
export default {
  components: {
    maincard
  }
};
</script>

<style scoped>
.z {
  padding: 0;
}
.r {
  background-attachment: fixed;

  background-image: url("~assets/3.jpg");
}
.l {
  background-attachment: fixed;

  background-image: url("https://tse2-mm.cn.bing.net/th?id=OIP.Oct7I-VO8iCVSrK_hr059gHaEa&w=299&h=175&c=7&o=5&dpr=1.25&pid=1.7");
}
</style>
