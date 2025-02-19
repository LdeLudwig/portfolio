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