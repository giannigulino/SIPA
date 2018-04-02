<template>
  <div class="menu">
    <ul>
      <li>
        <a href="#" class="-active">Dashboard</a>
      </li>
      <li>
        <a href="#">vuex</a>
      </li>
      <li>
        <a href="#">vue-devtools</a>
      </li>
      <li>
        <a href="#">vue-loader</a>
      </li>
      <li>
        <a href="#">awesome-vue</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Menu'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .menu {
  }
  .menu ul {
    list-style-type: none;
    display: flex;
    padding: 0;
    margin: 0;
  }
  .menu li {
    margin: 0 19px;
  }
  .menu a {
    position: relative;
    text-transform: uppercase;
    font-size: 12px;
    opacity: .6;
    text-decoration: none;
    color: #fff;
    padding: 10px 0;
    transition: opacity .2s ease;
  }
  .menu a:hover {
    opacity: 1;
  }
  .menu a.-active {
    opacity: 1;
  }
  .menu a.-active:after {
    content: "";
    display: block;
    position: absolute;
    bottom: 0;
    left: 50%;
    width: 80%;
    height: 1px;
    background: #fff;
    transform: translateX(-50%);
  }
</style>
