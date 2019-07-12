<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script lang="ts">
  export default {
    name: 'BookList',
    data() {
      return {
        title: 'All Books'
      }
    }
  }
</script>

<style scoped>
h1, h2 {
  font-weight: normal
}
</style>
