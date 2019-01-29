<template>
  <div class="hello">
    <h1>密码登录</h1>
    <input placeholder="请输入用户名" type="text" name="userName"/>
    <br><br>
    <input placeholder="请输入密码" type="text" name="passWord"/>
    <br><br>
    <input type="submit" value="登录" />
    <button @click="go">点我跳转</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      msg1: 'hello my app'
    }
  },

  methods:{
  	go(){
  		this.$router.push('/Registered')
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
