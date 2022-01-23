<template>
  <div>
    <!-- -----------------------------------------------
          Start Header
    ----------------------------------------------- -->
    <!-- <v-app-bar app absolute class="app-header" flat elevate-on-scroll> -->
    <v-app-bar app absolute class="app-header position-relative navbar-light header1" flat>
      <v-container class="py-0 fill-height">
        <!-- Logo -->
        <Logo />
        <!-- <div class="logo">
          <NLink to="/">
            <v-img
              :src="require('@/layouts/sections/Logo-crearts-simple.png')"
              alt="logo"
            />
          </NLink>
        </div> -->

        <v-spacer></v-spacer>
        <v-btn class="d-block d-md-none" text @click="toggleClass()">
          <!-- <v-app-bar-nav-icon class="white--text" /> -->
          <v-app-bar-nav-icon />
        </v-btn>
        <!-- Desktop view Navigation -->
        <div
          class="navigation"
          v-bind:class="[isActive ? 'd-block' : '']"
          @click="isActive = !isActive"
        >
          <ul class="navbar-nav">
            <li class="nav-item" text>
              <n-link class="nav-link" nuxt to="/">Qui Sommes-Nous ?</n-link>
            </li>
            <li class="nav-item" text>
              <n-link class="nav-link" nuxt to="/activites">Activités</n-link>
            </li>
            <li class="nav-item" text>
              <n-link class="nav-link" nuxt to="/contact">Contact</n-link>
            </li>
            <li class="nav-item" text>
              <!-- login-regiter -->
              <v-btn
                class="nav-link"
                color="d-none d-lg-flex btn-custom-nm ml-5"
                nuxt
                target="_blank"
                href="https://www.helloasso.com/associations/gem-les-crearts/adhesions/adhesion-annuelle"
                elevation="0"
              >
                Adhérer
              </v-btn>
            </li>
            <!-- <li class="nav-item" text>
              <v-btn
                color="white"
                nuxt
                target="_blank"
                href="https://www.wrappixel.com/templates/nextkit-nuxtjs-free-uikit/"
                elevation="0"
              >
                Soutenir
              </v-btn>
            </li> -->
          </ul>
        </div>
      </v-container>
    </v-app-bar>
    <!-- -----------------------------------------------
          End Header
    ----------------------------------------------- -->
  </div>
</template>

<script>
export default {
  name: "Header",

  components: {
    Logo: () => import("@/layouts/sections/Logo")
  },
  data() {
    return {
      isActive: false
    };
  },
  methods: {
    toggleClass: function(event) {
      this.isActive = !this.isActive;
    }
  }
};
</script>
