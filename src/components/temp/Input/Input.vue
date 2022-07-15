<template src="template.html">
    
</template>

<script>
    export default {
        name: "v-Input",
        methods: {
            inputText() {
                this.$emit('inputText', this.value);
            }
        },
        data() {
            return {
                value: ""
            }
        }
    }
</script>

<style scoped>

</style>