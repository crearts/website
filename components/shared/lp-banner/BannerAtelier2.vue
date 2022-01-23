<template>
  <div class="banner-wrapper">
    <v-container>
      <!-- -----------------------------------------------
            Start Banner
        ----------------------------------------------- -->
      <v-row justify="center">
        <v-col cols="12" md="12" lg="12" class="d-flex align-center">
          <v-img
            :src="require('@/assets/images/banner/IMG_20210925_205722.jpg')"
            alt="banner"
          />
        </v-col>
      </v-row>

      <!-- -----------------------------------------------
            End Banner
        ----------------------------------------------- -->
    </v-container>
  </div>
</template>
<script>
export default {
  name: "BannerAtelier2",
  data() {
    return {};
  }
};
</script>
