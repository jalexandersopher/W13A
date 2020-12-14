<template>
    <div>
        <h1>This is the Body Component!</h1>
        <sub-component-one></sub-component-one>
        <sub-component-two></sub-component-two>
        <sub-component-three></sub-component-three>
    </div>
</template>

<script>
import SubComponentOne from "../components/subComponentOne.vue";
import SubComponentTwo from "../components/subComponentTwo.vue";
import SubComponentThree from "../components/subComponentThree";
    export default {
        name: "BodyComponent",
        components: {
            SubComponentOne,
            SubComponentTwo,
            SubComponentThree,
        }
    }
</script>

<style lang="scss" scoped>

</style>