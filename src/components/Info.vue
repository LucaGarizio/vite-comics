<script>
export default{
  name: "Info",
  data() {
    return {
    
    }
  }
}
</script>

<template>
    <section>
        <div class="row">
            <div class="col">
                <h3>DC COMICS</h3>
                <ul>
                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li>
                        <a href="">comics</a>
                    </li>
                    <li>
                        <a href="">movies</a>
                    </li>
                    <li>
                        <a href="">tv</a>
                    </li>
                    <li>
                        <a href="">games</a>
                    </li>
                    <li>
                        <a href="">videos</a>
                    </li>
                    <li>
                        <a href="">news</a>
                    </li>
                </ul>

                <h3>SHOP</h3>
                <ul>
                    <li>
                        <a href="">Shop DC</a>
                    </li>
                    <li>
                        <a href="">shop DC Collectibles</a>
                    </li>
                </ul>
            </div>
            <div class="col">
                <h3>DC</h3>
                <ul>
                    <li>
                        <a href="#">Term Of Use</a>
                    </li>
                    <li>
                        <a href="">Privacy policy(New)</a>
                    </li>
                    <li>
                        <a href="">Ad Choices</a>
                    </li>
                    <li>
                        <a href="">Advertising</a>
                    </li>
                    <li>
                        <a href="">Jobs</a>
                    </li>
                    <li>
                        <a href="">Subscriptions</a>
                    </li>
                    <li>
                        <a href="">Talent Workshops</a>
                    </li>
                    <li>
                        <a href="">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="">Rating</a>
                    </li>
                    <li>
                        <a href="">Shop Help</a>
                    </li>
                    <li>
                        <a href="">Contact US</a>
                    </li>
                </ul>
            </div>
            <div class="col">
                <h3>SITES</h3>
                <ul>
                    <li>
                        <a href="">DC</a>
                    </li>
                    <li>
                        <a href="">MAD Magazine</a>
                    </li>
                    <li>
                        <a href="">DC Kids</a>
                    </li>
                    <li>
                        <a href="">SUniverse</a>
                    </li>
                    <li>
                        <a href="">DC Power Visa</a>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    section{
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
    }
    .row{
        width: 80%;
        margin: 0 auto;
        display: flex;
        background-image: url('../assets/img/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position-x: 100%;
        background-position-y: 50%;
        background-size: 40%;

        ul{
            list-style: none;

            li{
                margin-bottom: 5px;
            }
            
            a{
                text-decoration: none;
                color: #6e6e65;

                &:hover{
                    color: #fff;
                }
            }
        }
    }
    h3{
        color: white;
        margin: 20px 0;
    }

    .col{
        margin:  40px 40px 50px 0;
    }
</style>
