<template>
  <div class="hello">
    <h1>我是Registered</h1>
    <button @click="back">点我返回</button>
  </div>
</template>

<script>
export default {
  name: 'Registered',
  data () {
    return {
    }
  },

  methods:{
  	back(){
  		this.$router.push('/')
  	}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
