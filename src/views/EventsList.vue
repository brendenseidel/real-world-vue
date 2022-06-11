<template>
  <div>
    <h1>Events Listing</h1>

    <EventCard />

    <BaseIcon />
  </div>
</template>

<script>
import BaseIcon from "@/components/BaseIcon.vue";
import EventCard from "@/components/EventCard.vue";
export default {
  components: { EventCard, BaseIcon },
};
</script>

<style></style>
