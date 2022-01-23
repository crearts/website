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
                Ateliers et Activités
              </h2>
              <p>Les membres de l'association se reunissent de maniere reguliere pour travailler et explorer differentes techniques et sujet de création. 
                La regularité des ateliers depend des disponibilité des personnes qui l'animent, cela peut être hebdomadaire ou bimensuelle. 
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
                  src="@/assets/images/activites/atelier-terre.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <v-chip class="ma-2" color="primary">Bimensuel</v-chip>
                <h5 class="font-weight-medium font-18">
                  Atelier terre
                </h5>
                <!-- <p class="font-14 mb-0">Digital Marketing</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/activites/atelier-textile.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <v-chip class="ma-2" color="primary">Hebdomadaire</v-chip>
                <h5 class="font-weight-medium font-18">Atelier Art Textile</h5>
                <!-- <p class="font-14 mb-0">Admin templates</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/activites/atelier-multi.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <v-chip class="ma-2" color="primary">Hebdomadaire</v-chip>
                <h5 class="font-weight-medium font-18">Atelier Multitechnique</h5>
                <!-- <p class="font-14 mb-0">Branding</p> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/activites/atelier-lino.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <v-chip class="ma-2" color="warning" text-color="white">
            Terminé
          </v-chip>
                <h5 class="font-weight-medium font-18">Atelier Linogravure</h5>
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
                <v-chip class="ma-2" color="warning" text-color="white">
            Terminé
          </v-chip>
                <h5 class="font-weight-medium font-18">Atelier Banzaie</h5>
              </v-card-text>
            </v-card>
          </v-col> -->
          <!-- <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/portfolio/img6.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Hard Cover Book Mock</h5>
                <p class="font-14 mb-0">Book Covers</p>
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
  name: "PortfolioActivites",
  data() {
    return {};
  },
  methods: {},
};
</script>
