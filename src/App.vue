<script setup>
import PageTitle from './components/PageTitle.vue'
import ProjectCard from './components/ProjectCard.vue'
</script>

<template>
  <div id="content">
    <PageTitle />
    <ProjectCard />
  </div>
</template>

<style scoped>
#content {
  max-width: 1280px;
  padding: 2rem;
}
</style>
