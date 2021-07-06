<template>
  <navbar
    position="fixed"
    type="primary"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template>
      <router-link class="navbar-brand" to="/">
        Bruno Behnken
      </router-link>
    </template>
    <template slot="navbar-menu">
      <li class="nav-item">
        <router-link class="nav-link" to="/">
          Home
        </router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/blog">
          Blog
        </router-link>
      </li>

      <li class="nav-item">
        <a
            class="nav-link"
            rel="tooltip"
            title="View me on LinkedIn"
            data-placement="bottom"
            href="https://www.linkedin.com/in/brunobehnken/"
            target="_blank"
        >
          <ion-icon class="ion-icon" name="logo-linkedin"></ion-icon>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Follow me on Twitter"
          data-placement="bottom"
          href="https://twitter.com/behnken_dev"
          target="_blank"
        >
          <ion-icon class="ion-icon" name="logo-twitter"></ion-icon>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Send me an e-mail"
          data-placement="bottom"
          href="mailto:bruno@behnken.dev"
          target="_blank"
        >
          <ion-icon class="ion-icon" name="mail-outline"></ion-icon>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Check out my GitHub"
          data-placement="bottom"
          href="https://github.com/brunobehnken"
          target="_blank"
        >
          <ion-icon class="ion-icon" name="logo-github"></ion-icon>
        </a>
      </li>
    </template>
  </navbar>
</template>

<script>
import { DropDown, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';
import router from "@/router";
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    Navbar,
    // NavLink,
    [Popover.name]: Popover
  },
  methods: {
    toBlog() {
      router.push('/landing')
    }
  }
};
</script>

<style scoped></style>
