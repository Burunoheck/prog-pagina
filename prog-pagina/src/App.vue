<template>
  <v-app>
    <v-app-bar 
    app
    class="app"
    opacity
    elevation="3">
  </v-app-bar>
  <v-main id="pagi">
    <v-container
    class="fill-height"
    fluid
    style="min-height: 434px"
  >
    <v-fade-transition mode="out-in">
      <v-row>
        <v-col cols="6"  justify="center">
          <v-card class="ml-15">
            <v-img
              id="img"
              src="https://picsum.photos/350/165?random"
              contain
            ></v-img>
          </v-card>
          <v-card>
            alalal
          </v-card>
        </v-col>
      </v-row>
    </v-fade-transition>
  </v-container>
  </v-main>
</v-app>
</template>

<script>
export default {
}
</script>

<style>
.app {
  opacity: 0.5;
  background: linear-gradient(90deg, hsla(254, 68%, 9%, 1) 0%, hsla(269, 97%, 37%, 1) 33%, hsla(320, 80%, 55%, 1) 66%, hsla(316, 100%, 50%, 1) 100%);
}
#pagi {
  background: linear-gradient(90deg, hsla(217, 100%, 50%, 1) 0%, hsla(186, 100%, 69%, 1) 100%)
}
#img {
  border-radius: 50%;
}
</style>