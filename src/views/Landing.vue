<template>
  <div>
    <NavbarComponent />
    <main>
      <!-- Hero -->
      <HeroComponent />
      <!-- Mission Statement -->
      <MissionComponent />
      <!-- Vision Statement -->
      <VisionComponent />
      <!-- Categories -->
      <CategoriesComponent />
      <!-- Sponsors -->
      <SponsorsComponent />
      <!-- Team -->
      <TeamComponent />
      <!-- Project Levels -->
      <LevelsComponent />
      <!-- Registration Form -->
      <RegisterComponent />
    </main>
    <FooterComponent />
  </div>
</template>
<script>
import HeroComponent from "../components/Hero.vue"
import TeamComponent from "../components/Team.vue"
import LevelsComponent from "../components/Levels.vue"
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
import VisionComponent from "../components/Vision.vue";
import MissionComponent from "../components/Mission.vue";
import RegisterComponent from "../components/Register.vue"
import SponsorsComponent from "../components/Sponsors.vue"
import CategoriesComponent from "../components/Categories.vue"
export default {
  name: "landing-page",
  components: {
    HeroComponent,
    TeamComponent,
    LevelsComponent,
    NavbarComponent,
    FooterComponent,
    VisionComponent,
    MissionComponent,
    RegisterComponent,
    SponsorsComponent,
    CategoriesComponent,
  },
};
</script>
