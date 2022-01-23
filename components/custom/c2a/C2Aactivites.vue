<template>
  <div>
    <div class="c2a1-spacer primary">
      <v-container>
        <!-- -----------------------------------------------
            Start Call-2-Action
        ----------------------------------------------- -->
        <div class="d-block d-md-flex align-center">
          <h2 class="c2a-title white--text font-weight-medium">
            Vous voulez en savoir plus sur les projets réalisés? 
          </h2>
          <div class="ml-auto mt-5 mt-md-0">
            <v-btn
              nuxt
              large
              to="/activites"
              class="btn-custom-md"
              outlined
              color="white"
              elevation="0"
              block
            >
              Découvrez nos activités
            </v-btn>
          </div>
        </div>

        <!-- -----------------------------------------------
            End Call-2-Action
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "C2Aactivites",
  data() {
    return {};
  },
  methods: {},
};
</script>
