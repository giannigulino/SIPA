<template>
  <div class="box">
    <img :src="image" >
  </div>
</template>

<script>
export default {
  name: 'Box',
  props: {
    image: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .box {
    background: #fff;
    min-height: 170px;
    width: 100%;
    margin: 1%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1em;
  }

  .box img{
      max-height:200px;
  }

  .small_img img{
      max-height:140px;
  }
</style>
