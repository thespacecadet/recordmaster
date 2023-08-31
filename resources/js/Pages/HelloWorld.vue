<template>
    <div>
        <h1>Hello World!</h1>
        <p>{{ message }}</p>
    </div>
</template>

<script>
export default {
    name: "HelloWorld",
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
