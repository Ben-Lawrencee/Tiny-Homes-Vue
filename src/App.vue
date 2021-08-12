<template>
  <div class="wrapper background">
    <mentor-card/>
    <mentor-card/>
    <mentor-card/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import MentorCard from "@/components/MentorCard.vue";

export default defineComponent({
  name: 'App',
  components: { MentorCard },
  data() {
    return {
      //Global variables here
    }
  },
  methods: {
    //Global methods here
  }
});
</script>

<style>
html {
  background: #0F2E1B;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
