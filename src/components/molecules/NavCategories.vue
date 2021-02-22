<template>
    <div class="nav-item-categories">
        <ButtonCategories v-for="categorie in categories" :key="categorie.id" :categorie="categorie"/>
    </div>
</template>

<script>
import {ButtonCategories} from '@/components/atoms'
export default {
    components: {
        ButtonCategories
    },
    data(){
        return{
            categories: [
                {id: 1, title: 'All', danger: true},
                {id: 2,title: 'Action', danger: false},
                {id: 3,title: 'Adventure', danger: false},
                {id: 4,title: 'Animation', danger: false},
                {id: 5,title: 'Comedy', danger: false},
                {id: 6,title: 'Documentary', danger: false},
                {id: 7,title: 'Drama', danger: false},
                {id: 8,title: 'family Movies', danger: false},
            ]
        }
    }

}
</script>

<style scoped>
    .nav-item-categories{
        display: grid;
        grid-auto-flow: column;
        width: max-content;
        grid-gap: 15px;
    }

</style>