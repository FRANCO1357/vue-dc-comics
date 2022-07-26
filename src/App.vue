<template>
  <div id="app">
    <TheHeader/>
    <TheMain :comics="comics" />
    <TheFooter/>
  </div>
</template>

<script>
import comics from "./assets/data/dc-comics.json";
import TheHeader from './components/TheHeader.vue'
import TheMain from './components/TheMain.vue'
import TheFooter from './components/TheFooter.vue'

export default {
  name: 'App',
  data() {
        return{
            comics
        }
    },
  components: {
    TheHeader,
    TheMain,
    TheFooter
}
}
</script>

<style lang="scss">
@import './assets/sass/style.scss';
</style>
