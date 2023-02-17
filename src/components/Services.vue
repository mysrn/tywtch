<script setup>
import { ref } from 'vue'

</script>

<template>
  <div class="text-center p-4 div-services">
    <h1 class="about">Our Services</h1>
    <hr class="hr-about">
    <div class="row p-4">
      <div class="col-12 d-flex justify-content-between p-5">
        <div class="card-circle">
          <div class="card-text">Service 1</div>
        </div>
        <div class="card-circle">
          <div class="card-text">Service 2</div>
        </div>
        <div class="card-circle">
          <div class="card-text">Service 3</div>
        </div>
        <div class="card-circle">
          <div class="card-text">Service 4</div>
        </div>
        <div class="card-circle">
          <div class="card-text">Service 5</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.card-text{
  margin-top: 165px;
  font-family: 'Plus Jakarta Sans';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 25px;
  letter-spacing: 0.05em;
}

.card-circle {
  width: 137px;
  height: 137px;
  border-radius: 50%;
  background-color: #ccc;
}

.div-services{
  margin-top: 125px;
}

.about{
  font-family: 'Plus Jakarta Sans';
  font-style: normal;
  font-weight: 200;
  font-size: 48px;
  line-height: 60px;
  letter-spacing: 0.05em;
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
