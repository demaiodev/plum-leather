<template>
  <div class="main" id="page-top">
    <Navbar />
    <Masthead />
    <Services />
    <Portfolio />
    <About />
    <Team />
    <Clients />
    <Contact />
    <Footer />
    <Modal />
  </div>
</template>
<script>
import Navbar from "@/components/Navbar";
import Masthead from "@/components/Masthead";
import Services from "@/components/Services";
import Portfolio from "@/components/Portfolio";
import About from "@/components/About";
import Team from "@/components/Team";
import Clients from "@/components/Clients";
import Contact from "@/components/Contact";
import Footer from "@/components/Footer";
import Modal from "@/components/Modal";
export default {
  name: "Main",
  components: {
    Navbar,
    Masthead,
    Services,
    Portfolio,
    About,
    Team,
    Clients,
    Contact,
    Footer
  }
};
</script>