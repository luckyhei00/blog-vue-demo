<template>
  <div class="container">
    <header>
      <a href="#"><i class="el-icon-star-off">注册</i></a>
      <a href="#"><i class="el-icon-star-on">登录</i></a>
    </header>
    <div>
      <ul>
        <li class="mainNav">
          <a href="#">技术类文章</a>
        </li>
        <li><a href="#">html</a></li>
        <li><a href="#">css</a></li>
        <li><a href="#">javascript</a></li>
        <li><a href="#">vue</a></li>
        <li><a href="#">react</a></li>
        <li><a href="#">angular</a></li>
        <li><a href="#">outher</a></li>
        <li class="mainNav">
          <a href="#">文学类文章</a>
        </li>
        <li><a href="#">散文</a></li>
        <li><a href="#">诗歌</a></li>
        <li><a href="#">小说</a></li>
        <li><a href="#">其他</a></li>
        <li class="mainNav">
          <a href="#">交友类文章</a>
        </li>
        <li><a href="#">天下美食</a></li>
        <li><a href="#">小家大爱</a></li>
        <li><a href="#">人生故事</a></li>
        <li><a href="#">旅途风貌</a></li>
        <li><a href="#">鸡毛蒜皮</a></li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.container{
  padding: 20px;
}
header{
  height: 30px;
  font: 16px/30px "微软雅黑";
  margin-bottom: 20px;
}
header a{
  float: right;
  margin: 0 10px;
  display: block;
  border: 1px solid #666;
  padding: 0 5px;
  border-radius: 4px;
}
ul{
  padding: 0 10px;
}
ul li{
  height: 30px;
  margin-bottom: 8px;
  background: rgba(240,240,200,0.7);
  font: 14px/30px "微软雅黑";
  text-indent: 3em;
  font-style: italic;
  border-radius: 6px;
  cursor: pointer;
}
ul li a{
  transition: 0.5s;
}
.mainNav{
  height: 40px;
  margin-bottom: 10px;
  background: none;
  font: 18px/40px "微软雅黑";
  text-indent: 2em;
  font-style: italic;
  border-bottom: 2px solid #666;
}
li:hover a{
  margin-left: 50px;
  transition: 0.5s;
  color: #c81623;
}
</style>

 

