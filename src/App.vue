<script setup lang="ts">
// import { RouterLink, RouterView } from 'vue-router' 
import head1 from './components/head1.vue'
import head2 from './components/head2.vue'
import head3 from './components/head3.vue'
import maincontent from './components/maincontent.vue';
import maincontent2 from './components/maincontent2.vue';
import subcontent from './components/subcontent.vue';

</script>

<template>
    <!-- 
    <div>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
    </div>
      -->
    <head1/>
    <head2/>
    <head3/>
    <maincontent/>
    <maincontent2/>
    <subcontent/>
  <RouterView />
</template>

<style scoped>
.app{
  color: red;
  font-size: 30px;
}


</style>
