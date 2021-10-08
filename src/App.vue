<script lang="ts">
import { defineComponent } from 'vue'
import { Player, Youtube, Vimeo } from '@vime/vue-next';

export default defineComponent({
  setup() {

  },
  components: {
    Player,
    Youtube,
    Vimeo
  }
})
</script>


<template lang="pug">
Player(controls)
  Vimeo(videoId="411652396")

Player(controls)
  Youtube(videoId="DyTCOwB0DVw")

</template>

<style>
</style>
