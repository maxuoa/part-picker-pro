<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title>Part Picker Pro</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <v-container fluid>
        <p>Default layout loaded</p>
        <nuxt />
      </v-container>
    </v-main>

    <v-footer app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
}
</script>