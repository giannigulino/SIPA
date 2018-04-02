<template>
  <header class="header">
    <div class="wrapper">

      <Logo href="#"/>

      <Menu/>

      <User/>

    </div>
  </header>
</template>

<script>


export default {
  name: 'Header',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .header {
    padding: 15px;
    background: #2d2b44;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
  }
  .wrapper {
    max-width: 1280px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
</style>
