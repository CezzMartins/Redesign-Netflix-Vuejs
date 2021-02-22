<template>
  <form class="search-bar">
      <input class="search-input" placeholder="Find your movie....">
      <button class="search-button">B</button>
  </form>
</template>

<script>
export default {

}
</script>

<style scoped>
.search-bar{
    position: relative;
    width: max-content;
    display: flex;
    align-items: center;
}
.search-input{
    background-color: var(--color-grey-light);
    border: none;
    border-radius: 40px;
    color: var(--color-blue-dark);
    padding: 1rem;
    height: 2rem;
    width: 20rem;
    outline: none;
}
.search-button{
    position: absolute;
    right: 2px;
    background-color: var(--color-red-light);
    border-radius: 50%;
    width: 1.7rem;
    height: 1.7rem;
    color: var(--color-grey-light);
    border: none;
    cursor: pointer;
    outline: none;
}

</style>