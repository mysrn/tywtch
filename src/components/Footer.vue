<script setup>
import { ref } from 'vue'

</script>

<template>
  <div class="text-center p-4 div-about">
    <h1 class="about">Contact Us</h1>
    <hr class="hr-about">
    <div class="row content-contact">
      <div class="col-4"></div>
      <div class="col-2"><font-awesome-icon icon="fa-solid fa-email" />Emailaddress@gmail.com</div>
      <div class="col-2">089990009999</div>
      <div class="col-4"></div>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.content-contact{
  margin-top: 90px;
  margin-bottom: 175px;
}

.div-about{
  margin-top: 125px;
  background-color: #E0FFED;
}

.about{
  font-family: 'Plus Jakarta Sans';
  font-style: normal;
  font-weight: 200;
  font-size: 48px;
  line-height: 60px;
  letter-spacing: 0.05em;
  margin-top: 80px;
}

.hr-about{
  border: 3px solid #5DC787;
  width: 108px;
  text-align: center;
  margin-left:auto; 
  margin-right:auto;
}

.text-about{
  font-family: 'Plus Jakarta Sans';
  font-style: normal;
  font-weight: 300;
  font-size: 20px;
  line-height: 40px;
  /* or 200% */
  text-align: center;
  letter-spacing: 0.05em;
  color: #000000;
}
</style>
