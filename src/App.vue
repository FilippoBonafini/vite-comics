<!-- JS  -->
<script>
// IMPORTO I SOTTOCOMPONENTI 
import Header from './components/header/Header.vue';
import Main from './components/main/Main.vue';
import Footer from './components/footer/Footer.vue';
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    components: {
        Header,
        Main,
        Footer
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
    <div class="body">
        <header>
            <Header></Header>
        </header>

        <main>
            <Main></Main>
        </main>

        <footer>
            <Footer></Footer>
        </footer>

    </div>
</template>

<!-- SCSS  -->
<style lang="scss">
// RESET DOCUMENTO
@use './styles/Reset.css' as *;

.body {
    display: flex;
    flex-direction: column;
    height: 400px; //DEBUG 

    header {
        background-color: blue;
    }

    main {
        background-color: red;
        flex-grow: 1;
    }

    footer {
        background-color: yellow;
    }
}
</style>
