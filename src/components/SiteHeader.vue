<template>
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Hi! I'm Matias Davidson</div>
          <div class="intro-heading">Front End Developer</div>
          <img src="../assets/img/scroll.png" alt="scroll" class="scroll-icon">
        </div>
      </div>
</template>

<script>
export default {
      methods: {
    collapseMenu: function(){
      document.getElementById("navbarResponsive").classList.remove("show");
    }
  },
}
</script>

<style lang="css">
</style>


