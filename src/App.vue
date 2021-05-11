<template>
  <router-link :to="{name: 'hello', params: {id: 1}}">Item 1</router-link><br/>
  <router-link :to="{name: 'hello', params: {id: 2}}">Item 2</router-link><br/>
  <router-link :to="{name: 'hello', params: {id: 3}}">Item 3</router-link><br/>

  <br/>

  <router-view>

  </router-view>
</template>

<script>

export default {
  name: 'App'
}
</script>
