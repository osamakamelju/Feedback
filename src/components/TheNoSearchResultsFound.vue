<script setup>
import Button from './buttons/Button.vue';
</script>
<template>
    <div class="flex justify-center items-center flex-col p-8" >
        <img src="@/assets/suggestions/illustration-empty.svg" />
        <h3 class="font-bold text-lg lg:m-4">Det finns ingen feedback ännu.</h3>
        <p class="mb-4 max-w-lg text-center">Har du ett förslag? Hittade du en bugg som måste klämmas? Vi älskar att höra om nya idéer för att förbättra vår app. </p>
        <Button msg="+ Add Feedback" />
    </div>
</template>