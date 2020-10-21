<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  props: ['title']
}
</script>

<style scoped>
  header {
    width: 100%;
    height: 5rem;
    margin-bottom: 2rem;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #39116d;
  }

  header h1 {
    color: white;
    margin: 0;
  }
</style>
