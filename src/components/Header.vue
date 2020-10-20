<template>
  <header class="site-header sitenav fixed-top">
    <div class="sitenav__container">
      <nav
        class="sitenav__links"
        id="#navbar-example2"
        :class="[isActive ? 'active' : ' ']"
      >
        <ul class="sitenav__linklist">
          <li class="sitenav__linkitem" v-for="(item, i) in menuItems" :key="i">
            <a :class="item.iconName" :href="item.path">{{ item.name }}</a>
          </li>
        </ul>
        <div class="sitenav__download">
          <a href="/android-user" target="_blank" rel="noopener noreferrer">
            <button class="sx-btn sx-btn--android icon-android" type="button">
              <span>download <em>android</em></span>
            </button>
          </a>
          <a href="/ios-user">
            <button class="sx-btn sx-btn--ios icon-apple" type="button">
              <span>click here <em>IOS</em></span>
            </button>
          </a>
        </div>
      </nav>
      <div class="container-fluid">
        <div class="sitenav__wrap">
          <div class="sitenav__logo">
            <a href="/" target="_blank">
              <img
                src="../assets/images/logo.png"
                alt=""
                class="img-fluid logo-light"
              />
            </a>
          </div>
          <div class="sitenav__download--icons d-block d-sm-none ml-auto mr-3">
            <a href="/android-user" class="sx-btn icon-android"></a>
            <a href="/ios-user" class="sx-btn icon-apple"></a>
          </div>
          <div
            class="sitenav__hamburger"
            @click="toggleClass()"
            :class="[isActive ? 'active' : ' ']"
          >
            <div class="hamburger-inner"></div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        {
          iconName: "icon-home",
          name: "home",
          path: "/",
        },
        {
          iconName: "icon-help",
          name: "faq",
          path: "/faq",
        },
        {
          iconName: "icon-cricket",
          name: "fantasy-cricket",
          path: "/fantasy-cricket",
        },
        {
          iconName: "icon-cricket",
          name: "how to play",
          path: "/how-to-play",
        },
        {
          iconName: "icon-accept",
          name: "play responsibly",
          path: "/play-responsibly",
        },
        {
          iconName: "icon-policy",
          name: "fair play policy",
          path: "/fairplaypolicy",
        },
        {
          iconName: "icon-accept",
          name: "Legalities",
          path: "/legalities",
        },
        {
          iconName: "icon-refer",
          name: "refer a friend",
          path: "/android",
        },
        {
          iconName: "icon-phone",
          name: "contact us",
          path: "/contact",
        },
      ],
      isActive: false,
    };
  },
  methods: {
    toggleClass() {
      this.isActive = !this.isActive;
    },
  },
};
</script>

<style>
</style>