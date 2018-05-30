<template>
  <div class="login">
     <h1>登录</h1>
      <div class="name">
        <span>账号</span>
        <input type="text" placeholder="请输入账号" v-model="names">
      </div>
      <div class="name">
        <span>密码</span>
        <input type="password" placeholder="请输入密码" v-model="pas">
      </div>
      <button @click="goLogin">登录</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      names:'',
      pas:''
    }
  },
  methods:{
    goLOgin:()=>{
      if( this.names && this.pas){
        
      }
      
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
.name{
  margin: 1rem 0;
}
</style>
