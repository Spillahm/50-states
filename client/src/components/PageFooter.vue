<template>
  <div>

    <div id="navigation-links">


      <span class="nav-link">
      <router-link to="/">Home</router-link>
      </span>

      <span class="nav-link">

    <router-link to="about">About this site</router-link>
      </span>

    <p>Header image by
      <a href="https://unsplash.com/photos/KpBXAOs80YI">@chrislawton on Unsplash</a>
    </p>

      </div>
  </div>
</template>

<script>
export default {
  name: 'PageFooter'
}
</script>

<style scoped>
.nav-link {
  margin: 1rem;
}
</style>