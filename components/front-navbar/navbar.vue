<template>
    <div class="container-fluid px-md-5 bg-light">
        <div class="row">
          <nav class="navbar navbar-expand-lg navbar-light ">
            <img src="/phone_PNG49052.png" alt="" style="max-width: 3rem" class="img-fluid d-md-none"/>
            <div>
              <div class="d-flex">
                <strong
                  class="align-self-center"
                  style="display:inline-block;
                  color:#f65454;
                  font-size: 30px; margin-left: 15px;">BOSTON</strong>
                <img class="ms-0" src="/tracking.png" alt="" style="max-width: 4rem;"/>
              </div>
              <p style="font-size: 25px; margin-top: -15px">CAREFUL MOVERS</p>
            </div>
            <button
              class="navbar-toggler navbar-expand-md"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarSupportedContent">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav ms-5">
                <li class="nav-item text-center"><nuxt-link class="nav-link active" to="/">SHOP</nuxt-link></li>
                <li class="nav-item text-center"><nuxt-link class="nav-link " to="/">MY ORDERS</nuxt-link></li>
                <li class="nav-item text-center"><nuxt-link class="nav-link " to="/">SELLER LIST</nuxt-link></li>
                <li class="nav-item text-center"><nuxt-link class="nav-link " to="/">CONTACT US</nuxt-link></li>
              </ul>
            </div>
            <div class="d-none d-md-block">
              <h5>@(647)123-1544</h5>
            </div>
          </nav>
        </div>
    </div>
</template>

<script>
export default {
name: "navbar"
}
</script>

<style scoped>

</style>
