<script setup>
import GuestLayout from "@/Layouts/GuestLayout.vue";
import InputLabel from "@/Components/InputLabel.vue";
import TextInput from "@/Components/TextInput.vue";
import { ref } from "vue";

const input = ref("初期値が入る");
</script>
<template>
    <GuestLayout>
        <InputLabel value="件名" />
        <TextInput v-model="input" class="w-full" />
    </GuestLayout>
</template>
