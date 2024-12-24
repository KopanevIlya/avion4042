<template>
  <div class="main_container">
    <HeaderTop/>
    <nav class="nav-list">
      <router-link to="/">Plant pots</router-link> 
      <router-link to="/about">Ceramics</router-link> 
      <router-link to="/">Tables</router-link> 
      <router-link to="/">Chairs</router-link> 
      <router-link to="/">Crockery</router-link> 
      <router-link to="/">Tableware</router-link> 
      <router-link to="/">Cutlery</router-link> 
    </nav>
    <FirstBlock/>
    <MakesBlock/>
    <FooterBlock/>
  </div>
</template>

<script>
import HeaderTop from './components/HeaderTop.vue';
import FirstBlock from './components/FirstBlock.vue';
import MakesBlock from './components/MakesBlock.vue';
import FooterBlock from './components/FooterBlock.vue';


export default{
  name:"App",
  components: {
    HeaderTop, FirstBlock, MakesBlock,FooterBlock
  }
}
</script>


<style>
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline}
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}
html{height:100%}
body{line-height:1}
ol,ul{list-style:none}
blockquote,q{quotes:none}
blockquote:before,blockquote:after,q:before,q:after{content:'';content:none}
table{border-collapse:collapse;border-spacing:0}

.main_container {
  margin: 0 auto;
  width: 1440px;
  font-family: sans-serif;
}

.bottom-navigation {
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav-list {
  display: flex;
  justify-content: center;
}

.nav-list a {
  text-decoration: none;
  color: #726E8D;
}

.nav-list li {
  margin-right: 44px;
}

</style>
