<template>
  <div id="app">
    <Navigation/>
    <Masthead/>
    <About/>
    <Requirements/>
    <Label/>
    <Newsletter/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Masthead from "@/components/Masthead";
import About from "@/components/About";
import Requirements from "@/components/Requirements";
import Label from "@/components/Label";
import Newsletter from "@/components/Newsletter";
import Contact from "@/components/Contact";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Navigation,
    Masthead,
    About,
    Requirements,
    Label,
    Newsletter,
    Contact,
    Footer
  }
}
</script>

<style>
@import './assets/css/styles.css';
</style>

