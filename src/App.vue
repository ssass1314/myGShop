<template>
 <div id="div">
     <router-view/>
    <FooterGuide></FooterGuide>
 </div>
</template>

<script type="text/ecmascript-6">
import FooterGide from './components/FooterGuide/FooterGuide'
export default {
  components: {
    FooterGide,
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
  
</style>
