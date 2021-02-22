<template>
    <button class="btn">{{categorie.title}}</button>
</template>

<script>
export default {
    props:['categorie']
}
</script>

<style>
.btn {
    background-color: var(--color-grey-medium);
    width: 150px;
    height: 50px;
    color: var(--color-grey-light);
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
.btn:hover{
    background-color: var(--color-red-light);
}
.danger{
    background-color: var(--color-red-light);
}

</style>