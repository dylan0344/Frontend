<template>
  <img alt="Vue logo" src="./assets/logo.png">

</template>




<script>
import  './components/header.vue'
import  './components/content.vue'
import  './components/footer.vue'

export default {
  name: 'App',
  components: {
    header
  }
}
new Vue({
  el: '#example-2',
  data: {
    show: true
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.bounce-enter-active {
  animation: bounce-in .5s;
}
.bounce-leave-active {
  animation: bounce-in .5s reverse;
}
@keyframes bounce-in {
  0% {
    transform: scale(0);
  }
  50% {
    transform: scale(1.5);
  }
  100% {
    transform: scale(1);
  }
}
</style>
