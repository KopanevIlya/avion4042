<template>

<div class="homework-footer">
    <div class="container">
      <div class="top-footer">
        <div class="list">

          <ul class="footer-first_list">
            <h1>Menu</h1>
            <li>New arrivals</li>
            <li>Best sellers</li>
            <li>Recently viewed</li>
            <li>Popular this week</li>
            <li>All products</li>
          </ul>

          <ul class="footer-second_list">
            <h1>Categories</h1>
            <li>Crockery</li>
            <li>Furniture</li>
            <li>Homeware</li>
            <li>Plant pots</li>
            <li>Chairs</li>
            <li>Crockery</li>
          </ul>

          <ul class="footer-third_list">
            <h1>Our company</h1>
            <li>About us</li>
            <li>Vacancies</li>
            <li>Contact us</li>
            <li>Privacy</li>
            <li>Returns policy</li>
          </ul>

        </div>

        <div class="right-block">
          <h1>Join our mailing list</h1>

          <div class="index-box">

            <div class="email">
              <span>your@email.com</span>
            </div>

            <div class="button">
              <span>Sign up</span>
            </div>


          </div>
        </div>
      </div>    

      <div class="social-line">
        <span>Copyright 2022 Avion LTD</span>

        <div class="social-icons">

          <span class="material-symbols-outlined">
            check_box
            </span>
          <span class="material-symbols-outlined">
            check_box
            </span>
          <span class="material-symbols-outlined">
            check_box
            </span>
          <span class="material-symbols-outlined">
            check_box
            </span>
          <span class="material-symbols-outlined">
            check_box
            </span>
          <span class="material-symbols-outlined">
            check_box
            </span>

        </div>
      </div>
    </div>

  </div>


</template>


<script>
export default {
  name:"FooterBlock"
}
</script>

<style>
.homework-footer {
  height: 380px;
  background-color: #2A254B;
  display: flex;
  justify-content: center;
}

.container {
  margin-top: 58px;
  width: 1277px;
}

.list {
  display: flex;
}

.list h1 {
  font-size: 16px;
}

.list li {
  font-size: 14px;
}

.top-footer {
  display: flex;
  align-items: flex-start;
}

.list h1,
.list li {
  margin-bottom: 12px;
}


.list ul {
  color: #FFFFFF;
}

.footer-first_list {
  margin-right: 109px;
}

.footer-second_list {
  margin-right: 133px;
}

.footer-second_list li:last-child {
  margin-bottom: 0px;
}

.footer-third_list {
  margin-right: 109px;
}

.right-block h1 {
  margin-bottom: 16px;
  color: #FFFFFF;
}

.index-box {
  display: flex;
}

.email {
  width: 509px;
  height: 56px;
  background: #FFFFFF26;
  display: flex;
  justify-content: center;
  align-items: center;
}

.email span {
  margin-right: 360px;
  margin-left: 32px;
  color: #FFFFFF;
}

.button {
  width:118px;
  height: 56px;
  background: #FFFFFF;
  display: flex;
  justify-content: center;
  align-items: center;
}

.social-line {
  border-top: 1px solid #4E4D93;
  height: 68px;
  margin-top: 48px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #FFFFFF;
}

.social-icons span {
  margin-left: 24px;
}

</style>