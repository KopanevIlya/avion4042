<template>

    <div class="card">
        <img class="card_img" :src="require('@/assets/image/'+item.icons)">   
        <!-- <h6>{{item.icons }}</h6> -->
        <h2 class="title_h2">{{item.titli_one}}</h2>
        <h3 class="title_h3">{{item.title_two}}</h3>
    </div>

</template>



<script>

    export default{
        name: 'DescriptionData',
        props:['item']
    } 

</script>



<style>

    .card{        
        width: 250px;
        height: 244px;
        background-color: rgba(249,249,249,1);
        margin-left: 30px;               
    }

    .card_img{
        margin-top:50px;
        margin-left: 30px;
    }

    .title_h2{
        margin-top: 20px;
        margin-left: 30px;
        font:15px sans-serif;
    }

    .title_h3{
        margin-top: 25px;
        font:13px sans-serif;
        flex-wrap: wrap;
        margin-left: 30px;
      
    }

</style>