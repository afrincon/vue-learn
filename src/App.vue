<template>
  <div id="app">
    <HeaderBanner></HeaderBanner>
    <router-view/>
  </div>
</template>

<script>
import HeaderBanner from '@/components/HeaderSection.vue';

export default {
  name: 'app',
  components: { HeaderBanner },
};
</script>


<style>

</style>
