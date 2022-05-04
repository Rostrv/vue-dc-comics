<template>
<div class="col-2 p-0">
    <div class="comic-container" style="width: 200px">
        <img class="" :src="img"/>
          <div class="p-1">
            
           <p class=" text-white text-uppercase">{{text}}</p>
           
          </div>
      </div>    
</div>
      
</template>

<script>
export default {
    name:'cards-items',
    props: {
        img: String,
        text: String,
    }
}

</script>

<style lang="scss" scoped>

img{
    width: 200px;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    object-position: top;
}

</style>
