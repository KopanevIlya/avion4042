<template>
    <!-- Разметка -->  
     <div>   
        <!-- <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=search,shopping_cart_checkout"/> -->

        <!-- <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=account_circle" /> -->

        <!-- <div class="container-navi">
            <h1 class="title-left">Avion</h1>   

            <div class="right">
            
                <div class="title-right">
                    <h6>About us</h6>
                    <h6>Contact</h6>
                    <h6>Blog</h6>

                </div>                    
                
                <div class="title-icon">
                    <span class="material-symbols-outlined">
                        search
                    </span>

                    <span class="material-symbols-outlined">
                        shopping_cart_checkout
                    </span>

                    <span class="material-symbols-outlined">
                        account_circle
                    </span>

                    <img src="img/контакты.png" alt="">
                    <img src="img/User--avatar.jpg" alt="">
          </div> 
          </div>
          </div>  -->
        </div> 
              

                
<!-- 
<div class="Bottom Bar">
    <div class="botton-navigation">
        <ul class="nav-list">
            <p class="nav-item">Plant pots</p>
            <p class="nav-item">Ceramics</p>
            <p class="nav-item">Tables</p>
            <p class="nav-item">Chairs</p>
            <p class="nav-item">Crockery</p>
            <p class="nav-item">Tableware</p>
            <p class="nav-item">Cutlery</p>
        </ul>
    </div> 
</div> -->

<div class="page-heder">

    <p class="title-page">A brand built on the love of craftmanship,<br/>
        quality and outstanding customer service
    </p>

    <button class="title-page-right">View our products</button>
    
</div>

<div class="Features">
    <div class="Features-left">
        <div class="Features-left-title">

            <h1 class="Features-left-title-h1">
                It started with a small idea
            </h1>

            <h3 class="Features-left-title-h3">
                A global brand with local beginnings, our story begain in a  
            </h3>

            <h3 class="Features-h3">small studio in South London in early 2014</h3>
        
            <div class="button">
                <button class="button_collectiion">View collection</button>
            </div>
        </div>          
    </div>

    <div class="Features-right">
        <!-- <img class="one" src="ProductV3.vue/aviontest/img/block.png" alt=""> -->
        <!-- <img class="one" :src="require('@/assets/img/block.png')" alt=""> -->
        <!-- <img class="one" src="assets/Features-right.jpeg" alt=""> -->
        <img class="Features-right-img" :src="require('@/assets/image/Features-right.png')" alt=""> 
             
    </div>     

</div>

<div class="Features-second">
        <div class="Features-second-left">
            <img class="Features-second-left-img" :src="require('@/assets/image/Features-second-right.png')" alt="">
            
        </div>

        <div  class="Features-second-right">
            <p class="Features-second-right-title0">Our service isn’t just personal, it’s actually</p>
            <p class="Features-second-right-title00">hyper personally exquisite</p>

            <div class="Features-second-right-title">
                <p>When we started Avion, the idea was simple. Make high quality furniture</p>
                 
                <p>affordable and available for the mass market.</p>
            </div>

            <div class="Features-second-right-title2">
                <p>Handmade, and lovingly crafted furniture and homeware is what we live,</p> 
                <p>breathe and design so our Chelsea boutique become the hotbed for the </p>
                <p>London interior design community.</p>                
            </div>    

                <button class="buttun-left">Get in touch</button>

            </div>     

</div> 

<div class="Feature-three">
    <h2 class="Feature-three-title">What makes our brand different</h2>

  
            <div class="card_title">
                <DescriptionData v-for="i in items"
                :key="i.id"
                :item="i"
                />
            </div>     

</div>

<div class="Email_sign_up">

        <div class="Email">

            <h1 class="Email_title">
                Join the club and get the benefits
            </h1>

            <H3 class="Email_basement">
                Sign up for our newsletter and receive exclusive offers on new 
            </H3>
            <H3 class="Email_basement2">
                ranges, sales, pop up stores and more
            </H3>
            
            <div class="Email_completion">
                <input class="email_input" type="Sign up" id="emailInput" placeholder="your@email.com">
                <button class="one" id="sendEmailButton">Sign up</button>
            </div>

        </div>
