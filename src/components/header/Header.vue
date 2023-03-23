<!-- JS  -->
<script>
// IMPORTO I SOTTOCOMPONENTI 
import HeaderLogo from './HeaderLogo.vue';
import HeaderMenu from './HeaderMenu.vue';
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    components: {
        HeaderLogo,
        HeaderMenu
    },
    // STRUTTURA CLASSICA DI VUE 
    data() {
        return {

        }
    }
}
</script>

<!-- HTML  -->
<template>
    <HeaderLogo></HeaderLogo>
    <HeaderMenu></HeaderMenu>
</template>

<!-- SCSS  -->
<style lang="scss" scoped ></style>