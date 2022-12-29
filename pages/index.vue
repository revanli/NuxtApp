<template>
  <Tutorial/>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  head() {
    return {
      title:  '单独页面 title',
      meta: [{
        hid: 'description',
        name: 'description',
        content: '单独页面Meta description'
      },
      {
          hid: 'keywords',
          name: 'keywords',
          content: '单独页面Meta keywords'
      }]
    }
  }
})
</script>
