<template>
  <!-- Footer -->
  <footer class="white-section text-center" id="footer">
    <div class="container-fluid">
      <i class="social-icon fab fa-facebook-f" onclick="location.href='https://www.facebook.com/adityadimasptra/'"></i>
      <i class="social-icon fab fa-twitter" onclick="location.href='https://www.twitter.com/adityadimasptra/'"></i>
      <i class="social-icon fab fa-instagram" onclick="location.href='https://www.instagram.com/adityadimasptra/'"></i>
      <i class="social-icon fab fa-github" onclick="location.href='https://github.com/adityadimasptra/'"></i>
      <p>{{ copyright }}</p>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      copyright: "© Copyright 2020 Aditya Dimas Saputra"
    };
  }
};
</script>
