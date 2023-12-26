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
                <a href="#">
                    <h4>SIGN-UP NOW!</h4>
                </a>
            </div>

            <div class="icons-col">
                <h4>FOLLOW US</h4>
                <div class="icons">
                    <a href="#">
                        <img src="../assets/img/footer-facebook.png" alt="">
                    </a>
                    <a href="#">
                        <img src="../assets/img/footer-twitter.png" alt="">
                    </a>
                    <a href="#">
                        <img src="../assets/img/footer-youtube.png" alt="">
                    </a>
                    <a href="#">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </a>
                    <a href="#">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </a>
                </div>
            </div>
        </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use'../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *; 

.row{
    width: 80%;
    margin: 0 auto;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.sign-in-col{
    border: 1px solid #0089ff;

    h4{
        padding: 15px;
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
