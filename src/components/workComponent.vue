<script lang="ts" setup>
import { ref } from 'vue';

    const model = ref
</script>


<template>
    <v-container
    max-width="1200">
        <v-div 
        class="d-flex align-center justify-center">
            <h1 class="title">Work</h1>
            <v-divider 
            inset 
            :thickness="3"
            color="#4bc538" 
            opacity="0.5"></v-divider>
        </v-div>
        <div style="display: inline_block" align="center">
            <img class="mx-2" align="center" alt="Django" height="50" width="50" src="https://devicons.railway.com/i/django.svg">
            <img class="mx-2" align="center" alt="Vue" height="50" width="50" src="https://devicons.railway.com/i/vuejs.svg">
            <img class="mx-2" align="center" alt="Postgres" height="50" width="50" src="https://devicons.railway.com/i/postgresql.svg">
            <img class="mx-2" align="center" alt="Docker" height="50" width="50" src="https://devicons.railway.com/i/docker.svg">
            <img class="mx-2" align="center" alt="Python" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
            <img class="mx-2" align="center" alt="JavaScript" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
            <img class="mx-2" align="center" alt="Typescript" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg">
            <img class="mx-2" align="center" alt="C" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg">
        </div>
        <v-div>
            <v-slide-group
            v-model="model"
            class="pa-4"
            selected-class="bg-success"
            show-arrows
            >
            <v-slide-group-item
                v-for="n in 15"
                :key="n"
                v-slot="{ isSelected, toggle, selectedClass }"
            >
                <v-card
                :class="['ma-4', selectedClass]"
                color="grey-lighten-1"
                height="300"
                width="480"
                @click="toggle"
                >
                <div class="d-flex fill-height align-center justify-center">
                    <v-scale-transition>
                    <v-icon
                        v-if="isSelected"
                        color="white"
                        icon="mdi-close-circle-outline"
                        size="48"
                    ></v-icon>
                    </v-scale-transition>
                </div>
                </v-card>
            </v-slide-group-item>
            </v-slide-group>
        </v-div>
    </v-container>
</template>

<style scoped>

</style>