<template>

  <div class="homework-block">
    <h1 class="title">What makes our brand different</h1>

    <div class="block-cards">
      <section>
        <span class="material-symbols-outlined">
        local_shipping
        </span>
        <h1>Next day as standard</h1>
        <span>Order before 3pm and get your order
          the next day as standard</span>
      </section>

      <section>
        <span class="material-symbols-outlined">
          check_circle
          </span>
        <h1>Made by true artisans </h1>
        <span>Handmade crafted goods made with
          real passion and craftmanship</span>
      </section>

      <section>
        <span class="material-symbols-outlined">
        credit_card
        </span>
        <h1>Unbeatable prices</h1>
        <span>For our materials and quality you won’t find better prices anywhere</span>
      </section>

      <section>
        <span class="material-symbols-outlined">
          psychiatry
          </span>
        <h1>Recycled packaging</h1>
        <span>We use 100% recycled packaging to ensure our footprint is manageable </span>
      </section>
    </div>

  </div>


</template>


<script>

export default{
name: "ManesBlock"
}
</script>


<style>
.homework-block {
  height: 355px;
}

.title {
  text-align: center;
  margin-top: 60px;
  line-height: 33px;
  font-size: 24px;
  margin-bottom: 51px;
}

.block-cards {
  display: flex;
  margin-left: 86px;
}

</style>