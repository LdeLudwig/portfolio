<script setup lang="ts">

</script>

<template>
    <v-container
    class="d-flex align-center justify-space-between mx-auto my-5 px-4"
    max-width="1200"
    width="100%"
    >
        <v-div>
            <p
            class="paragraph text-h3">
                Hello, I'm Lucas,
            </p>
            <h1
            class="title ">
                Full Stack Developer
            </h1>
            <!-- need add link to contact by email -->
            <a 
            href="#"
            class="paragraph text-h5 ">
                Contact Me
            </a>
        </v-div>
        <v-div>
            <img 
            style="max-width: 600px; max-height: 734px;"
            class="rounded-lg"
            src="../assets/img/perfil.jpeg" 
            alt="me">
        </v-div>
    </v-container>
</template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
.title{
    font-family: "Roboto", serif;
    font-size: 100px;
    font-weight: 800;
    color: #4bc538;
}

.paragraph{
    font-family: "Roboto", serif;
    font-weight: 600;
    color: white
}
</style>