<template>
  <div>
    <h2>Invoice Page</h2>
    <div class="row">
      <div class="col col-12">
        <div class="v-card v-sheet theme--light">
          <div primary-title="" class="v-card__title headline grey lighten-2">
            Package Details
          </div>
          <div class="v-responsive v-image" style="height: 200px">
            <div
              class="v-responsive__sizer"
              style="padding-bottom: 165.694%"
            ></div>
            <div
              class="v-image__image v-image__image--cover"
              style="
                background-image: url('https://api.cloudminepro.com/images/package/1599479279-21779.jpg');
                background-position: center center;
              "
            ></div>
            <div class="v-responsive__content" style="width: 720px"></div>
          </div>
          <div class="v-card__text">
            <div class="row">
              <div class="col-md-6 col-12">
                <ul class="package-details-list">
                  <li>
                    <span class="ma-2 v-chip theme--light v-size--default blue"
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-package-variant-closed
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white">Name:</span></span
                      ></span
                    >
                    <span class="list-item-data">New package 100 $</span>
                  </li>
                  <li>
                    <span
                      class="ma-2 v-chip theme--light v-size--default orange"
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-currency-usd
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white">Price:</span></span
                      ></span
                    >
                    <span class="list-item-data">100 $</span>
                  </li>
                  <li>
                    <span
                      class="
                        ma-2
                        v-chip
                        theme--light
                        v-size--default
                        pink
                        accent-4
                      "
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-currency-usd
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white">Fee:</span></span
                      ></span
                    >
                    <span class="list-item-data">17.5 $</span>
                  </li>
                  <li>
                    <span
                      class="ma-2 v-chip theme--light v-size--default purple"
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-diamond
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white"
                          >Package CMP Price:</span
                        ></span
                      ></span
                    >
                    <span class="list-item-data"> 400 CMP </span>
                  </li>
                  <li>
                    <span class="ma-2 v-chip theme--light v-size--default blue"
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-lead-pencil
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white">Summary:</span></span
                      ></span
                    >
                    <span class="list-item-data"
                      >this is the new 117.5 $ package</span
                    >
                  </li>
                </ul>
              </div>
              <div class="col-md-6 col-12">
                <ul class="package-details-list">
                  <li>
                    <span class="ma-2 v-chip theme--light v-size--default blue"
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-currency-usd-circle
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white">Profit Limit:</span></span
                      ></span
                    >
                    <span class="list-item-data">200 %</span>
                  </li>
                  <li>
                    <span
                      class="ma-2 v-chip theme--light v-size--default orange"
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-percent
                            theme--light
                            white--text
                          "
                        ></i>
                        <span style="color: white"
                          >Daily Profit Percentage:</span
                        ></span
                      ></span
                    >
                    <span class="list-item-data"> 0.5 % up to 1 % </span>
                  </li>
                  <li>
                    <span
                      class="
                        ma-2
                        v-chip
                        theme--light
                        v-size--default
                        pink
                        accent-4
                        white--text
                      "
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-wallet
                            theme--light
                          "
                        ></i>
                        Wallet Amount:
                      </span></span
                    >
                    <span class="list-item-data">0 $</span>
                  </li>
                  <li>
                    <span
                      class="
                        ma-2
                        v-chip
                        theme--light
                        v-size--default
                        purple
                        white--text
                      "
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-wallet
                            theme--light
                          "
                        ></i>
                        Voucher Wallet Amount:
                      </span></span
                    >
                    <span class="list-item-data">0 $</span>
                  </li>
                  <li>
                    <span
                      class="
                        ma-2
                        v-chip
                        theme--light
                        v-size--default
                        blue
                        white--text
                      "
                      ><span class="v-chip__content"
                        ><i
                          aria-hidden="true"
                          class="
                            v-icon
                            notranslate
                            mr-2
                            mdi mdi-wallet
                            theme--light
                          "
                        ></i>
                        CMP Wallet Amount:
                      </span></span
                    >
                    <span class="list-item-data">0 CMP</span>
                  </li>
                  <li></li>
                </ul>
              </div>
            </div>
            <div
              role="alert"
              class="v-alert v-sheet theme--light v-alert--text green--text"
            >
              <div class="v-alert__wrapper">
                <div class="v-alert__content">
                  <h3 class="text-h5">
                    <span style="color: darkgreen; font-weight: bolder"
                      >Voucher Notice</span
                    >
                  </h3>
                  <div>
                    If you want to use the voucher, please check it later and
                    enter the desired amount
                  </div>
                  <div>
                    <span style="color: darkgreen; font-weight: bolder"
                      >* Max voucher</span
                    >
                    amount can use for
                    <span style="color: darkgreen; font-weight: bolder"
                      >USDT</span
                    >
                    payments is
                    <span style="color: darkgreen; font-weight: bolder"
                      >0$</span
                    >
                  </div>
                  <div>
                    <span style="color: darkgreen; font-weight: bolder"
                      >* Max voucher</span
                    >
                    amount can use for
                    <span style="color: darkgreen; font-weight: bolder"
                      >CMP</span
                    >
                    payments is
                    <span style="color: darkgreen; font-weight: bolder"
                      >0$</span
                    >
                  </div>
                  <hr
                    role="separator"
                    aria-orientation="horizontal"
                    class="my-4 info v-divider theme--light"
                    style="opacity: 0.22"
                  />
                  <div class="row no-gutters align-center">
                    <div class="col-lg-1 col-1">
                      <div
                        class="
                          v-input
                          shrink
                          mr-2
                          mt-0
                          v-input--hide-details
                          theme--light
                          v-input--selection-controls v-input--checkbox
                        "
                      >
                        <div class="v-input__control">
                          <div class="v-input__slot">
                            <div class="v-input--selection-controls__input">
                              <i
                                aria-hidden="true"
                                class="
                                  v-icon
                                  notranslate
                                  mdi mdi-checkbox-blank-outline
                                  theme--light
                                "
                              ></i
                              ><input
                                aria-checked="false"
                                id="input-88"
                                role="checkbox"
                                type="checkbox"
                                value=""
                              />
                              <div
                                class="v-input--selection-controls__ripple"
                              ></div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-4 col-11">
                      <div
                        class="
                          v-input
                          v-input--is-label-active
                          v-input--is-dirty
                          v-input--is-disabled
                          theme--light
                          v-text-field v-text-field--is-booted
                        "
                      >
                        <div class="v-input__control">
                          <div class="v-input__slot">
                            <div class="v-text-field__slot">
                              <label
                                for="input-90"
                                class="
                                  v-label v-label--active v-label--is-disabled
                                  theme--light
                                "
                                style="
                                  left: 0px;
                                  right: auto;
                                  position: absolute;
                                "
                                >Enter the amount of voucher used </label
                              ><input
                                id="input-90"
                                type="text"
                                disabled="disabled"
                              />
                            </div>
                          </div>
                          <div class="v-text-field__details">
                            <div class="v-messages theme--light">
                              <div class="v-messages__wrapper"></div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-3 col-12">
                      <button
                        type="button"
                        class="
                          v-btn v-btn--depressed v-btn--disabled
                          theme--light
                          elevation-2
                          v-size--x-small
                        "
                        plain=""
                        raised=""
                        disabled="disabled"
                      >
                        <span class="v-btn__content"
                          ><span style="color: white"
                            >USDT Voucher MAX</span
                          ></span
                        >
                      </button>
                      <button
                        type="button"
                        class="
                          v-btn v-btn--depressed v-btn--disabled
                          theme--light
                          elevation-2
                          v-size--x-small
                        "
                        plain=""
                        raised=""
                        disabled="disabled"
                      >
                        <span class="v-btn__content"
                          ><span style="color: white"
                            >CMP Voucher MAX</span
                          ></span
                        >
                      </button>
                    </div>
                    <div class="spacer"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <hr
            role="separator"
            aria-orientation="horizontal"
            class="v-divider theme--light"
          />
          <div class="v-card__actions">
            <span class="invoice-calc"
              ><span class="ma-2 v-chip theme--light v-size--default purple"
                ><span class="v-chip__content"
                  ><span style="color: white">Package amount:</span></span
                ></span
              >
              <span>100 $ + </span>
              <span
                class="
                  ma-2
                  v-chip
                  theme--light
                  v-size--default
                  pink
                  accent-4
                  white--text
                "
                ><span class="v-chip__content"
                  ><span style="color: white">Fee amount:</span></span
                ></span
              >
              <span>17.5 $ = </span>
              <span
                class="
                  ma-2
                  v-chip
                  theme--light
                  v-size--default
                  orange
                  white--text
                "
                ><span class="v-chip__content"
                  ><span style="color: white">Package total price:</span></span
                ></span
              >
              <span>117.5 $ </span></span
            >
            <div class="spacer"></div>
            <div role="dialog" class="v-dialog__container"><!----></div>
            <!-- <button
              type="button"
              class="v-btn v-btn--contained theme--light v-size--default blue"
              role="button"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="v-btn__content"><span style="color: white">Buy Package</span></span>
            </button> -->
            <v-row justify="center">
              <v-dialog v-model="dialog" scrollable max-width="300px">
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    color="primary"
                    v-bind="attrs"
                    v-on="on"
                    class="
                      v-btn v-btn--contained
                      theme--light
                      v-size--default
                      blue
                    "
                  >
                    <span class="v-btn__content"
                      ><span style="color: white">Buy Package</span></span
                    >
                  </v-btn>
                </template>
                <v-card>
                  <v-card-title>Select Country</v-card-title>
                  <v-divider></v-divider>
                  <v-card-text style="height: 300px">
                    <v-radio-group v-model="dialogm1" column>
                      <v-radio label="USDT (trc20)" value="USDT (trc20)"></v-radio>
                      <v-radio label="CMP" value="CMP"></v-radio>
                    </v-radio-group>
                  </v-card-text>
                  <v-divider></v-divider>
                  <v-card-actions>
                    <v-btn color="blue darken-1" text @click="dialog = false">
                      Close
                    </v-btn>
                    <v-btn color="blue darken-1" text @click="dialog = false">
                      Go
                    </v-btn>
                  </v-card-actions>
                </v-card>
              </v-dialog>
            </v-row>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
 export default {
    data () {
      return {
        dialogm1: '',
        dialog: false,
      }
    },
  }
</script>

<style>
</style>