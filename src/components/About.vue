<script setup>
import { ref } from 'vue'

</script>

<template>
  <div class="text-center p-4 div-about">
    <h1 class="about">About Us</h1>
    <hr class="hr-about">
    <p class="text-about">“No name” is website developer service based in Indonesia. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.div-about{
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
