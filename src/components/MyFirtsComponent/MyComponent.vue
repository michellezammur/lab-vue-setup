<template>
    <h1>Hello World</h1>
    <button @click="helloWorld"> CLICK ME! </button>

  </template>
  
  <script setup>
  import { ref } from "vue";

 
function helloWorld() {
    console.log("Hello World");
    alert("hello world");
}

helloWorld();
  
  </script>
  
  
  <style scoped>

    button {
      padding: 2rem;
      border-radius: 10%;
      margin-left: 2rem;
    }

   
  </style>