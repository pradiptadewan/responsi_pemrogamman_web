<template>

  <div>
    
    <Navbar />,
    <HeroSection />,
    <AboutSection />,
    <ProjectsSection />,
    <ContactSection />,
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';

export default {
  components: {
    HeroSection,
    AboutSection,
    ProjectsSection,
    ContactSection,

  }
}
</script>./Index.vue
