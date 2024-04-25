<template>
  <div class="text-white">
    <ul>
      <li v-for="(food, i) in foodItems" :key="i">
        {{ food }}
      </li>
    </ul>
  </div>
</template>

<script lang="ts" setup>
const foodItems = ["Pasta", "Pizza", "Potatoes"];
</script>
