<template>
  <div class="container">
    <h1 class="title">DINO FUN LAND</h1>
    <div class="links">
      <router-link to="/dino-jump" class="link">Play Dino Jump &#8594</router-link>
      <router-link to="/dino-jump-ranking" class="link">Ranking Dino Jump &#8594</router-link>
    </div>
    <!--<router-link to="/dino-jump-demo">Go To Dino Jump Demo &#8594</router-link>-->
  </div>
</template>
<script setup lang="ts">
</script>
<style scoped>
.title {
  font-size: clamp(2.4rem, 5vw, 6.4rem);
  text-shadow: 7px 7px #5a265e;
}
.container {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 10px;
}

.links {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.link {
  display: inline-block;
  border: 1px solid;
  font-size: clamp(1.6rem, 2vw, 2.4rem);
  padding: 1em;
  text-align: center;
}

@media screen and (max-width: 819px) {
  .title {
    text-shadow: 5px 5px #5a265e;
  }
}
</style>