<script setup>
import About from "./components/About.vue";
import Contact from "./components/Contact.vue";
import Navbar from "./components/Navbar.vue";
import Projects from "./components/Projects.vue";
import Tools from "./components/Tools.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
	<Navbar />
    <div class="container-fluid">
        <About />
        <Projects />
        <Tools />
        <Contact />
    </div>
    <Footer />
</template>
