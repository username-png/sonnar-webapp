<template>
  <div class="home">
    <Hero />
    <Overview />
    <Features />
    <Marketplace />
    <Contact />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue";
import Overview from "@/components/Overview.vue";
import Features from "@/components/Features.vue";
import Marketplace from "@/components/Marketplace.vue";
import Contact from "@/components/Contact.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Hero,
    Overview,
    Features,
    Marketplace,
    Contact,
    Footer
  }
};
</script>