</div>

<div class="Footer">

    <div class="footot_one">
        <h1 class="footer_title">Avion</h1>

        <div class="footer_text"> 
            <h3 class="footer_title_1">21 New York Street</h3>
            <h3 class="footer_title_2">New York City</h3>
            <h3 class="footer_title_3">United States of America</h3>
            <h3 class="footer_title_4">432 34</h3>
        </div>

    </div>

    <div class="footer_two">

        <h3 class="footer_h3">Social links</h3>

        <div class="footer_title_5">
            <span class="material-symbols-outlined">language</span>    
            <span class="material-symbols-outlined">account_circle</span>
            <span class="material-symbols-outlined">recommend</span>
            <span class="material-symbols-outlined">clock_loader_20</span>
            <span class="material-symbols-outlined">sync_saved_locally</span>
        </div>

    </div>


    <div class="description_footer">
                <DescriptionItems v-for="q in item"
                :key="q.id"
                :foot="q"
                />
    </div>

    

</div>



</template>


<script>
// Логика
import items from '@/data/item';
import DescriptionData from '@/components/DescriptionData.vue'
import item from '@/data/items'
import DescriptionItems from '@/components/DescriptionItems.vue';



    export default{
        name: 'ProductView',
        components: {
            DescriptionData, DescriptionItems
        },
    

        data() {
            return {
                items:items,
                item:item
                
            }
            
        }
        
    }

</script>

<style scoped>
/* Стили */

.container-navi{
    display: flex;
    justify-content: space-between;
    width:1440px;
    height: 64px;     
}
.right{
    display: flex;
    justify-content: end;
    
}
.title-left{
    font-size: 24px;
    font-family: sans-serif;
    margin-left: 28px;
}
.title-right{
    display: flex;
    justify-content: space-between;    
    margin-top: 20px;
    width: 215px;
    height: 22px;   
}
    
.title-icon{
    width: 120px;
    height: 16px;
    justify-content: space-between;
}

.material-symbols-outlined{
    margin-top: 20px;
    height: 16px;
    width: 16px;
    margin-left: 15px;
}
.Bottom Bar{
    width: 1440px;
    height: 64px;
    justify-content: center;    
}
.botton-navigation{
    width: 803px;
    height: 64px;
    margin-left: 318px;
    margin-top: 20px;   
}
.nav-list{
    display: flex;
   justify-content: space-between;  
   margin-left: 20px;
   
}
.nav-item{
    font-family: sans-serif;
    font-size: 16px;
    color: rgba(114, 110, 141, 1);
}
.page-heder{
    width: 1300px;
    height: 277px;
    display: flex;
    margin-left: 128px;      
}
.title-page{
    margin-top: 88px;
    font-size: 36px;  
    margin-right: 2px;
    margin-left: -30px;
    font: 32px sans-serif;
    color: rgba(42,37,75,1);
}
.title-page-right{
  margin-top: 90px;
  color: rgba(42,37,75,1);
  margin-left: 350px;
  font-size: 16px;
  font: 15px sans-serif;
  width: 180px;
  height: 50px;
}
.Features{
    display: flex;
   justify-content: center;
    align-items: center;
    width: 1440px;
    height: 598px; 
}
.Features-left{
    width: 630px;
    height: 478px;
    background-color: rgba(42,37,75,1);
}
.Features-right{
    margin-left: 30px;
}  
.Features-right-img{
    width: 630px;
    height: 478px;
}
.Features-left-title{   
     
    font-family: sans-serif;
    width: 530px;
    height: 99px;
    color: rgba(255,255,255,1);    
}
.Features-left-title-h1{
    margin-left: 30px;
    margin-top: 30px;
    font-size: 32px;
    font:35px sans-serif;       
}
.Features-left-title-h3{
    margin-top: 30px;
    margin-left: 30px;
    font-size: 18px;
    font: 15px sans-serif;
        
}
.Features-h3{
    margin-left: 30px;
    font: 15px sans-serif;
    
}
.button{
    display: flex;
    justify-content: center;
    align-items: center;  
    width: 170px;
    height: 56px;
    margin-left: 64px;
    margin-top: 240px;
}
.button_collectiion{
    width: 170px;
    height: 56px;
    /* color: (255,255,255,1); */
    background: rgb(106, 91, 123) 
}
.Features-second{
    display: flex;
} 
.Features-second-left-img{
    width: 720px;
    height: 603px;
}
.Features-second-right{ 
    font:30px sans-serif;    
    text-align: left; /* Выровнять текст по левому краю */
    
    width: 720px;
    height: 603px;
    /* font-size: 27px; */
    line-height: 35px; /* ширина между строками */ 
    background-color: rgba(249,249,249,1);   
}
.Features-second-right-title0{
    margin-left: 60px;
}

