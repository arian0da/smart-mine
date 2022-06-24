<template>
  <main
    class="v-content"
    data-booted="true"
    style="padding: 64px 0px 0px 256px"
  >
    <div class="v-content__wrap">
      <div class="container px-6">
        <div class="my-10">
          <h3 class="my-5">Packages</h3>
          <section class="my-10">
            <h2 class="my-5">Packages List, choose your favorite one!</h2>
            <div class="packages-wrapper">
              <div class="row">
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
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
                      <div
                        class="v-responsive__content"
                        style="width: 720px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 100.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 100 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 117.5 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <div class="text-center">
                          <v-dialog v-model="dialog" width="500">
                            <template v-slot:activator="{ on, attrs }">
                              <v-btn
                                color=""
                                dark
                                v-bind="attrs"
                                v-on="on"
                                class="primary"
                              >
                                <span class="v-btn__content">
                                  More Details
                                </span>
                              </v-btn>
                            </template>

                            <v-card>
                              <v-card-title class="text-h5 grey lighten-2">
                                Package Details
                              </v-card-title>

                              <v-card-text>
                                Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit, sed do eiusmod tempor
                                incididunt ut labore et dolore magna aliqua. Ut
                                enim ad minim veniam, quis nostrud exercitation
                                ullamco laboris nisi ut aliquip ex ea commodo
                                consequat. Duis aute irure dolor in
                                reprehenderit in voluptate velit esse cillum
                                dolore eu fugiat nulla pariatur. Excepteur sint
                                occaecat cupidatat non proident, sunt in culpa
                                qui officia deserunt mollit anim id est laborum.
                              </v-card-text>

                              <v-divider></v-divider>

                              <v-card-actions>
                                <v-spacer></v-spacer>
                                <v-btn
                                  color="primary"
                                  text
                                  @click="dialog = false"
                                >
                                  CANCEL
                                </v-btn>
                                <v-btn>
                                  <nuxt-link to="/Packages/invoice/1"
                                    >Go to Invoice preview</nuxt-link
                                  >
                                </v-btn>
                              </v-card-actions>
                            </v-card>
                          </v-dialog>
                        </div>

                        <!-- <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        
                      </div> -->
                      </div>
                    </div>
                  </div>
                </div>

                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 165.694%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1596410401-26163.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 720px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 250.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 250 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 270 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 165.694%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627156995-15601.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 720px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 500.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 500 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 515 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 195.37%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1616749459-62239.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 540px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 750.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 750 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 772.5 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 165.694%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1596410478-81617.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 720px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 1000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 1000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 1030 $package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 195.37%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1616749530-32665.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 540px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 2000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 2000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 2030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 165.694%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1596410509-81774.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 720px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 3000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 3000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this iss the new 3030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 158.358%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627424590-94427.jpg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 682px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 4000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 4000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 4030 $ packege
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 179.402%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157105-26184.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 602px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 5000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 5000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 5030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 174.475%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157116-42116.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 619px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 10000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 10000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 10030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 162.162%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157142-39897.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 666px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 15000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 15000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 15030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 177.924%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157165-32557.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 607px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 20000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 20000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 20030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 176.759%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157185-37454.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 611px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 30000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 30000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 30030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 177.34%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157204-63125.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 609px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 40000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 40000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 40030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                  <div
                    class="
                      custom-package-card
                      v-card v-card--outlined
                      v-sheet
                      theme--light
                    "
                    style="max-width: 344px"
                  >
                    <div class="v-responsive v-image" style="height: 150px">
                      <div
                        class="v-responsive__sizer"
                        style="padding-bottom: 177.924%"
                      ></div>
                      <div
                        class="v-image__image v-image__image--cover"
                        style="
                          background-image: url('https://api.cloudminepro.com/images/package/1627157221-97237.jpeg');
                          background-position: center center;
                        "
                      ></div>
                      <div
                        class="v-responsive__content"
                        style="width: 607px"
                      ></div>
                    </div>
                    <div
                      tabindex="-1"
                      class="v-list-item v-list-item--three-line theme--light"
                    >
                      <div class="v-list-item__content">
                        <div class="overline mb-4">price: 50000.00 $</div>
                        <div class="v-list-item__title headline mb-1">
                          New package 50000 $
                        </div>
                        <div class="v-list-item__subtitle">
                          this is the new 50030 $ package
                        </div>
                      </div>
                    </div>
                    <div class="text-center package-card-footer">
                      <div class="v-card__actions">
                        <button
                          type="button"
                          class="
                            primary
                            v-btn v-btn--flat v-btn--text
                            theme--light
                            v-size--default
                          "
                        >
                          <span class="v-btn__content"> More Details </span>
                        </button>
                      </div>
                      <div role="dialog" class="v-dialog__container">
                        <!---->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
        </div>
      </div>
    </div>
  </main>
</template>

<script type="text/javascript" src="http://localhost:1337/plugins/strapi-stripe/static/stripe.js" >
</script>
<script>
// import {productQuery} from '../../qraphql/query';
import gql from 'graphql-tag';
export default {
  data() {
    return {
      dialog: false,
      products: [],
    }
  },
  apollo: {
    products: {
      query: gql`
        query {
          product0S {
            data {
              id
              attributes {
                Name
                Summary
                Price
                PackageCMPPrice
                Fee
                ProfitLimit
                DailyProfitPercentage
                WalletAmount
                VoucherWalletAmount
                CMPWalletAmount
              }
            }
          }
        }
      `,
    },
  },
  mounted() {
    console.log("products",this.products);
  },
}
</script>

<style>
.v-content {
  margin: -100px 0 0 -250px;
}
</style>