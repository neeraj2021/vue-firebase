<template>
  <div>
    <h1>Today Date using new Date = {{ date }}</h1>
    <h1>Today Date using moment = {{ momentDate }}</h1>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
// import moment from "moment";

export default Vue.extend({
  name: "IndexPage",
  data() {
    return {
      date: new Date(),
      momentDate: moment.weekdays(),
    };
  },
});
</script>
