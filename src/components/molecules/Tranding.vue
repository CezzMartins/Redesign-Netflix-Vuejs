<template>
  <div class="tranding">
      <h1>Movies of The Month</h1>
      <hr class="hr">
      <div class="tranding-movies">
         <div class="tranding-item" v-for="top in topMovies" :key="top.id">
             <div class="id">{{ top.id }}</div>
             <h3 class="item">{{ top.title }}</h3>
         </div>
      </div>
      

  </div>
</template>

<script>
export default {
    data(){
        return{
            topMovies: [
                {id: 1, title: 'Avenger Infinity War'},
                {id: 2, title: 'Alexandra'},
                {id: 3, title: 'Tomb Raider'},
                {id: 4, title: 'Not Out'},
                {id: 5, title: 'Sherlock Molmes'},
                {id: 6, title: 'SickLove'},
                {id: 7, title: 'How I Met your Mother'},
                {id: 8, title: 'Friends'},
                {id: 9, title: 'Friends'},
                {id: 10, title: 'Friends'},
            ]
        }
    }

}
</script>

<style scoped>
h1{ 
    margin: 0;
    padding-top: 25px ;

}
.hr{
    color: var(--color-red-light);
    width: 50%;
    padding:0;
    margin: 5px 0;
}
.tranding-movies{
    margin: 0;
    padding: 0;
}
.tranding{
    display: grid;
    padding: 20px;
    border-radius: 10px;
    justify-items: center;
    background-color: var(--color-blue-medium);
    color: var(--color-grey-light);
    width: max-content;
}
.tranding-item{
    width: 100%;
    /* text-align: center; */
    border-top: 1px var(--color-grey-light) solid;
    display: flex;
    justify-items: center;
    align-items: center;
}
.item{
    padding: 10px 0;
    align-self: center;
}
.item:hover{
    color: var(--color-red-light);
    cursor: pointer;
}
.id{
    width: 30px;
    height: 30px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-right: 40px;
    border: 1px var(--color-grey-light) solid;
}

</style>