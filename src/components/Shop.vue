<script>


</script>

<template>
   <div class="container">
        <div class="row">
            <div class="box-container">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <h4>Digital comics</h4>
            </div>
            <div class="box-container">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <h4>Digital comics</h4>
            </div>
            <div class="box-container">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <h4>Digital comics</h4>
            </div>
            <div class="box-container">
                <img class="shrink" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <h4>Digital comics</h4>
            </div>
            <div class="box-container">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <h4>Digital comics</h4>
            </div>
        </div>
   </div>
</template>

<style lang="scss" scoped>
    .container{
        background-color: #0282f9;
        min-height: 170px;
        display: flex;
        justify-content: center;
        align-items: center;

        h4{
            color: white;
        }
    }

    .row{
        width: 70%;
        display: flex;
    }

    .box-container{
        margin: 0 30px;
        display: flex;
        align-items: center;

        img{
            width: 60px;
            margin-right: 10px;
        }

        .shrink{
            width: 45px;
        }
    }
</style>