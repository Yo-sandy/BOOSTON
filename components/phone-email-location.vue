<template>
  <div class="row">
    <div class=" text-center" style="background-color: #01071d;">
      <div class="row justify-content-center text-white pt-5">
        <div class="col-md-2 me-xl-5 dotted">
          <img src="/location-icon-map-png-15.png" class="img-responsive"/>
          <p>Hisar(125001) kaimri</p>
        </div>
        <div class="col-md-2 me-xl-4 dotted">
          <img src="/email-logo.png" class="img-responsive"/>
          <p>justsandy786@Gmail.com</p>
        </div>
        <div class="col-md-2">
          <img src="/phone-logo.png" class="img-responsive"/>
          <p>(617)123-1598</p>
        </div>
        <div class="mt-md-5">
          <h4>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Adipisci consectetur, consequuntur dolore eaque facili</h4>
        </div>
        <div class="mt-xl-4 mt-md-4 mt-2 mb-3">
          <img src="/socal-media-icon/Facebook_-icon.png" class="icon-img">
          <img src="/socal-media-icon/Circled_Instagram_svg-512.png" class="icon-img">
          <img src="/socal-media-icon/Circled_Pinterest_svg-512.png" class="icon-img">
          <img src="/socal-media-icon/Circled_Twitter_svg-512.png" class="icon-img">
          <img src="/socal-media-icon/Circled_Whatsapp_svg2-512.png" class="icon-img">
          <img src="/socal-media-icon/Circled_Youtube_svg-512.png" class="icon-img">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "phone-email-location"
}
</script>

<style scoped>
  .dotted{
     border-right:1px solid rgba(255, 255, 255, 0.3);
  }
  .icon-img{
    max-width: 2rem;
    background-color: white;
    border-radius: 50%;
  }
  .img-responsive{
    width: 45px;
    max-width: 100%;
    height: 45px;
    object-fit: contain;
    margin-bottom: 5px;
  }
</style>
