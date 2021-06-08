<template>
  <div class="home">
    <main>
        <div class="hero_single version_1">
            <div class="opacity-mask">
                <div class="container">
                    <div class="row justify-content-lg-start justify-content-md-center">
                        <div class="col-xl-6 col-lg-8">
                            <h1 class="kw_">GHANA FOOD DELIVERY </h1>
                            <p class="kw_">Pre-order your meals up to 2 weeks ahead.<br> The earlier you order, the cheaper the food!</p>
                            <!--  -->

                            <div class="sign_in_inf">
                                <form>
                                    <div class="sign-in-wrapper">
                                        <div class="sign_intit">
                                            Log in to shedule or manage your orders
                                        </div>
                                        <a href="#" class="social_bt facebook">Continue with Facebook</a>
                                        <a href="#" class="social_bt google">Continue with Google</a>
                                        <div class="divider"><span>Or</span></div>
                                        <a href="#" class="social_bt mail">Continue with email</a>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                    <!-- /row -->
                </div>
            </div>
            <div class="wave hero"></div>
        </div>
        <!-- /hero_single -->

        <div class="container margin_30_60">
            <div class="main_title center">
                <span><em></em></span>
                <h2>Menu Categories</h2>
                <p>What do you feel like eating? We're constantly updating our option to meet your demands</p>
            </div>
            <!-- /main_title -->
            <!-- /promo -->

            <div class="row isotope-wrapper">
                <div class="col-xl-4 col-lg-6 col-md-6 col-sm-6 isotope-item delivery">
                    <div class="strip">
                        <figure>
                            <!-- <span class="ribbon off">15% off</span> -->
                            <img src="../assets/img/location_1.jpg" class="img-fluid lazy" alt="">
                            <a href="detail-restaurant.html" class="strip_info">
                                <!-- <small>Pizza</small> -->
                                <div class="item_title">
                                    <h3>POPULAR FAVOURITES</h3>
                                    <!-- <small>27 Old Gloucester St</small> -->
                                </div>
                            </a>
                        </figure>

                    </div>
                </div>
                <!-- /strip grid -->
                <div class="col-xl-4 col-lg-6 col-md-6 col-sm-6 isotope-item delivery">
                    <div class="strip">
                        <figure>
                            <img src="../assets/img/location_2.jpg" class="img-fluid lazy" alt="">
                            <a href="detail-restaurant.html" class="strip_info">
                                <!-- <small>Burghers</small> -->
                                <div class="item_title">
                                    <h3>HEALTH WATCH</h3>
                                    <!-- <small>27 Old Gloucester St</small> -->
                                </div>
                            </a>
                        </figure>

                    </div>
                </div>
                <!-- /strip grid -->
                <div class="col-xl-4 col-lg-6 col-md-6 col-sm-6 isotope-item takeaway">
                    <div class="strip">
                        <figure>
                            <!-- <span class="ribbon off">15% off</span> -->
                            <img src="../assets/img/location_3.jpg" class="img-fluid lazy" alt="">
                            <a href="detail-restaurant.html" class="strip_info">
                                <!-- <small>Vegetarian</small> -->
                                <div class="item_title">
                                    <h3>SOMETHING DIFFERENT</h3>
                                    <!-- <small>27 Old Gloucester St</small> -->
                                </div>
                            </a>
                        </figure>

                    </div>
                </div>
               </div>
            <!-- /strip row -->
        </div>
              <div class="bg_gray">
            <div class="container margin_60_40">
           
                <div class="banner lazy" src="../assets/img/banner_bg_desktop.jpg">
                    <div class="wrapper d-flex align-items-center opacity-mask" data-opacity-mask="rgba(0, 0, 0, 0.3)">
                        <div>
                            <small>GHANA FOOD DELIVERY </small>
                            <h3>We Deliver to your Office</h3>
                            <p>Enjoy a tasty food in minutes!</p>
                            <a href="grid-listing-filterscol.html" class="btn_1 gradient">Start Now!</a>
                        </div>
                    </div>
                    <!-- /wrapper -->
                </div>
                <!-- /banner -->
            </div>
        </div>
        <!-- /bg_gray -->

        <div class="shape_element_2">
            <div class="container margin_60_0">
                <div class="row">
                    <div class="col-lg-6">
                        <div class="row">
                            <div class="col-lg-6">
                                <div class="box_how">
                                    <figure><img src="../assets/img/how_1.svg" alt="" width="150" height="167" class="lazy"></figure>
                                    <h3>Schedule Your Order</h3>
                                    <p>We take up to 2 weeks of orders in advance and give you sweet discounts for doing so</p>
                                </div>
                                <div class="box_how">
                                    <figure><img src="../assets/img/how_2.svg" alt="" width="130" height="145" class="lazy"></figure>
                                    <h3>Free Delivery</h3>
                                    <p>There are no additional charges for getting the food to you</p>
                                </div>
                            </div>
                            <div class="col-lg-6 align-self-center">
                                <div class="box_how">
                                    <figure><img  src="../assets/img/how_3.svg" alt="" width="150" height="132" class="lazy"></figure>
                                    <h3>Enjoy the Food</h3>
                                    <p>We take your taste buds seriously and only work with the best chefs and restaurants in town</p>
                                </div>
                            </div>
                        </div>
                        <p class="text-center mt-3 d-block d-lg-none"><a href="#" class="btn_1 medium gradient pulse_bt mt-2">Register Now!</a></p>
                    </div>
                    <div class="col-lg-5 offset-lg-1 align-self-center">
                        <div class="intro_txt">
                            <div class="main_title">
                                <span><em></em></span>
                                <h2>Start Ordering Now</h2>
                            </div>
                            <p class="lead">You can edit or cancel orders up to 2 days before the scheduled date. If you cancel an order, we'll credit your account for future orders.</p>
                            <!-- <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p> -->
                            <p><a href="#" class="btn_1 medium gradient pulse_bt mt-2">Register</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- /shape_element_2 -->

    </main>
  </div>
</template>

<script>


export default {
  name: 'Home',
  components: {
    
  }
}
</script>
<style>

</style>
