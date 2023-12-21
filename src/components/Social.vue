<script>
export default{
  name: "Social",
  data() {
    return {
    
    }
  }
}
</script>

<template>
  <footer>
    <div class="container">
        <div class="row">
            <div class="sign-in-col">
                <h4>SIGN-UP NOW!</h4>
            </div>

            <div class="icons-col">
                <h4>FOLLOW US</h4>
                <div class="icons">
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer{
    background-color: #303030;
}
.row{
    width: 80%;
    margin: 0 auto;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 20px;
}
.sign-in-col{
    border: 1px solid #0089ff;

    h4{
        padding: 15px;
        color: white;
    }
}
.icons-col{
    display: flex;
    justify-content: center;
    align-items: center;
    
        h4{
            color: #0089ff;
            margin-right: 10px;
            
        }
            img{
                width: 30px;
                margin-left: 15px;
            }
}
</style>
