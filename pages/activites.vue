<template>
  <div>
    <!-- -----------------------------------------------
    Banner
    ----------------------------------------------- -->
    <BannerImg2 />
    <Portfolio />
    <C2Aadherer />
    <PortfolioProjets />
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
    BannerImg2: () => import("@/components/shared/lp-banner/BannerImage2"),
    Portfolio: () => import("@/components/custom/portfolio/PortfolioActivites"),
    PortfolioProjets: () => import("@/components/custom/portfolio/PortfolioProjets"),
    C2Aadherer: () =>
      import("@/components/custom/c2a/C2Aadherer"),
  },
};
</script>
