<script>


</script>

<template>
  <nav>
    <div class="row">
      <div class="logo-col">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="nav-col">
        <ul>
          <li>
            <a href="#">CHARACTERS</a>
          </li>
          <li>
            <a href="">COMICS</a>
          </li>
          <li>
            <a href="">MOVIES</a>
          </li>
          <li>
            <a href="">TV</a>
          </li>
          <li>
            <a href="">GAMES</a>
          </li>
          <li>
            <a href="">COLLECTIBLES</a>
          </li>
          <li>
            <a href="">VIDEOS</a>
          </li>
          <li>
            <a href="">FANS</a>
          </li>
          <li>
            <a href="">NEWS</a>
          </li>
          <li>
            <a href="">SHOP</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
  nav{
    background-color: #fff;
  }
  .row{
    margin: 0 auto;
    margin-top: 20px;
    height: 100px;
    width: 80%;
    display: flex;
    justify-content: space-between;
  }
  .logo-col{
    display: flex;
    align-items: center;

    img{
      width: 70px;
    }
  }
  .nav-col{
    display: flex;
    justify-content: flex-end;
    align-items: center;

    ul{
      list-style-type: none;
      display: flex;
    }

      li{
        margin: 0 20px;

        a{
          text-decoration: none;
          color: #333;
          font-size: 13px;

          &:hover{
            color: #0077f8;
          }
        }
      }
  }

</style>
