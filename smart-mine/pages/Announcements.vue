<template>
   

 <main class="v-content" data-booted="true" style="padding: 64px 0px 0px 256px;">
    <div class="v-content__wrap">
      <div class="container px-6">
        <div class="my-10"> 
          <h3 class="my-5">Announcements</h3>

      <div>
          <section class="announcements-section">
          <div class="announcement-card my-12 pa-6 d-flex flex-column v-card v-sheet theme--light">
          <div aria-label="" class="v-responsive v-image responsive-img" style="height: 300px; width: 100%;">
          <div class="v-image__image v-image__image--preload v-image__image--cover" style="background-position: center center;">
          </div>
          <div class="v-responsive__content">

            <v-carousel>
              <v-carousel-item
                v-for="(item,i) in items"
                :key="i"
                :src="item.src"
                reverse-transition="fade-transition"
                transition="fade-transition">
            </v-carousel-item>
            </v-carousel>
        </div>
      </div>
    <div class="d-flex flex-column flex-sm-row justify-space-between align-center">
    <div class="text-center text-sm-left">
    <div class="v-card__title px-0">
    <h2 class="announcement-title">
        <div v-for="news1 in news1S.data" :key="news1.id">
    <div :to="{ name: 'news1-id', params: { id: news1.id } }" >
        {{ news1.attributes.title }}  
    </div>
  </div>
</h2>
</div>
    <div class="v-card__subtitle px-0">
    <p class="announcement-summery">
        <div v-for="news1 in news1S.data" :key="news1.id" >
    <div :to="{ name: 'news1-id', params: { id: news1.id } }">
      {{ news1.attributes.title }}
    </div>
  </div>
</p>
</div>
</div> 
    <div class="text-center text-sm-right d-flex flex-column flex-sm-row mb-6">
    <div class="mr-0 mr-sm-2 mb-2 mb-sm-0 d-flex align-center flex-column flex-sm-row">
    <span class="success mr-0  mr-sm-2 v-chip v-chip--no-color theme--light v-size--default" rounded="">
    <span class="v-chip__content">
        <i aria-hidden="true" class="v-icon notranslate mdi mdi-calendar-range theme--light" style="color: rgb(255, 255, 255); caret-color: rgb(255, 255, 255);"></i>
                            Publish Date:
    </span>
    </span>
    <div v-for="news1 in news1S.data" :key="news1.id" >
    <div :to="{ name: 'news1-id', params: { id: news1.id } }">
      {{ news1.attributes.Date }}
    </div>
  </div>
</div> 
<div class="d-flex align-center flex-column flex-sm-row">
    <span class="error mr-0 mr-sm-2 v-chip v-chip--no-color theme--light v-size--default" rounded="">
        <span class="v-chip__content">
            <i aria-hidden="true" class="v-icon notranslate mdi mdi-account-edit theme--light" style="color: rgb(255, 255, 255); caret-color: rgb(255, 255, 255);"></i>
        Author:
        
    </span>
    </span>
    <div v-for="news1 in news1S.data" :key="news1.id" style="color:red;">
<div :to="{ name: 'news1-id', params: { id: news1.id } }" >
    {{ news1.attributes.Author }}
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="v-card__text pa-0 text-justify">
    <div v-for="news1 in news1S.data" :key="news1.id" style="color:red;">
<div :to="{ name: 'news1-id', params: { id: news1.id } }">
  {{ news1.attributes.text_area}}
</div>
  </div>
  </div>
  </div>
  </section>
  </div> 
  <div data-v-9b27b732="" class="text-center pa-6">
    <button data-v-9b27b732="" type="button" disabled="disabled" class="ma-2 error v-btn v-btn--contained v-btn--disabled theme--light v-size--default" style="background-color: white;">
      <span class="v-btn__content">
        Prev
    </span>
    </button>
     <button data-v-9b27b732="" type="button" class="v-btn v-btn--contained theme--light v-size--default" style="width: 40px;background-color: white;">
      <span class="v-btn__content">
        1
    </span>
    </button> 
    <button data-v-9b27b732="" type="button" disabled="disabled" class="ma-2 error v-btn v-btn--contained v-btn--disabled theme--light v-size--default" style="width: 40px;background-color: white;">
      <span class="v-btn__content">
        Next
    </span>
    </button>
    </div>
    </div>
    </div>
    </div>
    </main>
</template>

<script>
import gql from 'graphql-tag'
export default{
    data(){
        return{
            news1S:[],
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
},
    apollo:{
        news1S:{
                query: gql`
                    query{
                        news1S{ 
                            data{
                            attributes{
                                title
                                Date
                                Author
                                text_area
                                
                            }
                        }
                                
                    }
            }`,

        },
    },
}
</script>
<style>
.v-content{
    margin: -100px 0 0 -250px; 
  
}
</style>