<template>
  <main>

    <video autoplay muted loop id="backgroundVideo">
      <source src="../assets/arcanepadPromoVideo.mp4" type="video/mp4">
    </video>

    <div class="infographic-container">
      <img src="../assets/infographic.png" alt="infographics">
    </div>

  </main>
</template>

<script setup lang="ts">



</script>

<style>
body,
html {
  height: 100%;
  margin: 0;
  overflow-x: hidden;
  /* background-color: black; */
  color: cyan;
}

#backgroundVideo {
  position: fixed;
  min-width: 100%;
  min-height: 100%;
  width: 100vw;
  height: 100vh;
  z-index: -1;
  object-fit: cover;
}

#backgroundVideo {
  width: 100%;
}

.infographic-container {
  background-color: rgba(0, 0, 0, 0.7);
  padding: 3em 5% 5em 5%;
  margin: auto;
  text-align: center;
}

.infographic-container img {
  width: 100%;
  height: auto;
  max-width: 100%;
  max-width: 1200px;

  /* Adjust this value to your needs */
}
</style>
