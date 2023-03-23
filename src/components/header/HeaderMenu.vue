<!-- JS  -->
<script>
// DICHIARO COSA VOGLIO ESPORTARE 
export default {
    // STRUTTURA CLASSICA DI VUE 
    data() {
        return {
            menu: [
                {
                    text: 'Characters',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Comics',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Movies',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'TV',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Games',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Collectibles',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Videos',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Fans',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'News',
                    link: '#',
                    terget: '_blank'
                },
                {
                    text: 'Shop',
                    link: '#',
                    terget: '_blank'
                },
            ]
        }
    }
}
</script>

<!-- HTML  -->
<template>
    <nav>
        <ul>
            <li v-for="element in menu"><a :href="element.link">{{ element.text }}</a></li>
        </ul>
    </nav>
</template>

<!-- SCSS  -->
<style lang="scss" scoped >
nav {
    ul {
        display: flex;

        li {
            text-transform: uppercase;
            display: inline-block;
            padding: 50px 20px;

            &:hover {
                cursor: pointer;
                border-bottom: 10px inset blue;
            }

            &:hover a {
                color: blue;
            }
        }
    }
}
</style>