<template>
  <div class="edge">
    <card v-for="ele in cards" v-bind:key="ele.title" v-bind:card="ele"></card>
  </div>
</template>

<script>
import card from "~/components/card.vue";
export default {
  components: {
    card
  },
  data: function() {
    return {
      cards: [
        {
          des:
            "After Ymir's death, the Nine Titans conquered the nation of Marley and established the empire of Eldia.[2] The Nine Titans were split into Eldian noble houses. The Fritz family maintained order over the other eight houses, who were locked in constant conflict, using the Founding Titan.[34]",
          title: "Alron and armour",
          src:
            "https://tse2-mm.cn.bing.net/th?id=OIP.9Qq4Of87Aek2MQNBhhltfQHaEx&w=248&h=160&c=7&o=5&dpr=1.25&pid=1.7"
        },
        {
          des:
            "Unlike other species, Titans do not mate, nor interact with organisms other than humans;[3] their sole purpose in life is to seek out and devour humans. They do not derive any real sustenance from humans either, as many of them did not taste human flesh for a century after the Walls were raised, ",
          title: "first2",
          src:
            "https://tse3-mm.cn.bing.net/th?id=OIP.eLea1EAcoK6SiRQUUFs43QHaEK&w=252&h=160&c=7&o=5&dpr=1.25&pid=1.7"
        },
        {
          des:
            "Theming the navbar has never been easier thanks to the combination of theming classes and background-color utilities. Choose from .navbar-light for use with light background colors, or .navbar-dark for dark background colors. Then, customize with .bg-* utilities.",
          title: "first3",
          src:
            "https://tse1-mm.cn.bing.net/th?id=OIP.UG_caapfrXQLajK9lJl-AwHaEK&w=250&h=160&c=7&o=5&dpr=1.25&pid=1.7"
        }
      ]
    };
  }
};
</script>

<style>
.edge {
  margin-top: 1rem;
  background-color: rgba(49, 40, 40, 0.849);
  border: 5px solid rgba(233, 141, 141, 0.205);
  padding: 3px;
  z-index: 3;
}
</style>
