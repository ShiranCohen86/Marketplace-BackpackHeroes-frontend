<template>
  <div id="app">
    <app-header />
    <router-view class="app-container "/>
    <app-footer />
  </div>
</template>
<script>
import appHeader from "./cmps/app-header";
import appFooter from "./cmps/app-footer";

export default {
  components: {
    appHeader,
    appFooter,
  },
};
</script>

