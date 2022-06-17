<template>
  <main class="v-content" data-booted="true" style="padding: 64px 0px 0px 256px;"><div class="v-content__wrap"><div class="container px-6"><div class="my-10">
  <h3 class="my-5">
    Dashboard
  </h3> 

  <!-- <div class="swiper-container swiper swiper-container-initialized swiper-container-horizontal">  
    <div class="swiper-wrapper" style="transform: translate3d(0px, 0px, 0px);">
        <div class="main-slider-slide swiper-slide swiper-slide-active" style="width: 959px; margin-right: 30px;">
            <img src="https://api.cloudminepro.com/images/banner/1644647305-7630.jpg" alt="" class="main-slider-img">
             <div class="hero-container">
                <h1 class="hero-title">CMP</h1>
                 <h3 class="hero-subtitle">Contracts</h3>
                 </div>
                 </div>
                 <div class="main-slider-slide swiper-slide swiper-slide-next" style="width: 959px; margin-right: 30px;">
                    <img src="https://api.cloudminepro.com/images/banner/1633100392-4165.jpg" alt="" class="main-slider-img">
                     <div class="hero-container">
                        <h1 class="hero-title">CMP</h1>
                         <h3 class="hero-subtitle">The token will be unveiled soon</h3>
                         </div>
                         </div>
                         <div class="main-slider-slide swiper-slide" style="width: 959px; margin-right: 30px;">
                            <img src="https://api.cloudminepro.com/images/banner/1625132412-3954.jpg" alt="" class="main-slider-img"> 
                            <div class="hero-container">
                                <h1 class="hero-title">CMP</h1> 
                                <h3 class="hero-subtitle">CLOUDMINPRO.COM</h3>
                                </div>
                                </div>
                                <div class="main-slider-slide swiper-slide" style="width: 959px; margin-right: 30px;">
                                    <img src="https://api.cloudminepro.com/images/banner/1625132969-4144.jpg" alt="" class="main-slider-img">
                                     <div class="hero-container">
                                        <h1 class="hero-title">CMP</h1>
                                         <h3 class="hero-subtitle">TOKEN</h3>
                                         </div>
                                         </div>
                                         <div class="main-slider-slide swiper-slide" style="width: 959px; margin-right: 30px;">
                                            <img src="https://api.cloudminepro.com/images/banner/1633158000-3827.jpg" alt="" class="main-slider-img">
                                             <div class="hero-container">
                                                <h1 class="hero-title">2FA</h1>
                                                 <h3 class="hero-subtitle">We give you security</h3>
                                                 </div>
                                                 </div>
                                                    </div> 
                                                    <div class="swiper-pagination swiper-pagination-clickable swiper-pagination-bullets">
                                                        <span class="swiper-pagination-bullet swiper-pagination-bullet-active" tabindex="0" role="button" aria-label="Go to slide 1">
                                                            </span>
                                                            <span class="swiper-pagination-bullet" tabindex="0" role="button" aria-label="Go to slide 2">
                                                                </span>
                                                                <span class="swiper-pagination-bullet" tabindex="0" role="button" aria-label="Go to slide 3">
                                                                    </span>
                                                                    <span class="swiper-pagination-bullet" tabindex="0" role="button" aria-label="Go to slide 4">
                                                                        </span>
                                                                        <span class="swiper-pagination-bullet" tabindex="0" role="button" aria-label="Go to slide 5">
                                                                            </span>
                                                                            </div>
                                                                             <div class="swiper-button-prev swiper-button-disabled" tabindex="0" role="button" aria-label="Previous slide" aria-disabled="true">
                                                                                </div>
                                                                                 <div class="swiper-button-next" tabindex="0" role="button" aria-label="Next slide" aria-disabled="false">
                                                                                    </div> 
                                                                                    <span class="swiper-notification" aria-live="assertive" aria-atomic="true">
                                                                                        </span>
                                                                                        </div> -->

  <v-carousel>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>

  
  
   <section class="my-10"><div class="row"><div class="col-lg-6 col-12"><h3 class="my-5">
          Your referral link, share it with your friends
        </h3> <div class="d-inline-block mx-auto mb-10 v-card v-sheet theme--light" style="width: 100%;"><div class="container"><div class="row justify-space-between"><div class="col"><div>Your left refferal link</div> <div class="v-input custom-referrer-input v-input--hide-details v-input--is-label-active v-input--is-dirty v-input--is-disabled theme--light v-text-field v-text-field--full-width v-text-field--single-line v-text-field--is-booted"><div class="v-input__control"><div class="v-input__slot"><div class="v-text-field__slot"><input disabled="disabled" id="input-145" type="text"></div></div></div></div> <div class="mt-4">Your right refferal link</div> <div class="v-input custom-referrer-input v-input--hide-details v-input--is-label-active v-input--is-dirty v-input--is-disabled theme--light v-text-field v-text-field--full-width v-text-field--single-line v-text-field--is-booted"><div class="v-input__control"><div class="v-input__slot"><div class="v-text-field__slot"><input disabled="disabled" id="input-146" type="text"></div></div></div></div></div> <div class="d-flex flex-column text-center pl-0 col col-auto"><div class="row ma-0 align-center justify-center"><div class="px-0 col"><button type="button" class="v-btn v-btn--flat v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate mdi mdi-content-copy theme--light"></i></span></button></div></div> <div class="row ma-0 align-center justify-center"><div class="px-0 col"><button type="button" class="v-btn v-btn--flat v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate mdi mdi-content-copy theme--light"></i></span></button></div></div></div></div></div></div></div> <div class="col-lg-6 col-12"><h3 class="my-5">
          Purchase a package to activate your account!
        </h3> <div data-v-4df6f9ae="" class="text-center pa-5 custom-timer-card v-card v-sheet theme--light"><span data-v-4df6f9ae=""><!----><!----><div data-v-4df6f9ae=""><p data-v-4df6f9ae="" class="ma-0">
                    Your account will be deactivated from about:
                </p> <div data-v-4df6f9ae="" class="custom-timer">

