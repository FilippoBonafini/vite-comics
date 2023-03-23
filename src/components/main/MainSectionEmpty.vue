<!-- JS  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA CLASSICA DI VUE 
    data() {
        return {
            text: '-->Content goes here<--'
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <div class="sectionContainer">
        <div class="content">{{ text }}</div>
    </div>
</template>

<!-- SCSS  -->
<style lang="scss" scoped >
.sectionContainer {
    font-size: 40px;
    color: white;
    background-color: black;


    .content {
        max-width: 1500px;
        margin: auto;
        padding: 50px 0;
    }
}
</style>