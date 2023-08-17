<template>
  <div class="container">
    <ul>
      <li>
        <NuxtLink to="/parent"><h3>Nested Pages</h3></NuxtLink>
      </li>
      <li>
        <NuxtLink to="/users"><h3>Users Pages</h3></NuxtLink>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>

<style lang="scss"></style>
