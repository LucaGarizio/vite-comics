<script>
export default{
  name: "CardBoxes",
  props: {
    details: Object,
  }
 
}
</script>

<template>
    <div class="box">
        <img :src="details.thumb" :alt="details.series">
        <div class="text-box">
            <h5>{{ details.series }}</h5>
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use'../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *; 

    .box{
        flex-basis: 10%;
        height: 280px;
        padding: 0 10px;
    
        img{
            width: 200px;
            height: 200px; 
        }

        .text-box{
            text-transform: uppercase;
            
            h5{
                padding-top: 10px;
            }
        }
    }
    
</style>