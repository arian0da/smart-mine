<template>
  <v-app dark>
    <v-navigation-drawer
      v-model="drawer"
      :mini-variant="miniVariant"
      :clipped="clipped"
      fixed
      app
    >
      <v-list>
        <div class="v-navigation-drawer__prepend" style="border-bottom:2px solid #444444">
          <div tabindex="-1" class="v-list-item v-list-item--two-line theme--light">
            <div class="v-avatar v-list-item__avatar" style="height: 40px; min-width: 40px; width: 40px;">
              <img src="../static/SMT-100-removebg-preview.png" class="Panel-icone">
              </div> <div class="v-list-item__content">
                <div class="v-list-item__title" style="color: white;">Welcome to</div>
                 <div class="v-list-item__subtitle" style="color: white;">Smart Mine</div>
                 </div>
                 </div>
              </div>
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
        >
        
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
      
    </v-navigation-drawer>
    

    <v-app-bar :clipped-left="clipped" fixed app>

      <v-app-bar-nav-icon @click.stop="drawer = !drawer" />

      <!-- <v-btn icon @click.stop="miniVariant = !miniVariant">
        <v-icon>mdi-{{ `chevron-${miniVariant ? 'right' : 'left'}` }}</v-icon>
      </v-btn> -->

      <!-- <v-btn icon @click.stop="clipped = !clipped">
        <v-icon>mdi-application</v-icon>
      </v-btn> -->

      <!-- <v-btn icon @click.stop="fixed = !fixed">
        <v-icon>mdi-minus</v-icon>
      </v-btn> -->
      
      

      <v-toolbar-title v-text="title" />
      <v-spacer />

      <!-- <v-btn icon @click.stop="rightDrawer = !rightDrawer">
        <v-icon>mdi-menu</v-icon>
      </v-btn> -->
      
    </v-app-bar>

    <v-main>
      <v-container class="v-container">
        <Nuxt />
      </v-container>
    </v-main>

    <v-navigation-drawer v-model="rightDrawer" :right="right" temporary fixed>
      <v-list>
        <v-list-item @click.native="right = !right">
          <v-list-item-action>
            <v-icon light> mdi-repeat </v-icon>
          </v-list-item-action>
          <v-list-item-title>Switch drawer (click me)</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    
    <!-- <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer> -->
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-monitor-dashboard',
          title: 'Dashboard',
          to: '/Dashboard',
        },
        {
          icon: 'mdi-card-account-details',
          title: 'Profile',
          to: '/profile',
        },
        {
          icon: 'mdi-wan',
          title: 'MyNetwork',
          to: '/MyNetwork',
        },
        {
          icon: 'mdi-server-network',
          title: 'NetworkAccounting',
          to: '/NetworkAccounting',
        },
        {
          icon: 'mdi-bullhorn',
          title: 'Announcements',
          to: '/Announcements',
        },
        {
          icon: 'mdi-trademark',
          title: ' LiveTrades',
          to: '/LiveTrades',
        },
        {
          icon: 'mdi-gift',
          title: 'Packages',
          to: '/Packages',
        },
        {
          icon: 'mdi-credit-card-outline',
          title: 'Vouchers',
          to: '/Vouchers',
        },
        {
          icon: 'mdi-headphones',
          title: 'Support',
          to: '/Support',
        },
        {
          icon: 'mdi-account-cash',
          title: 'Accounting',
          to: '/Accounting',
        },
      
        {
          icon: 'mdi-logout',
          title: 'Log out',
          to: '/Login',
        },

      
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'smart mine',
    }
  },
}
</script>
<style>
.Panel-icone{
  background-color:rgb(255, 255, 255);
}
::-webkit-scrollbar {
	background: transparent;
	width: 8px;
	height: 5px;
}

::-webkit-scrollbar-thumb {
	background-color: #232323;
}

::-webkit-scrollbar-thumb:hover {
	background-color: rgba(50, 50, 50, 0.3);
}
.v-container{
  color: rgb(255, 255, 255);
}
</style>
