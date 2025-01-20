<script setup>
    import Hero from '@/components/Hero.vue';
  import HomeCards from '@/components/Homecards.vue';
  import JobListings from '@/components/JobListings.vue';
</script>

<template>
  <Hero subtitle="Created by Stano"/>
  <HomeCards />
  <JobListings :limit="3" :show-button="true"/>
</template>