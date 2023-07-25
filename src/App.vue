<script setup lang="ts">

</script>

<template>
  <div class="main-container">
    <img class="me" src="./assets/me.webp" alt="Photo of Pieter Bikkel">  
    <div class="content">
      <h1>Pieter Bikkel</h1>
      <h2>Fullstack Developer</h2>
      <div class="socials">
        <a href="https://www.instagram.com/bikkelpieter/" target="_blank">
          <img src="./assets/instagram.svg" alt="Instagram">  
        </a>
        <a href="https://x.com/pieterbikkel" target="_blank">
          <img src="./assets/x.svg" alt="X (twitter)">  
        </a>
        <a href="https://github.com/pieterbikkel" target="_blank">
          <img src="./assets/github.svg" alt="Github">  
        </a>
      </div>
    </div>    
  </div>
</template>

<style scoped>

.main-container {
  display: flex;
  column-gap: 5rem;
  align-items: center;
}

.socials {
  display: flex;
  column-gap: 2rem;
}
.me {
  width: 550px;
  height: 550px;
  object-fit: cover;
  border-radius: 50%;
}

@media only screen and (max-width: 1240px) {
  .me {
      width: 350px;
      height: 350px;
  }
}

@media only screen and (max-width: 970px) {
  .main-container {
    flex-direction: column;
    row-gap: 2rem;
    align-items: center;
  }

  .content {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .me {
      width: 300px;
      height: 300px;
  }
}

@media only screen and (max-width: 350px) {
  .me {
      width: 250px;
      height: 250px;
  }
}

</style>
