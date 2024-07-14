<template>
  <Home />
</template>

<script>
import { defineComponent } from 'vue';
import Home from '~/sections/Home.vue';
import About from '~/sections/About.vue';

export default defineComponent({
  components: { About, Home },
});
</script>

<style lang="css"></style>
