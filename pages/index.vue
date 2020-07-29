<template>
  <div>
    <div class="main-container">
      <div class="title-wrapper">
        <h1 class="title">{{title}}</h1>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        title: 'perinola mágica'
      }
    }
  }
</script>

<style lang="scss" scoped>
.main-container {
  padding: 2rem;
  border: 1px solid #ddd;
  margin: 1rem;
}
</style>