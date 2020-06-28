<template>
  <div class=product>
      <headerWowok/>
       <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-left">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="breadcrumb-text product-more">
                        <a href="./home.html"><i class="fa fa-home"></i> Home</a>
                        <span>Detail</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <!-- Product Shop Section Begin -->
    <section class="product-shop spad page-details">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="row">
                        <div class="col-lg-6">
                            <div class="product-pic-zoom">
                                <img class="product-big-img" :src="gambar_default" alt="" />
                            </div>
                            <div class="product-thumbs">
                                <carousel :autoplay="true" :loop="true" :dots="false" :nav="false" class="product-thumbs-track ps-slider ">
                                    <div class="pt active" @click="changeImage(thumbs[0])"  :class="thumbs[0] == gambar_default ? 'active' :''">
                                        <img src="img/ANDREW.jpg" alt="" />
                                    </div>

                                    <div class="pt"  @click="changeImage(thumbs[1])" :class="thumbs[1] == gambar_default ? 'active' :'' ">
                                        <img src="img/MOUSE.jpg" alt="" />
                                    </div>

                                    <div class="pt"  @click="changeImage(thumbs[2])" :class="thumbs[2] == gambar_default ? 'active' : ''">
                                        <img src="img/KEYBOARD.jpg" alt="" />
                                    </div>

                                    <div class="pt"  @click="changeImage(thumbs[3])" :class="thumbs[3] == gambar_default ? 'active' : ''">
                                        <img src="img/VGA.jpg" alt="" />
                                    </div>
                                </carousel>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <div class="product-details text-left">
                                <div class="pd-title">
                                    <span>pomade</span>
                                    <h3>Pomade jamal</h3>
                                </div>
                                <div class="pd-desc">
                                    <p>
                                        pomade kesukaan kaum pria
                                    </p>
                                    <p>
                                        Gaya rambut dengan menggunakan pomade lebih banyak banyak dipakai oleh pria. Dibandingkan dengan gel ataupun wax, pomade terbilang lebih awet untuk menjaga kerapiaan rambut dan tidak membuat rambut rusak karena terbuat dari bahan-bahan alami yang sangat aman digunakan pada rambut.

                                    </p>
                                    <h4>RP30.000</h4>
                                </div>
                                <div class="quantity">
                                    <a href="shopping-cart.html" class="primary-btn pd-cart">Add To Cart</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Product Shop Section End -->
      <foter/>

    
   
      </div>
</template>

<script>
// @ is an alias to /src
import headerWowok from '@/components/headerWowok.vue'
import foter from '@/components/foter.vue'
import carousel from "vue-owl-carousel";



export default {
  name: 'product',
  components: {
    carousel,
    headerWowok,
     foter
  },
  data() {
    return{
      gambar_default:"img/ANDREW.jpg",
      thumbs:[
        "img/ANDREW.jpg",
        "img/MOUSE.jpg",
        "img/KEYBOARD.jpg",
        "img/VGA.jpg"
      ]
    }
  },
  methods:{
    changeImage(urlImage){
      this.gambar_default = urlImage;
    }
  }
};
</script>

<style scoped>
.product-thumbs .pt{
  margin-right: 14px;

}
</style>