<!-- JS  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA CLASSICA DI VUE 
    data() {
        return {

        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="jumbo">
    </div>
</template>

<!-- SCSS  -->
<style lang="scss" scoped >
@use 'src/styles/Variables.scss' as *;

.jumbo {
    background-image: url('img/background/jumbotron.jpg');
    background-size: cover;
    min-height: 500px;
}
</style>