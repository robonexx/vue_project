<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Learning as I go!</template>
    So Im learning Vue now, I've been working in REACT for about 1 year and did my Exam project at the Frontend education in NEXT.JS.
    I've learned a lot and now I'm trying this to have an overview of how it works. 
    I don't have 5 year experience but I have dedication and passion for what i do, if it be <span class='alt-text'>CODING</span> check my <a target="_blank" href="https://github.com/robonexx/">Github</a> or <span class='alt-text'>DANCING</span> <a target="_blank" href="https://https://youtu.be/LZp0HoFXgsA?t=13/">Watch</a> me get down. 
  </WelcomeItem>

</template>
