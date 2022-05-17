<template>
  <v-app light>
    <v-app-bar
      color="white"
      fixed
      app
    >
      <MovaLogo></MovaLogo>
      <v-spacer />
      <ButtonSecondary :title="'Voltar'"></ButtonSecondary>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  
  </v-app>
</template>


<script>
import MovaLogo from "../components/MovaLogo.vue"
import ButtonSecondary from "../components/ButtonSecondary.vue";
export default {
    name: "DefaultLayout",
    data() {
        return {};
    },
    components: { MovaLogo, ButtonSecondary }
}
</script>
