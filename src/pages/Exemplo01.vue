<template>
    <div>
      <p>{{ `Ola ${name} sua idade é ${age}`}}</p>
      <p>{{ n1 + n2 }}</p>
    </div>
  </template>
  
  <script setup>
  
    let name = 'Icaro'
    let age = 25
  
    let n1 = 20 
    let n2 = 5
  
  </script>
  
  <style lang="scss" scoped>
  
  </style>