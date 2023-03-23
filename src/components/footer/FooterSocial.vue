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
    <div class="container">
        <div class="content">
            <div class="button">button</div>
            <div class="social">social</div>
        </div>
    </div>
</template>

<!-- SCSS  -->
<style lang="scss" scoped >
.container {
    max-width: 1500px;
    margin: auto;

    .content {
        display: flex;
        justify-content: space-between;
    }
}
</style>