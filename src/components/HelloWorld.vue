<template>
  <div class="hello">
    Component Hello word voi ID = {{id}}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    id: Number
  }
}
</script>
