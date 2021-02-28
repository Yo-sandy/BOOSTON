<template>
      <div class="row">
        <div style="background-color:#feca98; width: 100%;">
          <div class="text-center">
            <div>
              <h2 class="pt-2">Clear pricing. Affordable rates</h2>
              <div><img src="/delivery-icon-png-35.png" alt="" class="b1"></div>
              <p class="p2">LOCAL</p>
            </div>
            <div class="row justify-content-center">
              <div class="col-md-3 me-0 me-md-5 allbox" style=" background:radial-gradient(circle, rgba(236,119,1,0.3) 15%, rgba(236,119,1,1) 100%)">
                <img src="/moving-png-4.png" class="png-icon">
                <p class="p3">1 truck + 2 men</p>
                <p class="p4">form $<strong>79</strong>/hour</p>
              </div>
              <div class="col-md-3 text-center allbox" style="background: radial-gradient(circle, rgba(95,82,248,0.5) 0%, rgba(16,0,255,1) 100%);">
                <img src="/moving-png-4.png" class="png-icon">
                <p class="p3">1 truck + 3 men</p>
                <p class="p4">form $<strong>109</strong>/hour</p>
              </div>
            </div>
            <div>
              <div> <img src="/delivery-icon-11.png" alt="" class="b1"></div>
              <p class="p1">LONG DISTANCE</p>
            </div>
            <div class="row justify-content-center">
              <div class="col-md-3 me-md-5 allbox" style="background: radial-gradient(circle, rgba(232,232,232,0.8883753330433736) 3%, rgba(205,0,18,0.8631652490097601) 92%);">
                <img src="/moving-png-4.png" class="png-icon">
                <p class="p3">1 truck + 2 men</p>
                <p class="p4">form $<strong>799</strong></p>
              </div>
              <div class="col-md-3 text-center allbox" style="background: radial-gradient(circle, rgba(232,232,232,0.8883753330433736) 30%, rgba(148,187,233,1) 92%);">
                <img src="/moving-png-4.png" class="png-icon">
                <p class="p3">1 truck + 3 men</p>
                <p class="p4">form $<strong>1399</strong></p>
              </div>
              <div class="col-md-8 mt-md-2 mb-md-2 " style="background-color: #1c1c5d; height: 50px">
                <p class="text-white p5">VIEW ALL PRICING PLAN</p>
              </div>
            </div>
          </div>
        </div>
      </div>
</template>

<script>
export default {
name: "long-local-distance"
}
</script>

<style scoped>
    .allbox{
      height: 150px;
    }
    img.b1{
      max-width: 7rem;
      margin-top: 14px;
    }
    .png-icon{
      max-width: 5rem;
    }
    p.p1{
      font-size: 40px;
      color: white;
      margin-top: -30px;
      font-weight: bold;
    }
    p.p2{
      font-size: 40px;
      color: white;
      margin-top: -15px;
      font-weight: bold;
    }
    p.p3{
      color: white;
      font-weight: bold;
      font-size: 30px;
    }
    p.p4{
      color: white;
      margin-top: -15px;
    }
    p.p5{
      font-size: 30px;
    }
    strong{
      font-size: 30px;
    }
</style>
