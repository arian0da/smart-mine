<template>
<main class="v-content" data-booted="true" style="padding: 64px 0px 0px 256px;">
    <div class="v-content__wrap">
        <div class="container px-6">
            <div class="my-10">
                <h3 class="my-5">Support</h3>
                <section data-v-fa8b9a58 class="my-10 send-ticket-section">
                    <div data-v-fa8b9a58 class="send-ticket-content">
                        <h2 data-v-fa8b9a58 class="my-5">  Send a new Ticket</h2>
                        <div data-v-fa8b9a58 role="dialog" class="v-dialog__container"></div>
                        <button data-v-fa8b9a58 type="button" class="v-btn v-btn--contained v-btn--rounded theme--dark v-size--default primary">
                            <span class="v-btn__content"> New ticket</span>
                        </button>
                    </div>
                    <div data-v-fa8b9a58 class="backdrop-modal"></div>
                </section>
                <section class="my-10">
                    <h2 class="my-5">Tickets history</h2>
                    <div>
                        <div style="background-color: rgb(179, 212, 252); width: 100%; height: 50px; padding: 10px; color: black;">
                            <h2>
                                <span class="primary v-chip v-chip--no-color theme--light v-size--default">
                                    <span class="v-chip__content">
                                        <i aria-hidden="true" class="v-icon notranslate mdi mdi-star-outline theme--light white--text"></i>
                                        <i aria-hidden="true" class="v-icon notranslate mdi mdi-star-outline theme--light white--text"></i>
                                        <i aria-hidden="true" class="v-icon notranslate mdi mdi-star-outline theme--light white--text"></i>
                                    </span>
                                </span>
                                 Click to see management messages
                            </h2>
                        </div>
                        <div class="v-data-table elevation-1 theme--light">
                            <div class="v-data-table__wrapper">
                                <table>
                                    <colgroup>
                                    <col class>
                                    <col class>
                                    <col class>
                                    <col class>
                                    <col class>
                                    </colgroup>

                                    <thead class="v-data-table-header">
                                        <tr>
                                            <th role="columnheader" scope="col" aria-label="Title: Not sorted. Activate to sort ascending." aria-sort="none" class="text-center sortable">
                                                <span>Title</span>
                                                <i aria-hidden="true" class="v-icon notranslate v-data-table-header__icon mdi mdi-arrow-up theme--light" style="font-size: 18px;"></i>
                                            </th>
                                            <th role="columnheader" scope="col" aria-label="Department: Not sorted. Activate to sort ascending." aria-sort="none" class="text-center sortable">
                                                <span>Department</span>
                                                <i aria-hidden="true" class="v-icon notranslate v-data-table-header__icon mdi mdi-arrow-up theme--light" style="font-size: 18px;"></i>
                                            </th>
                                            <th role="columnheader" scope="col" aria-label="Ticket Date: Not sorted. Activate to sort ascending." aria-sort="none" class="text-center sortable">
                                                <span>Ticket Date</span>
                                                <i aria-hidden="true" class="v-icon notranslate v-data-table-header__icon mdi mdi-arrow-up theme--light" style="font-size: 18px;"></i>
                                            </th>
                                            <th role="columnheader" scope="col" aria-label="Status: Not sorted. Activate to sort ascending." aria-sort="none" class="text-center sortable">
                                                <span>Status</span>
                                                <i aria-hidden="true" class="v-icon notranslate v-data-table-header__icon mdi mdi-arrow-up theme--light" style="font-size: 18px;"></i>
                                            </th>
                                            <th role="columnheader" scope="col" aria-label="Details: Not sorted. Activate to sort ascending." aria-sort="none" class="text-center sortable">
                                                <span>Details</span>
                                                <i aria-hidden="true" class="v-icon notranslate v-data-table-header__icon mdi mdi-arrow-up theme--light" style="font-size: 18px;"></i>
                                            </th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr class="v-data-table__empty-wrapper">
                                            <td colspan="5">No data available</td>

                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                            <div class="v-data-footer">
                                <div class="v-data-footer__select">
                                    Rows per page:
                                    <div class="v-input v-input--hide-details v-input--is-label-active v-input--is-dirty theme--light v-text-field v-text-field--is-booted v-select">
                                        <div class="v-input__control">
                                            <div role="button" aria-haspopup="listbox" aria-expanded="false" aria-owns="list-80" class="v-input__slot">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="v-data-footer__pagination"></div>
                                <div class="v-data-footer__icons-before">
                                    <button type="button" disabled="disabled" class="v-btn v-btn--disabled v-btn--flat v-btn--icon v-btn--round v-btn--text theme--light v-size--default" aria-label="Previous page">
                                        <span class="v-btn__content">
                                            <i aria-hidden="true" class="v-icon notranslate mdi mdi-chevron-left theme--light">
                                            </i>
                                        </span>

                                    </button>
                                </div>
                                <div class="v-data-footer__icons-after">
                                    <button type="button" disabled="disabled" class="v-btn v-btn--disabled v-btn--flat v-btn--icon v-btn--round v-btn--text theme--light v-size--default" aria-label="Next page">
                                        <span class="v-btn__content">
                                            <i aria-hidden="true" class="v-icon notranslate mdi mdi-chevron-right theme--light"></i>
                                        </span>

                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </section>

            </div>

        </div>

    </div>

</main>
<!-- <svg id="SvgjsSvg1001" width="2" height="0" xmlns="http://www.w3.org/2000/svg" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:svgjs="http://svgjs.com/svgjs" style="overflow: hidden; top: -100%; left: -100%; position: absolute; opacity: 0;" >
    <defs id="SvgjsDefs1002"> </defs>
    <polyline id="SvgjsPolyline1003" points="0,0"> </polyline>
    <path id="SvgjsPath1004" d="M0 0 "></path>


</svg> -->
</template>

<script>
export default {
    name: 'Support',

}
</script>

<style>
/* .v-application .my-10 {
    margin-top: 40px!important;
    margin-bottom: 40px!important;
}
* {
    background-repeat: no-repeat;
    padding: 0;
    margin: 0;
}
*, :after, :before {
    box-sizing: inherit;
}
div {
    display: block;
}
.v-application--wrap {
    font-family: Assistant,sans-serif;
}
html {
    font-size: 16px;
    overflow-x: hidden;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-tap-highlight-color: rgba(0,0,0,0);
}
html {
    box-sizing: border-box;
    overflow-y: scroll;
    -webkit-text-size-adjust: 100%;
}
:after, :before {
    text-decoration: inherit;
    vertical-align: inherit;
}
::selection {
    background-color: #b3d4fc;
    color: #000;
    text-shadow: none;
} */
element.style {
    background-color: rgb(179, 212, 252);
    width: 100%;
    height: 50px;
    padding: 10px;
    color: black;
}
.v-chip.v-size--default {
    border-radius: 16px;
    font-size: 14px;
    height: 32px;
}
.v-chip {
    align-items: center;
    cursor: default;
    display: inline-flex;
    line-height: 20px;
    max-width: 100%;
    outline: none;
    overflow: hidden;
    padding: 0 12px;
    position: relative;
    text-decoration: none;
    transition-duration: .28s;
    transition-property: box-shadow,opacity;
    transition-timing-function: cubic-bezier(.4,0,.2,1);
    vertical-align: middle;
    white-space: nowrap;
}
.v-content{
    margin: -100px 0 0 -250px;

   
}
</style>