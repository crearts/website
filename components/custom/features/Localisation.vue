<template>
  <div>
    <div class="feature3-component mini-spacer">
      <v-container class="position-relative">
        <!-- -----------------------------------------------
            Start Feature 3 Text
        ----------------------------------------------- -->
        <v-row>
          <v-col cols="12" lg="10">
            <v-img
              :src="require('@/assets/images/CreartMap.png')"
              alt="access map"
              class="rounded"
            />
          </v-col>
          <v-col cols="12" md="7" lg="5" class="feature3-card">
            <v-card class="card-shadow">
              <v-card-text>
                <div class="pa-10 text-center">
                  <!-- <v-chip small color="info" text-color="white">
                    Accèder au GEM Les Crearts
                  </v-chip> -->
                  <h3 class="feature3-title font-weight-medium">
                    Accèder au GEM Les Crearts
                  </h3>
                  <p>
                    L'atelier est à deux pas du centre ville. Il est à 4 minutes des arrets de bus de la place Charles III et du marché centrale.
                  </p>
                  <v-btn
                    color="error"
                    class="btn-custom-lg linking mt-10 btn-arrow"
                    nuxt
                    large
                    href="https://www.google.fr/maps/place/9+Rue+des+S%C5%93urs+Macarons,+54000+Nancy/@48.6890873,6.1845644,17z/"
                    elevation="0"
                  >
                    <span>Y aller !</span>
                    <i class="mdi mdi-arrow-right"></i>
                  </v-btn>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 3 Text
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Feature3",
  data() {
    return {};
  },
  methods: {},
};
</script>
