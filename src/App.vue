<script setup>
  import Profile from './components/Profile.vue'
  import LinkButton from './components/LinkButton.vue'
</script>

<template>
  <div class="w-screen h-screen bg-studio bg-cover bg-top bg-no-repeat flex flex-col justify-start items-center">
    <div class="max-w-lg w-9/12 p-12 px-0 flex flex-col align-center gap-6">
      <Profile />
      <LinkButton :linkTitle="'Portfólio'" :link="'https://meu-portfolio-delta-two.vercel.app'"><i class="ri-pencil-ruler-2-fill"></i></LinkButton>
      <LinkButton :linkTitle="'Linkedin'" :link="'https://www.linkedin.com/in/davsilvam/'"><i class="ri-linkedin-box-fill"></i></LinkButton>
      <LinkButton :linkTitle="'GitHub'" :link="'https://github.com/davsilvam'"><i class="ri-github-fill"></i></LinkButton>
      <LinkButton :linkTitle="'Instagram'" :link="'https://www.instagram.com/davsilvam_/'"><i class="ri-instagram-line"></i></LinkButton>
    </div>
  </div>
</template>