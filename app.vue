<template>
  
  <div class="background-container z-0">
    <NavBar/>
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
  </div>
  <Footer/>
</template>

<style scoped>
.background-container {
  background-image: url('./assets/bg.png');
  background-size: cover;
  background-position: center;
  min-height: 100vh;
}
</style>


