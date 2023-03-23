<!-- JS  -->
<script>
// IMPORTO I SOTTOCOMPONENTI 
import FooterLogo from './FooterLogo.vue';
import FooterMenu from './FooterMenu.vue';
import FooterSocial from './FooterSocial.vue';
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    components: {
        FooterLogo,
        FooterMenu,
        FooterSocial
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
    <div class="container">
        <div class="content">
            <div class="menu">
                <FooterMenu></FooterMenu>
            </div>

            <div class="logo">
                <FooterLogo></FooterLogo>
            </div>
        </div>
        <div class="contacts">
            <FooterSocial></FooterSocial>
        </div>
    </div>
</template>

<!-- SCSS  -->
<style lang="scss" scoped >
.container {
    .content {
        max-width: 1500px;
        margin: auto;
        display: flex;
        position: relative;
        overflow: hidden;

        .menu {
            z-index: 1;
        }

        .logo {
            position: absolute;
            right: 0;
            top: -80px;
        }
    }

    .contacts {
        background-color: red;
    }
}
</style>