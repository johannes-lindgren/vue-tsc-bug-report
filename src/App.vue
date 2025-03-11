<script lang="ts">
const a: string = 1

export default {
  data() {
    return {
      class: 'vue',
    }
  },
}

</script>

<template>
  <div :class="class" >
  </div>
</template>
