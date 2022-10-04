<script setup lang="ts"></script>

<template>
  <div class="flex">
    <div class="h-32 w-32 bg-red-400 sm:flex-square">R</div>
    <div>
      <div class="h-16 w-64 bg-green-400 md:flex-square">G</div>
      <div class="h-16 w-64 bg-blue-400 lg:flex-square">B</div>
    </div>
  </div>
  <div className="flex h-16 justify-center items-center">
    <div className="group text-xl">
      <strong className="group-hover:text-red-500">Hover on me </strong>
      <strong className="group-hover:text-green-500">the texts will be </strong>
      <strong className="group-hover:text-blue-500">of different colors</strong>
    </div>
  </div>
  <div
    class="h-16 w-16 m-8 animate-bounce md:animate-pulse rounded-full bg-gray-200"
  ></div>
</template>

<style scoped></style>
