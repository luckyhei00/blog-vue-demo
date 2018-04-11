<template>
  <div id="app">
    <el-row :gutter="24">
      <el-aside id="nav">
        <app-nav></app-nav>
      </el-aside>
    </el-row>
    
  </div>
</template>

<script>
import Nav from './components/Nav'
export default {
  name: 'App',
  components:{
    "app-nav": Nav
  }
}
</script>



<style>
*{
  margin: 0;
  padding: 0;
}
em,i{
  font-style: normal;
}
li{
  list-style: none;
}
img{
  border: 0;
  vertical-align: middle;
}
button{
  cursor: pointer;
}
a{
  color: #666;
  text-decoration: none;
}
a:hover{
  color: #c81623;
}

body{
  background: url('./assets/blog_bj.jpg') no-repeat;
  height: 100%;
}
#nav{
  width:20%!important;
  margin-top:50px;
  margin-left:100px;
  height: 860px;
  background:rgba(240,240,130,0.8);
  border-radius: 10px;
}
</style>

