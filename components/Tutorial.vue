<!-- Please remove this file from your project -->
<template>
  <div class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0">
    <button @click="onClick">Click me</button>
  </div>
</template>

<script>

import { JsonServiceClient } from "@servicestack/client"


export default {
  name: 'NuxtTutorial',
  methods: {
    onClick: function() {
      console.log('hi');

      let json = new JsonServiceClient();


    }
  }

}
</script>
