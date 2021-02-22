<template>
  <nav class="navbar">
      <Logo/>
      <SearchBar />
      <Navegation/>
      <User/>
  </nav>
</template>

<script>
import {Navegation, SearchBar} from '@/components/molecules'
import {User, Logo} from '@/components/atoms'
export default {
    components:{
        Navegation,
        SearchBar,
        User,
        Logo
    }

}
</script>

<style scoped>
.navbar{
    display: grid;
    grid-auto-flow: column;
    grid-template-columns: 120px repeat(2, 1fr) 120px;
    justify-items: center;
    align-items: center;
    width: 100vw;
    padding: 20px 40px;
}

</style>