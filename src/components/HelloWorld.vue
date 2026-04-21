<script setup>
import { ref, computed } from "vue"

const name = ref("Alan")
const type = name.value.type
</script>

<template>
  <p>{{ type }}</p>
</template>
