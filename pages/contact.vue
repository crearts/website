<template>
  <div>
    <Localisation />
    <Contact />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "GEM Les Crearts | Contact et localisation",
      meta: [
        {
          hid: "Contact et localisation",
          name: "GEM Les Crearts",
          content: "Next Ui Kit is the best way",
        },
      ],
    };
  },

  data() {
    return {};
  },
  components: {
    Contact: () => import("@/components/custom/contact/Contact"),
    Localisation: () => import("@/components/custom/features/Localisation"),
  },
};
</script>