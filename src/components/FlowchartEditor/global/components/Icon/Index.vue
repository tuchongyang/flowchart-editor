/**
*
* Icon
*/

<style scoped lang="scss">
  .icon {

  }
</style>

<template>
  <span v-if="type" class="icon iconfont" :class="[type ? 'icon-' + type : '']"></span>
</template>

<script>
  export default {
    name: 'Icon',
    props: {
      type: String
    }
  }
</script>
