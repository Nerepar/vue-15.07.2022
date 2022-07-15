<template>

    <ListDisplay :list="list"/>
    <ListControl @changeList="changeList"/>
</template>

<script>
    import ListControl from "@/components/Window/ListController/ListControl";
    import ListDisplay from "@/components/Window/ListController/ListDisplay";

    export default {
        name: "ListController",
        components: {
            ListControl, ListDisplay
        },
        data() {
            return {
                list: []
            }
        },
        methods: {
            changeList(item) {
                this.list.push(item);
            }
        }
    }
</script>

<style scoped>

</style>