<template>

    <div class="top-navigation">
      <span class="material-symbols-outlined">
      search
      </span>
      <h1 class="logo-nav">AVION</h1>
      <div class="wrapper-right-iecons">
        <span class="material-symbols-outlined icons-shop-account">
        shopping_cart
        </span>
        <span class="material-symbols-outlined">
        account_circle
        </span>
      </div>
    </div>


</template>

<script>


export default{
  name: "HeaderTop"
}


</script>

<style>

.logo-nav {
  font-size: 24px;
  font-weight: 400;
}

.top-navigation {
  display: flex;
  justify-content: space-between;
  border-bottom: 1px solid #0000001A;
  height: 70px;
  align-items: center;
}

.icons-shop-account {
  margin-right: 16px;
}



</style>