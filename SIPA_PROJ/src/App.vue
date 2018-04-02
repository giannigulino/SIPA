<template>
  <div id="app">
    <Header/>
    <div class="wrapper-grid">
      <div class="row">
        <Box image="https://cdn02.nintendo-europe.com/media/images/10_share_images/systems_11/nintendo_switch_1/nintendo_labo/H2x1_Labo_Generic_itIT_image800w.jpg" />
      </div>

      <div class="row">
        <Box image="https://cdn02.nintendo-europe.com/media/images/10_share_images/games_15/nintendo_switch_4/H2x1_NSwitch_SuperMarioOdyssey_Musical_image1250w.jpg" />
        <Box image="https://cdn02.nintendo-europe.com/media/images/10_share_images/games_15/nintendo_switch_4/H2x1_NSwitch_TheElderScrollsVSkyrim_image1250w.jpg"/>
      </div>

      <div class="row">
		<Box class="small_img" image="https://cdn02.nintendo-europe.com/media/images/10_share_images/country_support_5/it_24/SI_Brochure_Nintendo_image1250w.jpg" />
		<Box class="small_img" image="https://cdn02.nintendo-europe.com/media/images/10_share_images/games_15/nintendo_switch_4/H2x1_NSwitch_KirbyStarAllies_image1250w.jpg" />
		<Box class="small_img" image="https://cdn02.nintendo-europe.com/media/images/10_share_images/games_15/smart_device_3/H2x1_SmartDevice_SuperMarioRun_image1250w.jpg" />
      </div>
    </div>

  </div>
</template>

<script>

import Header from './components/Header.vue'
import Box from './components/Box.vue'

export default {
  name: 'app',
  components: {
    'Header': Header,    
  }
}
</script>

<style>

* {
  box-sizing: border-box;
}

body, html {
  margin: 0;
  padding: 0;
}

body {
  background: #efefef;
}

.wrapper-grid {
  max-width: 900px;
  margin: 0 auto;
  margin-top: 150px;
}

.row {
  display: flex;
  justify-content: space-between;
}


#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000;
}
</style>
