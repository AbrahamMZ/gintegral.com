<template>
  <div>
    <hero />
    <banner />
    <features />
    <teasers />
    <!-- <prices /> -->
    <call-to-action />
  </div>
</template>

<script>
import "sweetalert2/dist/sweetalert2.min.css";
import Hero from "@/components/Hero";
import Features from "@/components/Features";
import Teasers from "@/components/Teasers";
import CallToAction from "@/components/CallToAction";
import Banner from "@/components/Banner";
import logo from "~/assets/img/logo_makenzie.png";
// let logo = require("~assets/img/logo.svg");
export default {
  name: "LandingPage",
  components: {
    hero: Hero,
    features: Features,
    teasers: Teasers,
    banner: Banner,
    // prices: Prices,
    "call-to-action": CallToAction,
  },
  mounted() {
    // this.$swal.fire({
    //   title: "Nos entusiasma anunciar!!",
    //   html:
    //     "A partir del 01 de junio 2021 celebraremos una fusión estratégica y comercial con <b> Makenzie S.A. de C.V </b> comprometiéndonos en brindarles una gran calidad y satisfacción de servicio además de una amplia gama de oportunidades para tu negocio.",
    //   imageUrl: logo,
    //   imageAlt: "makenzie_alt",
    //   width: 600,
    // });
  },
};
</script>
