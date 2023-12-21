<script>
export default{
  name: "MainContent",
  data() {
    return {
    
    }
  }
}

</script>

<template>
    <div class="row">
        <h2>
        Content goes here
        </h2>
    </div>
</template>

<style lang="scss" scoped>
    .row{
        display: flex;
        justify-content: start;
        align-items: center;
        width: 80%;
        margin: 0 auto;
        min-height: 150px;

        h2{
            color: white;
        }
    }
</style>
