<template>
      

          <!-- Women Banner Section Begin -->
    <section class="women-banner spad">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-5">
                    <carousel class="product-slider owl" :items="3" :nav="false" :dots="false" :autoplay="true">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/ANDREW.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="product.html">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Console</div>
                                <a href="#">
                                    <h5>Nintendo Switch</h5>
                                </a>
                                <div class="product-price">
                                    RP4.000.000
                                    <span>RP6.000.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/MOUSE.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">akesoris Game</div>
                                <a href="#">
                                    <h5>Stel Series Rival</h5>
                                </a>
                                <div class="product-price">
                                    RP350.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/KEYBOARD.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Akesories Game</div>
                                <a href="#">
                                    <h5>Razer Widow</h5>
                                </a>
                                <div class="product-price">
                                    RP800.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/VGA.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Hardware</div>
                                <a href="#">
                                    <h5>Nvidia Rtx 2060</h5>
                                </a>
                                <div class="product-price">
                                    Rp3.000.000
                                    <span> RP4.000.000 </span>
                                </div>
                            </div>
                        </div>
                          <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/ps.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Console</div>
                                <a href="#">
                                    <h5>playstation</h5>
                                </a>
                                <div class="product-price">
                                    Rp2.500.000z
                                    <span> RP4.000.000 </span>
                                </div>
                            </div>
                        </div>
                    </carousel>
                </div>
            </div>
        </div>
    </section>
    <!-- Women Banner Section End -->

</template>



<script>
import carousel from "vue-owl-carousel";

export default {
    name: "woman",
    components: {
        carousel
    }
};
</script>


<style scoped>
.product-item {
    margin-right: 35px;
}
.pi-pic img{
    height: 450px;
}
</style>