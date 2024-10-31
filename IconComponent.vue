<template>
    <ion-icon :name="iconName" :color="color" :size="size"></ion-icon>
  </template>
  
  <script>
  export default {
    name: 'IconComponent',
    props: {
      iconName: { type: String, default: 'star' },
      color: { type: String, default: 'primary' },
      size: { type: String, default: 'large' }
    }
  }
  </script>
  
  <style scoped>
  ion-icon {
    margin: 5px;
  }
  </style>
  