.Features-second-right-title00{
    margin-left: 60px;
}

.Features-second-right-title{
    font-size: 17px;
    margin-top: 70px;
    line-height: 25px;
    margin-left: 60px;
}
.Features-second-right-title2{
    font-size: 17px;
    margin-top: 70px;
    line-height: 25px;
    margin-left: 60px;
}
.buttun-left{
    width: 170px;
    height: 56px;
    margin-top: 150px;
    margin-left: 60px;
    
}
.Feature-three{
    width: 1440px;
    height: 476px;
}
.card_title{
    display: flex;
    justify-content: center;
    margin-top: 50px;
    font-size: 12px;  
    align-items: center;
}
.Feature-three-title{
    display: flex;
    justify-content: center;
    margin-top: 50px;
    font:30px sans-serif;
}

.Email_sign_up{
    width: 1440px;
    height: 481px;
    display: flex;
    justify-content: center;
    background-color: rgba(249,249,249,1);
}

.Email{
    width: 1273px;
    height: 364px; 
    background-color: white;  
    margin-top: 52px;
    margin-left: 93px;
}

.Email_title{
    display: flex;
    justify-content: center;
    font:40px sans-serif; 
    margin-top: 35px;

}

.Email_basement{
    font:20px sans-serif;
    display: flex;
    justify-content: center;
    margin-top: 20px;
}
.Email_basement2{
    font:20px sans-serif;
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

.Email_completion{
    margin-top: 100px;
    display: flex;
    justify-content: center;
    width: 460px;
    height: 45px;
    
    margin-left: 400px;

}

.Email_completion.sendEmailButton{
    color: blue;
    width: 150px;
    height: 150px;
}
.one{
    width: 118px;
    height: 56px;
    background-color: #2A254B;
}
.email_input{
    width: 354px;
    height: 52px;

}
.email_input.type{
    color: white;
}
.Footer{
    background-color: #2A254B;
    width: 1440px;
    height: 350px;
    display: flex;
}
.footot_one{
    height: 300px;
}

.footer_text{
    width: 170px;
    height: 112px;
    margin-left: 80px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;



}
.footer_title{
    color: white;
    font-family: sans-serif;
    font-size: 36px;
    width: 97px;
    height: 50px;
    padding-top: 53px;
    margin-left: 80px;
}
.footer_title_1{
    color: white;
    margin-top: 20px;
    font-family: sans-serif;
    
    font-size: 14px;
}
.footer_title_2{
    color: white;
    font-family: sans-serif;
    
    font-size: 14px;
}
.footer_title_3{
    color: white;
    font-family: sans-serif;
   
    font-size: 14px;
}
.footer_title_4{
    color: white;
    font-family: sans-serif;
    
    font-size: 14px;
}
.footer_two{
    color: white;
    font-family: sans-serif;
    font-size: 16px;
    margin-top: 53px;
    margin-left: 60px;
    height: 200px;
}
.footer_h3{
    width: 150px;
}

.footer_title_5{
    margin-left: -20px;

}
.description_footer{
    display: flex;
    height: 300px;
}






</style>