<template>
  <div>
    <h1>Game Projects</h1>

    <div style="margin-bottom: 30px;">
      The following are some projects I've made or heavily contributed to.
    </div>

    <ProjectsList v-bind:projects="projects" />

    <div style="margin-top: 20px;">
      <!--There is more to see on <a target="_blank" href="https://peaceminus1818.itch.io/">itch.io</a> -->
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import gameProjectsData from "@/data/GameProjectsData";

export default Vue.extend({
  name: "GameProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: gameProjectsData,
    };
  },
});
</script>
