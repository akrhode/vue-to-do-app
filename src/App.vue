<script setup>
import Todo from "./components/Todo.vue";
</script>

<template>
  <div class="bg-gray-600 text-white w-1/2 m-auto mt-3">
    <div class="text-center border-b-2 border-black py-4">
      <h1 class="text-3xl py-4">To Do App</h1>
      <p class="text-xl">To complete:</p>
    </div>
    <Todo />
    <Todo />
    <Todo />
  </div>
</template>
