<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
    <div class="greetings">
      <h1 class="text">{{ msg }}</h1>
    </div>
</template>