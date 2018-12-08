<template>
 <div class="one" :style="{backgroundColor:beijing}">第一个路由
   <br>
   <button @click="bianse">点我变色</button>
   <router-link to="/one1">去往one1</router-link>
 </div>
</template>

<script>
export default {
  name: 'one',
  data () {
    return {
      beijing:"red",
      // msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{
    bianse(){
     this.beijing='pink'
    }

  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

