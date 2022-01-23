import { mdiAccountGroup } from '@mdi/js'; 
<template>
  <div>
    <div class="feature1-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Feature 1 Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" md="10" lg="7">
            <div class="text-center">
              <!-- <v-chip small color="error" text-color="white">
                Feature 1
              </v-chip> -->
              <h2 class="section-title font-weight-medium">
                Nos missions
              </h2>
              <!-- <p>
                You can relay on our amazing features list and also our customer
                services will be great experience for you without doubt and in
                no-time
              </p> -->
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 1 Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Feature 1
        ----------------------------------------------- -->
        <v-row justify="center" class="mt-13">
          <v-col cols="12" md="6">
            <v-card elevation="0">
              <v-card-text>
                <div class="icon-round bg-light-info">
                  <i class="mdi mdi-bullhorn"></i>
                </div>
                <h5 class="font-weight-medium font-18">Permettre à chaqu'un de s'exprimer</h5>
                <p class="mt-10 mb-8">
                  Lorem ipsum dolor
                  sit amet, consectetur adipiscing elit. Praesent tristique
                  pellentesque ipsum.
                </p>
                <!-- <a
                  href="#"
                  class="
                    text-themecolor
                    linking
                    text-decoration-none
                    d-flex
                    align-center
                  "
                >
                  Explore More <i class="mdi mdi-arrow-right"></i>
                </a> -->
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card elevation="0">
              <v-card-text>
                <div class="icon-round bg-light-info">
                  <i class="mdi mdi-share-variant"></i>
                </div>
                <h5 class="font-weight-medium font-18">Créer du lien</h5>
                <p class="mt-10 mb-8">
                  Lorem ipsum dolor
                  sit amet, consectetur adipiscing elit. Praesent tristique
                  pellentesque ipsum.
                </p>
                <!-- <a
                  href="#"
                  class="
                    text-themecolor
                    linking
                    text-decoration-none
                    d-flex
                    align-center
                  "
                >
                  Explore More <i class="mdi mdi-arrow-right"></i>
                </a> -->
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 1
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Missions",
  data() {
    return {};
  },
  methods: {},
};
</script>
