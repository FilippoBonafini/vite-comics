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
@use 'src/styles/Variables.scss' as *;

.sectionContainer {
    font-size: 40px;
    color: $my-white;
    background-color: $my-black;


    .content {
        max-width: $my-container-max-width;
        margin: auto;
        padding: 50px 0;
    }
}
</style>