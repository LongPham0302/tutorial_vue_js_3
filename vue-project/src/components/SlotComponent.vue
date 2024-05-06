<template>
    <div>
      <slot></slot>
      <slot name="details"></slot>
      
    </div>
  </template>
  
  <script setup>
import { useSlots } from 'vue';
const slots = useSlots();

  </script>
  