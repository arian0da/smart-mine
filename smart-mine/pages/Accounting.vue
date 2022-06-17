<template>
  <main class="v-content" style="padding: 64px 0px 0px 256px;" data-booted="true"><div class="v-content__wrap"><div class="container px-6"><div class="my-10"><h3 class="my-5">
    Accounting
  </h3> <section class="my-10"><h2 class="my-5" style="display: none;">
      Your Accounting info &amp; transactions
    </h2> <div class="row"><div class="col-sm-6 col-12"><div data-v-f40addbc="" class="text-center pa-5 v-card v-sheet theme--light" style="height: 100%;"><div data-v-f40addbc="" class="v-card__title"><span data-v-f40addbc="" class="headline">Account info</span></div> <div data-v-f40addbc="" class="v-card__text"><div data-v-f40addbc="" class="row"><div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate fas fa-dollar-sign mdi mdi-currency-usd theme--light" style="font-size: 40px; color: rgb(233, 162, 0);"></i></div> <div data-v-f40addbc="">Commission Wallet: </div>
                0 $
            </div> <div data-v-f40addbc="" class="text-center col col-6"><div data-v-f40addbc=""><i data-v-f40addbc="" aria-hidden="true" class="v-icon notranslate mr-2 mdi mdi-cash-multiple theme--light" style="font-size: 40px; color: rgb(133, 187, 101);"></i></div> <div data-v-f40addbc="">Profit Wallet: </div>
                0 $
            </div></div> <!----> <!----></div></div></div> <div class="col-sm-6 col-12"><div class="v-card v-sheet theme--light"><span><div class="v-card__title"><span class="headline">Withdraw</span></div> <div class="v-card__text"><form novalidate="novalidate" class="v-form"><div class="container"><div class="row"><div class="col-sm-6 col-md-12 col-12"><span><div class="v-input theme--light v-text-field v-text-field--is-booted v-text-field--placeholder"><div class="v-input__control"><div class="v-input__slot"><div class="v-text-field__slot"><label for="input-136" class="v-label v-label--active theme--light" style="left: 0px; right: auto; position: absolute;">Wallet Adress</label><input required="required" id="input-136" placeholder="Your  Wallet  Address" type="text"></div></div><div class="v-text-field__details"><div class="v-messages theme--light"><div class="v-messages__wrapper"></div></div></div></div></div></span></div> <div class="col-sm-6 col-md-12 col-12"><!----> <span><div class="v-input v-input--is-label-active v-input--is-dirty theme--light v-text-field v-text-field--is-booted v-text-field--placeholder"><div class="v-input__control"><div class="v-input__slot"><div class="v-text-field__slot"><label for="input-140" class="v-label v-label--active theme--light" style="left: 0px; right: auto; position: absolute;">Withdraw</label><input required="required" id="input-140" placeholder="Amount" type="text"></div></div><div class="v-text-field__details"><div class="v-messages theme--light"><div class="v-messages__wrapper"></div></div></div></div></div> <span class="custom-input-hint"><span class="custom-indicator">*</span>Minimum withdraw is <span>$50</span> for commission</span></span></div> <div class="col-sm-6 col-md-12 col-12"><div class="v-input v-input--is-label-active v-input--is-dirty theme--light v-input--selection-controls v-input--radio-group v-input--radio-group--column"><div class="v-input__control"><div class="v-input__slot" style="height: auto;"><div role="radiogroup" aria-labelledby="input-143" class="v-input--radio-group__input"><div class="v-radio theme--light"><div class="v-input--selection-controls__input"><i aria-hidden="true" class="v-icon notranslate mdi mdi-radiobox-blank theme--light"></i><input aria-checked="false" id="input-144" role="radio" type="radio" name="radio-143" value="profit"><div class="v-input--selection-controls__ripple"></div></div><label for="input-144" class="v-label theme--light" style="left: 0px; right: auto; position: relative;">profit</label></div><div class="v-radio theme--light v-item--active"><div class="v-input--selection-controls__input"><i aria-hidden="true" class="v-icon notranslate mdi mdi-radiobox-marked theme--light primary--text"></i><input aria-checked="true" id="input-146" role="radio" type="radio" name="radio-143" value="commission"><div class="v-input--selection-controls__ripple primary--text"></div></div><label for="input-146" class="v-label theme--light" style="left: 0px; right: auto; position: relative;">commission</label></div></div></div><div class="v-messages theme--light"><div class="v-messages__wrapper"></div></div></div></div></div></div></div></form></div> <div class="v-card__actions"><div class="spacer"></div> <button type="button" class="v-btn v-btn--disabled v-btn--flat v-btn--text theme--light v-size--default error" disabled="disabled"><span class="v-btn__content">
                Submit
            </span></button></div></span></div></div></div></section> <section class="my-10"><h2 class="my-5">
      Withdraw Info
    </h2> <div role="alert" class="v-alert my-5 v-sheet theme--dark info"><div class="v-alert__wrapper"><i aria-hidden="true" class="v-icon notranslate v-alert__icon mdi mdi-information theme--dark"></i><div class="v-alert__content">
      You don't have any withdraw Info!
    </div></div></div></section> <section class="my-10"><h2 class="my-5">
      Transactions
    </h2> <div role="alert" class="v-alert my-5 v-sheet theme--dark info"><div class="v-alert__wrapper"><i aria-hidden="true" class="v-icon notranslate v-alert__icon mdi mdi-information theme--dark"></i><div class="v-alert__content">
      You don't have any transactions Info!
    </div></div></div></section></div></div></div></main>
</template>

<script>
export default {

}
</script>

<style>
.v-content{
    margin: -100px 0 0 -250px;

   
}

</style>