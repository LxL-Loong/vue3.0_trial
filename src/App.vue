<template>
  <div>
    初步学习{{title}}
  </div>
</template>
<script>
// export default {
//     steup () {
//       title: 'vue3.0'
//     }
//   }

import { defineComponent } from 'vue'
export default defineComponent({
  setup () {
    return {
      title: 'vue3.0'
    }
  }
})
</script>
<style scope>
div {
  width: 100px;
  height: 100px;
  background: #ccc;
  color: skyblue;
  margin: 20px;
  text-align: center;
}
</style>