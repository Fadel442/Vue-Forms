<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SignupForm from './components/komponen/SignupForm.vue'
</script>

<template>
  <SignupForm />
</template>

<script>
  export default {
    components: { SignupForm },
    data() {
      return {
        
      }
    },
  }
</script>

<style>
body {
  margin: 0;
  background: gray;
}
</style>
