<template>
 <div class="three" :style="{backgroundColor:beijing}">第三个路由
      <br>
   <button @click="bianse">点我变色</button>
 </div>
</template>

<script>
export default {
  name: 'three',
  data () {
    return {
        beijing:"black"
    //   msg: 'Welcome to Your Vue.js App'
    }
  },
    methods:{
    bianse(){
     this.beijing='greenyellow'
    }

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

