<script>
export default{
  name: "Jumbo",
 
}

</script>

<template>
    <div class="row">
        <div class="jumbo">

        </div>
    </div>
</template>

<style lang="scss" scoped>
@use'../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *; 

    .row{
       width: 100%;
    }

    .jumbo{
        background-image: url('../assets/img/jumbotron.jpg');
        height: 400px;
        background-size: cover;
    }

</style>
