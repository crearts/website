<template>
  <div>

    <BannerImg1/>

    <BannerDesc />

    <!-- <AllCustomComponents /> -->
 
    <C2Aactivites />

    <Missions />

  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "GEM Les Crearts | Accueil",
      meta: [
        {
          hid: "Description de l'association",
          name: "GEM Les Crearts",
          content: "Acceuil",
        },
      ],
    };
  },

  data() {
    return {};
  },
  components: {
    
    BannerDesc: () => import("@/components/shared/lp-banner/BannerDescription"),
    BannerImg1: () => import("@/components/shared/lp-banner/BannerImage1"),
    C2Aactivites : () => import("@/components/custom/c2a/C2Aactivites"),
    Missions : () => import("@/components/custom/features/Missions")
  },
};
</script>
