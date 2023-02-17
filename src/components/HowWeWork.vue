<script setup>
import { ref } from 'vue'

</script>

<template>
  <div class="div-how p-5">
    <div class="row">
      <div class="col-2">
        <h1 class="how">How <br> We <br> Work</h1><br><hr class="hr-how">
      </div>
      <div class="col-10">
        <div class="card card-content-how">
          <div class="row row-card">
            <div class="col-6">
              <div class="row">
                <div class="col-3">
                  <div class="card-circle"><span class="card-text-circle">1</span></div>
                </div>
                <div class="col-5">
                  <div class="card-text text-how">Project inisiation with stakeholder</div>
                </div>
                <div class="col-1"></div>
              </div>
              <div class="row row-how">
                <div class="col-3">
                  <div class="card-circle"><span class="card-text-circle">2</span></div>
                </div>
                <div class="col-5">
                  <div class="card-text text-how">Project Planning with stakeholder</div>
                </div>
                <div class="col-1"></div>
              </div>
            </div>
            <div class="col-6">
              <div class="row">
                <div class="col-3">
                  <div class="card-circle"><span class="card-text-circle">3</span></div>
                </div>
                <div class="col-5">
                  <div class="card-text text-how">Project Execution</div>
                </div>
                <div class="col-1"></div>
              </div>
              <div class="row row-how">
                <div class="col-3">
                  <div class="card-circle"><span class="card-text-circle">4</span></div>
                </div>
                <div class="col-5">
                  <div class="card-text text-how">Project Testing</div>
                </div>
                <div class="col-1"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.row-how{
  margin-top: 50px;
}

.text-how{
  font-family: 'Plus Jakarta Sans';
font-style: normal;
font-weight: 400;
font-size: 30px;
line-height: 38px;
letter-spacing: 0.05em;
}

.card-circle {
  width: 133px;
  height: 133px;
  border-radius: 50%;
  background-color: #E0FFED;
  position: relative;
}

.card-text-circle{
  text-align: center;
  font-family: 'Podkova';
  font-style: normal;
  font-weight: 800;
  font-size: 128px;
  line-height: 142px;
  /* identical to box height */
  letter-spacing: 0.05em;
  color: #000000;
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin-bottom: 10px;
}

.card-content-how{
  box-sizing: border-box;
  position: absolute;
  width: 1247px;
  height: 395px;
  top: 1975px;
  background: #FFFFFF;
  border: 1px solid #D3D3D3;
}

.how{
  font-family: 'Plus Jakarta Sans';
  font-style: normal;
  font-weight: 200;
  font-size: 48px;
  line-height: 60px;
  letter-spacing: 0.05em;
  margin-top: 70px;
}

.div-how{
  margin-top: 125px;
  margin-bottom: 100px;
}

.hr-how{
  width: 108px;
  height: 0px;
  left: 126px;
  border: 3px solid #5DC787;
}

.row-card{
  margin-top: 50px;
  margin-left: 50px;
}
</style>
