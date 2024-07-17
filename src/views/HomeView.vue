<script setup>
  import Header from "@/components/Header.vue";
  import Footer from "@/components/Footer.vue";
  import Intro from "@/components/Intro.vue";
  import Skill from "@/components/Skill.vue";
  import Site from "@/components/Site.vue";
  import Port from "@/components/Port.vue";
  import Contact from "@/components/Contact.vue";
  import Skip from "@/components/Skip.vue";
</script>

<template>
  <Skip />
  <Header />
  <main id="main" rol="main">
    <Intro />
    <Skill />
    <Site />
    <Port />
    <Contact />
  </main>
  <Footer />
</template>
