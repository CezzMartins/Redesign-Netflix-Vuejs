<template>
  <div class="nav-items">
      <NavItem text='Home' to="/home"/>
      <NavItem text='Movies' to="/movies"/>
      <NavItem text='Series' to="/series"/>
      <NavItem text='My List' to="/my-list"/>
  </div>
</template>

<script>
import { NavItem } from '@/components/atoms'
export default {
    components: {
        NavItem
    }

}
</script>

<style scoped>
.nav-items{
    width: max-content;
    display: grid;
    grid-auto-flow: column;
    grid-gap: 3rem; 
}

</style>