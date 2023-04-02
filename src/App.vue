<script setup>
import Todo from "./components/Todo.vue";
</script>

<template>
  <div class="bg-gray-600 text-white w-1/2 m-auto mt-3">
    <div class="text-center border-2 border-black py-4">
      <h1 class="text-3xl py-4">To Do App</h1>
      <p class="text-xl">To complete:</p>
      <div class="flex justify-between py-2">
        <input type="text" class="py-2 w-5/6" />
        <button class="py-2 w-1/6 bg-blue-500">Add</button>
      </div>
    </div>
    <Todo />
    <Todo />
    <Todo />
  </div>
</template>
