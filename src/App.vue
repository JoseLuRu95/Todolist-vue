<template>
   <div id="app">
      <Header />
      <b-container>
         <router-view />
      </b-container>
   </div>
</template>

<script>
import Header from "./components/Lay-out/Header";
export default {
   name: "app",
   components: {
      Header
   }
};
</script>

<style></style>
