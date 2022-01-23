<template>
  <div>
    <div class="portfolio-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Portfolio Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10" md="9" lg="7">
            <div class="text-center">
              <h2 class="section-title font-weight-medium">
                Projets
              </h2>
              <p>Chaque année, l'atlier organise et supporte les projets des adhérants. Ce projets sont autant d'opportunité pour trouver l'insipiration et explorer des thématiques durant les differents ateliers.
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Portfolio Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Portfolio
        ----------------------------------------------- -->
        <v-row class="mt-13">
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/projets/Expo-festivites.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                
                <h5 class="font-weight-medium font-18">
                  Exposition Les Festivités
                </h5>
                <p class="font-14 mb-0"><v-icon> mdi-map-marker </v-icon> Ateliers Les Créarts</p>
                <!-- <p class="font-14 mb-0">Digital Marketing</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/projets/Expo-palimpsestes.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Exposition Palimpsestes</h5>
                <p class="font-14 mb-0"><v-icon> mdi-map-marker </v-icon> Galerie 9, Nancy</p>
                <!-- <p class="font-14 mb-0">Admin templates</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/projets/Expo-Curedair.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                
                <h5 class="font-weight-medium font-18">Exposition l'Art de  Créer</h5>
                <p class="font-14 mb-0"><v-icon> mdi-map-marker </v-icon> Parc de la cure d'air, Nancy</p>
                <!-- <p class="font-14 mb-0">Branding</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/projets/Expo-bonsai.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Expositions Bonsai</h5>
                <p class="font-14 mb-0"><v-icon> mdi-map-marker </v-icon> Ateliers Les Créarts</p>
                <!-- <p class="font-14 mb-0">Search Engine</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <!-- <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/portfolio/img5.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Exposition ...</h5>
                <p class="font-14 mb-0"><v-icon> mdi-map-marker </v-icon> Addresse</p>
                <p class="font-14 mb-0">Wll Mockup</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/portfolio/img6.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Exposition ...</h5>
                <p class="font-14 mb-0"><v-icon> mdi-map-marker </v-icon> Addresse</p>
              </v-card-text>
            </v-card>
          </v-col> -->
        </v-row>

        <!-- -----------------------------------------------
            End Portfolio
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "PortfolioProjets",
  data() {
    return {};
  },
  methods: {},
};
</script>
