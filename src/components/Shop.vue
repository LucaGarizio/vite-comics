<script>
export default{
  name: "Shop",
}

</script>

<template>
   <div class="container">
        <div class="row">
            <div class="box-container">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <h5>Digital comics</h5>
            </div>
            <div class="box-container">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <h5>dc merchandise</h5>
            </div>
            <div class="box-container">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <h5>subscription</h5>
            </div>
            <div class="box-container">
                <img class="shrink" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <h5>comic shop locator</h5>
            </div>
            <div class="box-container">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <h5>dc power visa</h5>
            </div>
        </div>
   </div>
</template>

<style lang="scss" scoped>
@use'../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *; 


    .container{
        background-color: #0282f9;
        height: 150px; 
        display: flex;
        justify-content: center;
    }

    .row{
        width: 85%;
        display: flex;
        justify-content: space-between;
    }

    .box-container{
        margin: 0 40px;
        display: flex;
        align-items: center;

        img{
            width: 50px;
            margin-right: 10px;
        }

        .shrink{
            width: 40px;
        }
    }
</style>