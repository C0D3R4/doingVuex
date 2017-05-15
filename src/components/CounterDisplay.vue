<template>
  <div>
    Count is {{ count }}
  </div>
</template>

<script>
import store from '../store'

export default {
  computed: {
    counter() {
      return store.state.counter
    }
  }
}
</script>
<style>
</style>
