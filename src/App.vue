<script>
import appHeaderVue from './components/appHeader.vue';
import appMainVue from './components/appMain.vue';
import appFooter from './components/appFooter.vue';

export default {
  components: {
    appHeaderVue,
    appMainVue,
    appFooterVue,
    
  }
}
</script>

<template>
  <div>
    <appHeaderVue></appHeaderVue>
    <appMainVue></appMainVue>
    <appFooterVue></appFooterVue>
  </div>
</template>

<style lang="scss">

</style>
