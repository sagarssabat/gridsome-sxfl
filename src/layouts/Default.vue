<template>
  <div class="site" v-bind:class="show ? 'home' : ''">
    <Header></Header>
    <transition name="fade" appear>
      <div class="site-content">
        <slot />
      </div>
    </transition>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Footer from "../components/Footer.vue";

export default {
  metaInfo: {
    title: "SportzXchange",
  },
  components: {
    Header,
    Footer,
  },
  data() {
    return {
      show: false,
    };
  },
  async mounted() {
    let obj = this.$route;
    if (obj) {
      this.show = obj.path === "/" ? true : false;
    }
  },
};
</script>

<style>
.fade-enter-active {
  transition: opacity 0.5s;
}

.fade-enter {
  opacity: 0;
}
</style>

