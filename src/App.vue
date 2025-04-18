<template>
  <NavbarSection />
  <HeroSection />
  <CompaniesSection />
  <ShareSection />
  <FeedbackSection />
  <BetterFeedback />
  <ArchiveSection />
  <TestimonialsSection />
  <DesignersSection />
  <DashboardSection />
  <NewsletterSection />
  <FooterSection />
</template>

<script>
import NavbarSection from "./components/NavbarSection.vue";
import HeroSection from "./components/HeroSection.vue";
import CompaniesSection from "./components/CompaniesSection.vue";
import ShareSection from "./components/ShareSection.vue";
import FeedbackSection from "./components/FeedbackSection.vue";
import BetterFeedback from "./components/BetterFeedback.vue";
import ArchiveSection from "./components/ArchiveSection.vue";
import TestimonialsSection from "./components/TestimonialsSection.vue";
import DesignersSection from "./components/DesignersSection.vue";
import DashboardSection from "./components/DashboardSection.vue";
import NewsletterSection from "./components/NewsletterSection.vue";
import FooterSection from "./components/FooterSection.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    NavbarSection,
    HeroSection,
    CompaniesSection,
    ShareSection,
    FeedbackSection,
    BetterFeedback,
    ArchiveSection,
    TestimonialsSection,
    DesignersSection,
    DashboardSection,
    NewsletterSection,
    FooterSection,
  },
};
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: "Inter", sans-serif;
}
</style>
