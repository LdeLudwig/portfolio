<script setup lang="ts">

</script>

<template>
    <v-container>
        <v-div 
        class="d-flex align-center justify-center">
            <p class="title">About</p>
            <v-divider 
            inset 
            :thickness="3"
            color="#4bc538" 
            opacity="0.5"></v-divider>
        </v-div>
        <p 
        class="paragraph text-h6">
            I’m a Full Stack Developer currently finishing my Control and Automation Engineering degree at the Federal University of Santa Catarina (UFSC). 
            I’m passionate about using AI to create automation solutions that improve productivity and streamline workflows. 
            When I’m not coding, I enjoy skateboarding, which helps me stay creative and focused. 
            I’m always looking for ways to build practical, impactful solutions to make work easier and more efficient.
        </p>
        <v-div>
            
        </v-div>
    </v-container>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
.title{
    font-family: "Roboto", serif;
    font-size: 80px;
    font-weight: 800;
    color: #4bc538;
}

.paragraph{
    font-family: "Roboto", serif;
    font-weight: 600;
    color: white
}

</style>