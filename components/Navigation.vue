<template>
  <section class="colored-section">
    <!-- Nav Bar -->

    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand" :href="link.home">{{ nameTag }} </a>
      <small>{{ subtitle }}</small>

      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarToggle"
      >
        <span class="navbar-toggler-icons"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarToggle">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <nuxt-link :to="link.home" exact="">{{ titleLink.home }}</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link :to="link.aboutMe">{{ titleLink.aboutMe }}</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link :to="link.experiences">{{
              titleLink.experiences
            }}</nuxt-link>
          </li>
        </ul>
      </div>
    </nav>

    <!-- End Nav Bar -->
  </section>
</template>

<script>
export default {
  data() {
    return {
      nameTag: `Aditya's`,
      subtitle: "PORTOFOLIO",
      link: {
        home: "/",
        aboutMe: "/about",
        experiences: "experiences"
      },
      titleLink: {
        home: "Home",
        aboutMe: "About Me",
        experiences: "Experiences"
      }
    };
  }
};
</script>

<style></style>