172800
                    


                </div></div><!----></span></div></div></div></section> <section><h3 class="my-5">
      User Info
    </h3> <div class="row"><div class="col-md-4 col-12"><div class="text-center pa-5 v-card v-sheet theme--light" style="height: 100%;"><div class="dashboard-user-avatar"><img src="https://lh3.googleusercontent.com/a-/AOh14Giji9eAXx7CE7Jky5vFQ50vpvvUcSxX3IgX1Ph3=s96-c" alt="" class="user-avatar"></div> <div class="dashboard-user-info"><p class="mt-5 mb-1">
            email: arian68655@gmail.com
        </p> <p class="mb-1">
            Username: 6BZ5vIne
        </p> <p class="mb-1">
            Total Investment: 0.000
        </p> <p class="mb-1">
            Left Members: 0
        </p> <p class="mb-1">
            Right Members: 0
        </p></div></div></div> <div class="col-md-4 col-12"><div data-v-f40addbc="" class="text-center pa-5 v-card v-sheet theme--light" style="height: 100%;"><div data-v-f40addbc="" class="v-card__title"><span data-v-f40addbc="" class="headline">Account info</span></div> <div data-v-f40addbc="" class="v-card__text"><div data-v-f40addbc="" class="row"><div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate fas fa-dollar-sign mdi mdi-currency-usd theme--light" style="font-size: 40px; color: rgb(233, 162, 0);"></i></div> <div data-v-f40addbc="">Commission Wallet: </div>
                0 $
            </div> <div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate mr-2 mdi mdi-cash-multiple theme--light" style="font-size: 40px; color: rgb(133, 187, 101);"></i></div> <div data-v-f40addbc="">Profit Wallet: </div>
                0 $
            </div></div> <div data-v-f40addbc="" class="row"><div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate fas fa-dollar-sign mdi mdi-wallet theme--light" style="font-size: 40px; color: rgb(138, 226, 224);"></i></div> <div data-v-f40addbc="">Deposit Wallet: </div>
                0 $
            </div> <div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate fas fa-dollar-sign mdi mdi-credit-card theme--light" style="font-size: 40px; color: rgb(58, 163, 160);"></i></div> <div data-v-f40addbc="">Voucher Wallet: </div>
                0 $
            </div> <div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate mr-2 mdi mdi-cash-usd theme--light" style="font-size: 40px; color: rgb(247, 211, 48);"></i></div> <div data-v-f40addbc="">Left Investment: </div>
                0.000 $
            </div> <div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate mr-2 mdi mdi-home-currency-usd theme--light" style="font-size: 40px; color: rgb(246, 195, 36);"></i></div> <div data-v-f40addbc="">Right Investment: </div>
                0.000 $
            </div></div> <span data-v-f40addbc="" class="qualification-msg qualification-msg-failure">user is not qualified for binary plan</span></div></div></div> <div class="col-md-4 col-12"><div class="text-center pa-5 v-card v-sheet theme--light" style="height: 100%;"><div class="v-card__title"><span class="headline">Last Package</span></div> <div class="v-card__text"><div class="row"><div class="text-center col col-12"><!----></div></div></div></div></div></div></section>
            
            
            
             <section class="my-10"><h3>Your Packages</h3> <div role="alert" class="v-alert my-5 v-sheet theme--dark info"><div class="v-alert__wrapper"><i aria-hidden="true" class="v-icon notranslate v-alert__icon mdi mdi-information theme--dark"></i><div class="v-alert__content">
      Purchase a package!
    </div></div></div></section></div></div></div></main>
    
</template>

<script>
export default {
    props: {
    sale_items: Array,
  },
data(){
      return {
        items: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    }
};
 
</script>

<style>
.v-application .my-5 {
    margin-top: 20px!important;
    margin-bottom: 20px!important;
}
* {
    background-repeat: no-repeat;
    padding: 0;
    margin: 0;
}
h3 {
    display: block;
    font-size: 2.00em;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
}
.v-application--wrap {
    font-family: Assistant,sans-serif;
}
:after, :before {
    text-decoration: inherit;
    vertical-align: inherit;
}
*, :after, :before {
    box-sizing: inherit;
}
.v-application .px-6 {
    padding-right: 24px!important;
    padding-left: 24px!important;
}
@media (min-width: 1264px){
.container {
    max-width: 1185px;
}}
.container {
    width: 100%;
    padding: 12px;
    margin-right: auto;
    margin-left: auto;
}
* {
    background-repeat: no-repeat;
    padding: 0;
    margin: 0;
}
div {
    display: block;
    
}
.v-application--wrap {
    font-family: Assistant,sans-serif;
    margin: auto;
}
::selection {
    background-color: #b3d4fc;
    color: #000;
    text-shadow: none;
}
.v-content{
    margin: -100px 0 0 -250px;

   
}


</style>