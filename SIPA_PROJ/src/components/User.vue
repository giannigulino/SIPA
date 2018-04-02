<template>
  <div class="user">
    <a href="#">
      Utente Prova
    </a>
    <a href="#" class="pic">
      <img src="https://images-na.ssl-images-amazon.com/images/M/MV5BMTM0ODU5Nzk2OV5BMl5BanBnXkFtZTcwMzI2ODgyNQ@@._V1_UY256_CR4,0,172,256_AL_.jpg">
    </a>
  </div>
</template>

<script>
export default {
  name: 'User'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .user {
    display: flex;
    align-items: center;
  }

  .user a {
    color: #fff;
    font-size: 12px;
  }

  .pic {
    height: 50px;
    width: 50px;
    margin-left: 10px;
    border-radius: 50%;
    overflow: hidden;
    border: 2px solid #2d2b44;
    box-shadow: 0 0 0px 2px #fff;
  }

  .pic img {
    object-fit: cover;
    display: block;
    height: 100%;
    width: 100%;
  }
</style>
