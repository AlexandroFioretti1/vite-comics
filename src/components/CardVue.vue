<script>
    export default {
        name: "CardVue",
        props: {
            img: String,
            title: String,
        }
    }
</script>

<template>
 <h1>{{ img }}</h1>
 <h1>{{ title }}</h1>
</template>



<style lang="scss" scoped>

</style>