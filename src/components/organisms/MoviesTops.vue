<template>
    <div class="container wrapper">
        <Movies/>
        <Tranding/>
    </div>
  
</template>

<script>
import {Tranding, Movies} from '@/components/molecules'
export default {
    components: {
        Tranding,
        Movies
    }
}
</script>

<style scoped>
.wrapper{
    display: grid;
    grid-auto-flow: column;
    width: max-content;
    grid-gap: 30px;
}

</style>