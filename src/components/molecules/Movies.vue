<template>
  <div class="movies-container">
      <div class="movies-top">
          <img class="movies-img-top" src="@/assets/images/movie_06.jpg" alt="">
      </div>
      <div class="movies-okay">
          <img class="movies-img" src="@/assets/images/movie_01.jpg" alt="">
          <img class="movies-img" src="@/assets/images/movie_02.jpg" alt="">
          <img class="movies-img" src="@/assets/images/movie_03.jpg" alt="">
          <img class="movies-img" src="@/assets/images/movie_07.jpg" alt="">
          <img class="movies-img" src="@/assets/images/movie_05.jpg" alt="">
          <img class="movies-img" src="@/assets/images/movie_04.jpg" alt="">
      </div>
      
  </div>
</template>

<script>
export default {

}
</script>

<style>
.movies-container{
    display: grid;
    grid-auto-flow: column;
    width: max-content;
    grid-template-columns: auto;
    grid-gap: 10px;
}
.movies-img-top{
    height: 660px;
    border-radius: 10px;
}
.movies-okay{
    display: grid;
    grid-template-columns: repeat(3, 200px);
    grid-template-rows: auto;
    width: max-content;
    grid-gap: 10px;
    
}
.movies-img{
    width: 200px;
    height: 320px;
    border-radius: 10px;
    
}
img:hover{
    opacity: 0.6;
    cursor: pointer;
}


</style>