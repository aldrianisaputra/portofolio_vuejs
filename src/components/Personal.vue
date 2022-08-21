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
      <h3 class="text1">  
        Mark lee
      </h3>
      
      
    </div>
</template>