<template>


  <div>

    <div class="first-block">
    <div class="hero">
      <div class="left-block">
        <div class="top-content">
          <h1>The furniture brand for the<br>future, with timeless designs</h1>

          <div class="button-hero">
            <span>View collection</span>
          </div>
        </div>

        <div class="bottom-content">

          <p>A new era in eco friendly furniture with Avelon, the French luxury retail brand <br>
            with nice fonts, tasteful colors and a beautiful way to display things digitally <br>
            using modern web technologies.</p>

        </div>
      </div>
      <div class="right-block">
        <img src="../assets/image/Right Image.png" alt="">
      </div>
    </div>
  </div>

  </div>
</template>


<script>


export default{
  name:'FirstBlock'
}
</script>


<style>
.hero {
  display: flex;
  justify-content: center;
  padding: 60px 0px;
}

.left-block {
  width: 760px;
  height: 584px;
  background-color:#2A254B;
}

.top-content h1 {
  font-size: 32px;
  font-weight: 400;
  line-height: 45px;
  margin-top: 60px;
  margin-left: 60px;
  color: #FFFFFF;
}

.button-hero {
  margin-top: 41px;
  margin-left: 60px;
  width: 170px;
  height: 56px;
  background-color: #F9F9F926;
}

.button-hero  {
  color: #FFFFFF;
  display: flex;
  justify-content: center;
  align-items: center;
}

.bottom-content {
  margin-top: 196px;
  margin-left: 60px;
}

.bottom-content p {
  font-size: 18px;
  color: white;
  font-weight: 400;
  line-height: 27px;
}

</style>