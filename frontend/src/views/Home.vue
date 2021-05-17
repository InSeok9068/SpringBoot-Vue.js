<template>
  <div class="home">
    <img alt="Vue with Spring logo" src="../assets/siba.gif">
    <HelloSpringWorld hellomsg="시빠 개발자의 Web Application Service"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloSpringWorld from '@/components/HelloSpringWorld.vue'; // @ is an alias to /src

export default defineComponent({
  name: 'Home',
  components: {
    HelloSpringWorld,
  },
});
</script>
