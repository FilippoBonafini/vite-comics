<!-- JS  -->
<script>
// IMPORTO I SOTTOCOMPONENTI 
import MainMenu from './MainMenu.vue';
import MainSectionEmpty from './MainSectionEmpty.vue';
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    components: {
        MainMenu,
        MainSectionEmpty
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
    <MainSectionEmpty></MainSectionEmpty>
    <MainMenu></MainMenu>
</template>

<!-- SCSS  -->
<style lang="scss" scoped ></style>