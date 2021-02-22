<template>
  <div class="user">
      <img src="@/assets/images/user.jpg" alt="">
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.user{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 60px;
    height: 60px;
    overflow: hidden;
    border: 2px solid var(--color-red-light);
    border-radius: 50%;
    padding: 10px;
}
img{
    width: 50px;
    border-radius: 50%;
}
</style>