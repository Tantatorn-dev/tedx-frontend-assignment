<template>
  <b-navbar :shadow="true">
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <Logo />
      </b-navbar-item>
    </template>

    <template #end>
      <b-navbar-item href="#"> Find A Match </b-navbar-item>
      <b-navbar-item href="#"> Dog's Personalities </b-navbar-item>
      <b-navbar-item href="#"> About Us </b-navbar-item>
      <b-navbar-item href="#"> Contact Us </b-navbar-item>
      <b-navbar-item href="#">
        <img src="../assets/loupe.png" />
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
import Logo from "./Logo";

export default {
  name: "NavBar",
  components: {
    Logo,
  },
};
</script>