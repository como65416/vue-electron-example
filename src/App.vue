<template>
  <div>
    <component-a></component-a>
  </div>
</template>

<style scoped>
</style>

<script>
import ComponentA from './components/ComponentA.vue';

export default {
  data() {
    return {
    };
  },
  methods: {
  },
  components: {
    'component-a': ComponentA
  }
}
</script>