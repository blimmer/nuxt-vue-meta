<template>
  <div>
    <NuxtLink to="/">/</NuxtLink>
    <NuxtLink to="1">1</NuxtLink>
    <NuxtLink to="2">2</NuxtLink>
    <NuxtLink to="3">3</NuxtLink>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: '2',
  head() {
    return {
      title: '2'
    }
  }
})
</script>
