<script>
export default {
    data(){
        return {
            links: ['characters', 'comics', 'movies', 'tv', 'games', 'collectibles', 'videos', 'fans', 'news', 'shop']
        }
    }
}
</script>
<template lang="">
    <header>
        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <a href="/">
                        <img src="../img/dc-logo.png" alt="lgo dc">
                    </a>
                </div>
                <div class="menu">
                    <ul>
                        <li v-for="link, index in links" :key="index"><a href="#" :class="index == 1 ? 'active' : ''">{{ link }}</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss">
@use '../styles/generals.scss' as *;
@use '../styles/partials/variables' as *;

.navbar {
    display: flex;
    justify-content: space-between;
    padding: 20px 0px;

    .logo {
        a {
            img {
                width: 80px;
                vertical-align: middle;
            }
        }
    }

    ul {
        list-style-type: none;
        margin: 0;
        display: flex;

        li {
            display: inline-block;

            a {
                text-transform: uppercase;
                color: #000;
                padding: 0px 10px;
                line-height: 80px;
                font-weight: 600;
                position: relative;

                &.active,
                &:hover {
                    color: $primary_color;

                    &::after {
                        content: '';
                        position: absolute;
                        top: 30px;
                        bottom: 0;
                        left: 10px;
                        width: calc(100% - 20px);
                        height: 5px;
                        background-color: $primary_color;
                    }
                }


            }
        }
    }
}
</style>