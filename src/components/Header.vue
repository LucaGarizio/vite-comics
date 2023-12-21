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
            <a href="">collectibles</a>
          </li>
          <li>
            <a href="">videos</a>
          </li>
          <li>
            <a href="">fans</a>
          </li>
          <li>
            <a href="">news</a>
          </li>
          <li>
            <a href="">shop</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
  .row{
    margin-top: 20px;
    height: 130px;
    background-color: #fff;
    border: 1px solid white;
    display: flex;
  }
  .logo-col{
    width: 20%;
    display: flex;
    justify-content: end;
    align-items: center;

    img{
      width: 90px;
    }
  }
  .nav-col{
    width: 80%;
    display: flex;
    justify-content: center;
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

          &:hover{
            color: #0077f8;
          }
        }
      }
  }

</style>
