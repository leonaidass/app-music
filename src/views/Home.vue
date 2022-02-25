<template>
<v-app id="inspire" :style="{background: $vuetify.theme.themes.dark.background}">
  <Sidebar/>

</v-app>
</template>

<script>
  import Sidebar from "../components/Sidebar.vue"
  export default {
    name: 'Home',

    components: {
      Sidebar
    },
  }
</script>
