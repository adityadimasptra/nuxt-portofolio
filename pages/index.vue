<template>
  <section class="colored-section" id="title">
    <div class="container-fluid">
      <!-- Title -->

      <div class="row">
        <div class="col-lg-6">
          <h1 class="big-heading">
            {{ titleHeading }}
          </h1>
          <h6 class="find-me">Find me on:</h6>
          <button
            type="button"
            class="btn btn-light btn-lg download-btn"
            onclick="location.href='https://www.instagram.com/adityadimasptra/'"
          >
            <i class="fab fa-instagram"></i> {{ mediaSosial.instagram }}
          </button>
          <button
            type="button"
            class="btn btn-info btn-lg download-btn"
            onclick="location.href='https://twitter.com/adityadimasptra'"
          >
            <i class="fab fa-twitter"></i> {{ mediaSosial.twitter }}
          </button>
        </div>

        <div class="col-lg-6">
          <img
            class="title-img"
            src="@/assets/images/web-developer.svg"
            alt="iphone-mockup"
          />
        </div>
      </div>

      <!-- End Title -->
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      titleHeading: `Hello, i'm front-end developer. if you don't mind, please check information about me on this website`,
      mediaSosial: {
        twitter: "Twitter",
        instagram: "Instagram"
      }
    };
  }
};
</script>
