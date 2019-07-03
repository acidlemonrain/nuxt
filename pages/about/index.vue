<template>
  <div>
    <maincard v-for="ele in cards" v-bind:key="ele.title" v-bind:card="ele"></maincard>

    <div class="row">
      <div class="col-lg-6 offset-lg-3 main">
        <hr />Humans are nearly exterminated by giant creatures called Titans. Titans are typically several stories tall, seem to have no intelligence, devour human beings and, worst of all, seem to do it for the pleasure rather than as a food source. A small percentage of humanity survived by walling themselves in a city protected by extremely high walls, even taller than the biggest of titans. Flash forward to the present and the city has not seen a titan in over 100 years. Teenage boy Eren and his foster sister Mikasa witness something horrific as the city walls are destroyed by a colossal titan that appears out of thin air. As the smaller titans flood the city, the two kids watch in horror as their mother is eaten alive. Eren vows that he will murder every single titan and take revenge for all of mankind.
      </div>

      <div class="col-lg-6 offset-lg-3 main">
        <hr />
        <h5>Lorem, ipsum.</h5>
        <p>I've seen all kinds of animes, mostly adult ones because usually they have a better story then kid shows, and I had nothing left to watch so i googled 2013 animes and this one seemed slightly interesting, watched a trailer first and didn't like the trailer, watched the 1st episode and I was hooked, watched the 2nd and i was totally hooked, watched the 3rd and it blew my mind, now I will have to wait every week for an episode daaamn, the first 3 episodes of this anime prove that this anime will be an awesome one, you can foretell that by watching how the first episodes is building up this hype-level of an awesome story which started out sad and is going to become epic and bloody. The concept is unique and I like it. Humans who live inside 50 meters high walls to protect themselves from titans (giants), Eren the main character feels unpleasant about it compared to everybody else because that's not really true freedom for a human to be "livestock" inside walls, waiting to get eaten by titans. One day, and that would be the day they would all remember for eternity, the day when first wall fell and hell broke loose, this is where the story starts. And it just gets better and better! There's a lot of emotional and bloody scenes which usually makes up for a good story. You know those animes that catch your eyes on the first episode, this is one of them.</p>
      </div>
    </div>
  </div>
</template>
 
<script>
import ScrollReveal from "scrollreveal";
import maincard from "~/components/Acard.vue";
export default {
  components: {
    maincard
  },
  data: () => ({
    cards: [
      {
        des:
          "After Ymir's death, the Nine Titans conquered the nation of Marley and established the empire of Eldia.[2] The Nine Titans were split inThis anime just keeps me on the edge of my seat. Each week I watch and each week I want more. It's intense. The concept and story line are on point and keep you thrilled and wanting more. The only downside is the seven-day waiting for the next episode. Definitely one of the best anime I have seento Eldian noble houses. The Fritz family maintained order over the other eight houses, who were locked in constant conflict, using the Founding Titan.[34]",
        title: "Alron and armour",
        src:
          "https://tse2-mm.cn.bing.net/th?id=OIP.9Qq4Of87Aek2MQNBhhltfQHaEx&w=248&h=160&c=7&o=5&dpr=1.25&pid=1.7"
      },
      {
        des:
          "Unlike other species, Titans doThis anime just keeps me on the edge of my seat. Each week I watch and each week I want more. It's intense. The concept and story line are on point and keep you thrilled and wanting more. The only downside is the seven-day waiting for the next episode. Definitely one of the best anime I have seen not mate, nor interact with organisms other than humans;[3] their sole purpose in life is to seek out and devour humans. They do not derive any real sustenance from humans either, as many of them did not taste human flesh for a century after the Walls were raised, ",
        title: "Titans conquered",
        src:
          "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkL8MpE76EKO6P7AbXoV7DLAr_sLb0mUW55loYnxV47LbTGi-2ag"
      },
      {
        des:
          "Theming the navbarThis anime just keeps me on the edge of my seat. Each week I watch and each week I want more. It's intense. The concept and story line are on point and keep you thrilled and wanting more. The only downside is the seven-day waiting for the next episode. Definitely one of the best anime I have seen has never been easier thanks to the combination of theming classes and background-color utilities. Choose from .navbar-light for use with light background colors, or .navbar-dark for dark background colors. Then, customize with .bg-* utilities.",
        title: "Nine Titans",
        src:
          "https://tse1-mm.cn.bing.net/th?id=OIP.UG_caapfrXQLajK9lJl-AwHaEK&w=250&h=160&c=7&o=5&dpr=1.25&pid=1.7"
      }
    ],
    intersectionOptions: {
      root: null,
      rootMargin: "0px 0px 0px 0px",
      thresholds: [0]
    }
  }),
  mounted() {
    ScrollReveal().reveal(".main", {
      interval: 6,
      reset: true
    });
  },
  methods: {
    onWaypoint({ going, direction }) {
      // going: in, out
      // direction: top, right, bottom, left
      if (going === this.$waypointMap.GOING_IN) {
        console.log("waypoint going in!");
      }

      if (direction === this.$waypointMap.DIRECTION_TOP) {
        console.log("waypoint going top!");
      }
    }
  }
};
</script>

<style scoped>
h5 {
  text-align: center;
}
</style>
