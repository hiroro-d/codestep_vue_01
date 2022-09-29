<template>
  <div id="app">
    <NavComponent/>
    <MainVisual/>
    <MainContents/>
    <FooterComponent/>
  </div>
</template>

<script>
import 'normalize.css'
import NavComponent from './components/NavComponent.vue'
import MainVisual from './components/MainVisual.vue'
import MainContents from './components/MainContents.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    NavComponent,
    MainVisual,
    MainContents,
    FooterComponent,
  }
}
</script>

<style>

#app {
  color: #383e45;
  font-size: 0.9rem;
  max-width: 960px;
  margin: 0 auto;
}

#app img {
  max-width: 100%;
}
#app .mb_60 {
  margin-bottom: 80px;
}

#app li {
  list-style: none;
}

#app .contents_wrapper {
  margin-bottom: 60px;
  text-align: center;
}

#app .section_ttl {
  border-bottom: solid 1px #383e45;;
  font-size: 2rem;
  display: inline;
  padding: 10px;
}

@media screen and (min-width: 600px) {
  #app .main_visual img {
    height: 600px;
  }

  #app .r_wrapper {
  display: flex;
  }
  #app .r_wrapper img {
    width: 100px;
    height: 100px;
    margin: 15px 130px 0 0;
  }

  #app #bicycle {
    display: flex;
    margin: 0 20px;
    gap: 15px;
  }
  #app .bicycle_content img {
    width: 270px;
  }

}

</style>
