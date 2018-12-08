<template>
 <div class="two" :style="{backgroundColor:beijing}">第二个路由
     <br>
   <button @click="bianse">点我变色</button>
 </div>
</template>

<script>
export default {
  name: 'two',
  data () {
    return {
        beijing:"green"
        // msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{
    bianse(){
     this.beijing='yellow'
    }

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

