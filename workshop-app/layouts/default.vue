<template>
  <div id="root">
    <Navigation/>

    <div id="main-wraper">
      <main>
      <Nuxt/>
      </main>
    </div>

    <!-- TODO: Footer -->
    <Footer/>
    
  </div>
</template>

<script>
export default {}
</script>

<style scoped>

#root {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}


#main-wraper{
  display: flex;
  justify-content: center;
}

</style>