<template>
    <a class="nav-item" :href="to">
        {{ text }}
    </a>
</template>

<script>
export default {
    props:{
        text:{ type: String, required: true },
        to: { type: String, required: true }
    }
}
</script>

<style scoped>
.nav-item  {
    color: var(--color-grey-light);
    text-decoration: none;
    font-size: 1.3rem;
}

</style>