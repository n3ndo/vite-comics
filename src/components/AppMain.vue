<script>
export default {

}
</script>
<template lang="">
    <main>
        <div class="top-main">
            <div class="container">
                <h2>--> Content goes here <--</h2>
            </div>
        </div>
        <div class="bottom-main">
            <div class="container">
                <ul>
                    <li><img src="../img/buy-comics-digital-comics.png" alt=""><a href="#">digital comics</a></li>
                    <li><img src="../img/buy-comics-merchandise.png" alt=""><a href="#">dc merchandise</a></li>
                    <li><img src="../img/buy-comics-subscriptions.png" alt=""><a href="#">subscriptions</a></li>
                    <li><img src="../img/buy-comics-shop-locator.png" alt=""><a href="#">comic shop locator</a></li>
                    <li><img src="../img/buy-dc-power-visa.svg" alt=""><a href="#">dc power visa</a></li>
                </ul>
            </div>
        </div>
    </main>
</template>
<style lang="scss" scoped>
main {
    background-color: #000;

    h2 {
        color: #fff;
        padding: 40px 0px;
    }

    .bottom-main{
        background-color: rgba(2,130,249,255);
        padding: 30px 0px;
        ul {
            list-style-type: none;
            display: flex;
            justify-content: space-around;
            align-items: center;
    
            li {
                display: flex;
                align-items: center;
                padding: 0px 10px;
                
                a{
                    color: #fff;
                    padding: 0px 10px;
                    text-transform: uppercase;
                    font-size: 12px;
                }
                img {
                    width: 50px;
                }
            }
        }
    }
}</style>