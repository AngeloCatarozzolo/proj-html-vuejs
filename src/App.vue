<script>
import appHeader from './components/appHeader.vue';
import appMain1 from './components/appMain1.vue';
import appMain2 from './components/appMain2.vue';
import appMain3 from './components/appMain3.vue';
import appMain4 from './components/appMain4.vue';
import appMain5 from './components/appMain5.vue';
import appMain6 from './components/appMain6.vue';
import appMain7 from './components/appMain7.vue';
import appFooter from './components/appFooter.vue';

export default {
  components: {
    appHeader,
    appMain1,
    appMain2,
    appMain3,
    appMain4,
    appMain5,
    appMain6,
    appMain7,
    appFooter,    
  }
}
</script>

<template>
  <div>
    <appHeader></appHeader>
    <appMain1></appMain1>
    <appMain2></appMain2>
    <appMain3></appMain3>
    <appMain4></appMain4>
    <appMain5></appMain5>
    <appMain6></appMain6>
    <appMain7></appMain7>
    <appFooter></appFooter>
  </div>
</template>

<style lang="scss">

</style>
