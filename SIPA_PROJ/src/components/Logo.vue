<template>
  <a :href="href" class="logo">
    <img src="../assets/logo.png">
  </a>
</template>

<script>
export default {
  name: 'Logo',
  props: {
    href: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .logo {
    height: 40px;
  }
  .logo img {
    display: block;
    height: 100%;
  }
</style>
