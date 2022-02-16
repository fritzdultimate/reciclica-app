<template>
    <ion-content>
        <div class="flex-center">
            <ion-spinner name="crescent" color="success"></ion-spinner>
        </div>
    </ion-content>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'LoaderPage'
})
</script>

<style scoped>
    .flex-center {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
    }
</style>
