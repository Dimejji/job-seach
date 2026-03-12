<script setup>
import HeroView from '../components/HeroView.vue';
import HomeCards from '../components/Homecards.vue';
import JobsListings from '../components/JobsListings.vue';
</script>


<template>
    <HeroView />
  <HomeCards />
  <JobsListings :limit="3" :show-button=true />
</template>