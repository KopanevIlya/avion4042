<template>
    <div>
        <h2 class="title_h8">{{foot.titli_meny}}</h2>
        <h3 class="title_h9">{{foot.title_one}}</h3>
        <h3 class="title_h4">{{foot.title_three}}</h3>
        <h3 class="title_h5">{{foot.title_four}}</h3>
        <h3 class="title_h6">{{foot.titlt_five}}</h3>
        <h3 class="title_h7">{{foot.title_six}}</h3>

    </div>


</template>

<script>

export default{

name: 'DescriptionItems',
props:['foot']

}

</script>

<style>

.title_h8{
    color: white;
    margin-top: 60px;
    margin-left: 150px;
    font-family: sans-serif;
    font-size: 18px;
}
.title_h9{
    color: white;
    margin-left: 150px;
    font-family: sans-serif;
    font-size: 14px;
    margin-top: 30px;
}
.title_h4{
    color: white;
    margin-left: 150px;
    font-family: sans-serif;
    font-size: 14px;
    margin-top: 15px;
}
.title_h5{
    color: white;
    margin-left: 150px;
    font-family: sans-serif;
    font-size: 14px;
    margin-top: 15px;
}
.title_h6{
    color: white;
    margin-left: 150px;
    font-family: sans-serif;
    font-size: 14px;
    margin-top: 15px;
    
}
.title_h7{
    color: white;
    margin-left: 150px;
    font-family: sans-serif;
    font-size: 14px;
    margin-top: 15px;
}







</style>