<template>
    <footer>
        <TheFooterTop/>
        <TheFooterBottom/>
    </footer>
</template>

<script>
import TheFooterTop from './TheFooterTop.vue'
import TheFooterBottom from './TheFooterBottom.vue'

export default {
  name: 'TheFooter',
  components: {
    TheFooterTop,
    TheFooterBottom,
}
}
</script>

<style lang="scss" scoped>

footer{
    background-image: url('../assets/img/footer-bg.jpg');
}
</style>