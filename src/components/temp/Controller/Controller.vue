<template src="template.html">

</template>

<script>
    import Display from "@/components/temp/Display/Display";
    import Input from "@/components/temp/Input/Input";

    export default {
        name: "v-Controller",
        components: {
            Display, Input
        },
        data() {
            return {
                value: "",
            }
        },
        methods: {
            inputText(text) {
                this.value = text;
            },
        }
    }
</script>

<style scoped>

</style>