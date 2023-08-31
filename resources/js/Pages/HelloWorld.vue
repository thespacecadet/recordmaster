<template>
    <nav-bar></nav-bar>
    <div class="bg-sky-50">
        <p class="text-2xl text-green-900 font-bold underline">Hello World!</p>
        <p>{{ message }}</p>
    </div>
</template>

<script>
import NavBar from "../Components/NavBar.vue";

export default {
    name: "HelloWorld",
    components: {NavBar},
    props: {
        message: {
            type: String,
            required: true
        }
    }
}
</script>

<style scoped>
</style>
