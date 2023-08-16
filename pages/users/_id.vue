<template>
  <h1>This is user: {{ $route.params.id }}</h1>
</template>
<script lang="ts">
import { onMounted } from 'vue'
import { useRoute } from 'vue-router/composables.js'

export default {
  setup() {
    const route = useRoute()

    onMounted(() => {
      console.log(route)
    })
  },
}
</script>
