<template>
  <div id="app">
    <Title />
    <router-view></router-view>

  </div>
</template>


<script>
import Title from './components/Home/Title'

export default {
  name: "app",
  components: {
    Title,
  }
}
</script>
