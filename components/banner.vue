<template>
    <div class="row">
      <div class="container-box container-fluid">
        <div class="container-inner d-flex flex-column flex-md-row">
          <div class="main-text" style="max-width: 400px">
            <strong style="font-size: 50px">Boston Careful Movers</strong>
            <h4>provide full service relocation to both residential and Commercial Clients </h4>
          </div>
          <div class="main-image">
            <img src="/flyer.png" alt="" class="img-fluid" width="400px">
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "banner"
}
</script>


<style scoped>
.container-box{
  width: 100vw;
  height: 500px;
  background: radial-gradient(circle, rgba(236,119,1,0.3) 15%, rgba(236,119,1,1) 100%), url("/customer-man-signature.jpg") no-repeat;
  background-size:cover;
  display: flex;
  justify-content: center;
  align-items: center;
}
.container-inner{
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>

