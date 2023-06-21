<script>
import { computed, ref } from 'vue'
export default {
  setup() { 
    const player = ref('X')
    const squares = ref([
      ['', '', ''],
      ['', '', ''],
      ['', '', ''],
    ])
  }
}
</script>

<template>
  <div class="container">
  </div>
</template>
<style scoped> 
.square {
  background: #fff;
  border: 1px solid #999;
  float: left;
  font-size: 70px;
  font-weight: bold;
  line-height: 34px;
  height: 100px;
  margin-right: -1px;
  margin-top: -1px;
  padding: 0;
  text-align: center;
  width: 100px;
}
</style>