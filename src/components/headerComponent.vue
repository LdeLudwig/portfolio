<script lang="ts" setup>

const headerItens = [
  {value: 'Home', text: "Home"},
  {value: 'Projects', text: "Work"},
  {value: 'Contact', text: "Contact"}
]

</script>

<template>
  <v-sheet
    class="d-flex align-center text-center justify-space-between mx-auto my-5 px-4"
    elevation="4"
    height="64"
    max-width="1200"
    width="100%"
    rounded="pill"
    color="#1a1717"
  >
  <v-div
  style="width: 400px"
  class="d-flex justify-start">
      <p 
      class="text-h4 name"
      >
        Ludwig.br
      </p>
    </v-div>
    <v-div 
    class="d-flex justify-space-evenly"
    style="width: 400px">
      <v-btn v-for="item in headerItens"
      class="text-h6"
      :text="item.text"
      :value=item.value
      variant="text">
      </v-btn>
    </v-div>
    <v-div
    class="d-flex justify-end"
    style="width: 400px">
      <v-btn
      class="text-h4"
      icon="mdi-github"
      value="github"
      variant="text"
      href="https://github.com/LdeLudwig"
      >
      </v-btn>
    </v-div>
  </v-sheet>
</template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Lobster&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap');

.name {
  font-family: "Lobster";
  color: #4bc538;
}
</style>
