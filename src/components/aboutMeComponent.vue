<template>
    <v-container
    max-width="1200">
        <v-div 
        class="d-flex align-center justify-center">
            <h1 class="title">About</h1>
            <v-divider 
            inset 
            :thickness="3"
            color="#4bc538" 
            opacity="0.5"></v-divider>
        </v-div>
        <p 
        class="paragraph text-h6">
            I’m a Full Stack Developer currently finishing my Control and Automation Engineering degree at the Federal University of Santa Catarina (UFSC). 
            I stated my career as a software developer in 2024, as an intern remotly to a startup, where I worked on projects using technologies like Django, DJango Rest Framework, Vue.js and PostgreSQL. 
            When I’m not coding, I enjoy skateboarding, which helps me stay creative and focused. 
            I’m always looking for ways to build practical, impactful solutions to make work easier and more efficient.
        </p>

        <h1 class="mt-5 text-h4 paragraph" >I have professional experience with these technologies:</h1>
        <v-div class="d-flex align-start justify-space-around my-5">
            <div>
                <h1>Back-End</h1>
                <li>Django</li>
                <li>Django Rest Framework</li>
                <li>FastAPI</li>
            </div>
            <div>
                <h1>Front-End</h1>
                <li>TypeScript</li>
                <li>Vue</li>
                <li>Next</li>
            </div>
            <div>
                <h1>Database</h1>
                <li>PostgreSQL</li>
            </div>
            <div>
                <h1>Tools</h1>
                <li>Git</li>
                <li>Linux</li>
                <li>Docker</li>
            </div>
        </v-div>
    </v-container>
</template>

<style>

</style>