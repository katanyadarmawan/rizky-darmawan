<template>
  <!-- Navigation-->
  <SidebarItem />
  <!-- Page Content-->
  <div class="container-fluid p-0">
    <!-- About-->
    <AboutItem />
    <hr class="m-0" />
    <!-- Experience-->
    <ExperienceItem data-aos="fade-left"/>
    <hr class="m-0" />
    <!-- Education-->
    <EducationItem />
    <hr class="m-0" />
    <!-- Skills-->
    <SkillItem />
    <hr class="m-0" />
    <!-- Project-->
    <ProjectItem />
    <hr class="m-0" />
    <!-- Awards-->
    <AwardItem />
  </div>
</template>

<script>
import SidebarItem from "../components/Sidebar.vue";
import AboutItem from "../components/About.vue";
import ExperienceItem from "../components/Experience.vue";
import EducationItem from "../components/Education.vue";
import SkillItem from "../components/Skill.vue";
import ProjectItem from "../components/Project.vue";
import AwardItem from "../components/Award.vue";

export default {
  name: "TemplateItem",
  components: {
    SidebarItem,
    AboutItem,
    ExperienceItem,
    EducationItem,
    SkillItem,
    ProjectItem,
    AwardItem,
  },
};
</script>
