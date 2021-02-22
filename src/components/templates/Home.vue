<template>
  <div class="container">
      <div class="nav-container">
          <Navbar/>
      </div>
      
      <div class="content">
        <NavCategories/>
        <MoviesTops/>
      </div>
      
  </div>
</template>

<script>
import {MoviesTops, Navbar} from '@/components/organisms'
import {NavCategories} from '@/components/molecules'

export default {
    components: {
        NavCategories,
        MoviesTops,
        Navbar
    }
}
</script>

<style>
.nav-container{
    margin: 20px 0;
}
.content{
    display: grid;
    grid-gap: 20px;
    align-items: center;
    justify-items: center;
}
</style>