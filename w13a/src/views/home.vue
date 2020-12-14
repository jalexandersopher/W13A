<template>
    <div>
        <header-component></header-component>
        <body-component></body-component>
        <footer-component></footer-component>
    </div>
</template>

<script>
import HeaderComponent from '../components/headerComponent.vue';
import BodyComponent from '../components/bodyComponent.vue';
import FooterComponent from '../components/footerComponent.vue';
export default {
    name: "Home",
    components: {
        HeaderComponent,
        BodyComponent,
        FooterComponent
    }
}
</script>

<style scoped>

</style>