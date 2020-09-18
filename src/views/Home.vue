<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Welcome to Click Map</h1>
    <p>
      Instructions go here
      <font-awesome-icon icon="map-pin" />
    </p>
  </div>
</template>

<script>
export default {
  // TODO what does this do?
  name: 'Home',
};
</script>

<style scoped>
.home {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: 100%;
  justify-content: center;
  padding: 1rem;
}
</style>
