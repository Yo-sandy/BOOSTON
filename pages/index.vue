<template>
 <div class="container-fluid">
   <div class="row">
     <div class="col-md-12 p-0">
       <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
         <div class="carousel-inner">
           <div class="carousel-item active">
             <banner />
           </div>
           <div  class="carousel-item">
             <banner />
           </div>
         </div>
         <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"  data-bs-slide="prev">
           <span class="carousel-control-prev-icon" aria-hidden="true"></span>
           <span class="visually-hidden">Previous</span>
         </button>
         <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"  data-bs-slide="next">
           <span class="carousel-control-next-icon" aria-hidden="true"></span>
           <span class="visually-hidden">Next</span>
         </button>
       </div>
     </div>
   </div>
   <marketing/>
   <stress-free-move/>
   <long-local-distance/>
   <yelp/>
   <socal-media-logo/>
   <phone-email-location/>
 </div>
</template>

<script>
export default {
  layout:"default",

}
</script>
