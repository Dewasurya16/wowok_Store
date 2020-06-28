<template>
  <div class=home>
      <headerWowok/>

    
      <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items " :items="1" :nav="false">

            <div class="single-hero-items set-bg" style=background-image:url(/img/mikasa.jpg)>
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Akesories game</span>
                            <h1>Diskon Gede</h1>
                            <p>
                               Ayo buruan di order sebeblum kehabisan
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items set-bg"  style=background-image:url(/img/yuru.png)>
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Voucher game</span>
                            <h1>Diskon Gede juga</h1>
                            <p>
                                Ayo buruan di order sebelum diskonya abis
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items set-bg"  style=background-image:url(/img/kopi.jpg)>
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Kebutuhan game</span>
                            <h1>Diskon Gede juga</h1>
                            <p>
                                Ayo buruan di order mumpung lagi promo
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>


        </carousel>
    </section>
    <!-- Hero Section End -->
      </div>
</template>

<script>
// @ is an alias to /src
import carousel from 'vue-owl-carousel'

export default {
  name: 'heroWowok',
  components: {
     carousel 
  }
}
</script>
