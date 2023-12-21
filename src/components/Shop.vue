<script>
export default{
  name: "Shop",
  data() {
    return {
    
    }
  }
}

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
        min-height: 120px;
        display: flex;
        justify-content: center;

        h4{
            color: white;
        }
    }

    .row{
        width: 80%;
        display: flex;
        justify-content: space-between;
    }

    .box-container{
        margin: 0 30px;
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