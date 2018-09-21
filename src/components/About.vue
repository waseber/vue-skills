<template>
    <div class="about">
        <h1>Hello {{their_name }}, this is the about page</h1>
        <p>Blah blah blah</p>
    </div>
</template>

<script>
export default {
    data() {
        return{
            their_name: this.$route.params.name
        }
    }
}
</script>
