<template>
    <div>
        <h1>I am Home!</h1>
        <h1>I am {{ name }} and I am {{ age }} years old</h1>
    </div>
</template>

<script>
export default {
    name:"Home",
    data() {
        return {
            name: "Sai Win Oo",
            age : 17,
        }
    },
}
</script>

<style scoped>

</style>
