<template>
  <div class="hello">
    <div>
    <div style="margin-bottom:50px;"></div>
      <div class="container">
        <div id="demo" class="carousel slide" data-ride="carousel">
          <!-- 指示符 -->
          <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>
          </ul>
          <!-- 轮播图片-->
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="http://static.runoob.com/images/mix/img_fjords_wide.jpg">
            </div>
            <div class="carousel-item">
              <img src="http://static.runoob.com/images/mix/img_nature_wide.jpg">
            </div>
            <div class="carousel-item">
              <img src="http://static.runoob.com/images/mix/img_mountains_wide.jpg">
            </div>
          </div>
          <!--左右切换按钮-->
          <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </a>
          <a class="carousel-control-next" href="#demo" data-slide="next">
            <span class="carousel-control-next-icon"></span>
          </a>
        </div>
      </div>
      <div style="margin-top:40px;"></div>
    <h1>{{ msg }}</h1>
    </div>
    <div style="margin-top:120px"></div>
  <!--row 1-->
<div style="">
  <blog1 style="display:inline-block"></blog1>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog2 style="display:inline-block"></blog2>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog5 style="display:inline-block"></blog5>
 <div style="display:inline-block;width:20px;height:260px;"></div>
</div>

<div style="margin-top:40px"></div>

<!--row2-->
<div style="">
  <blog style="display:inline-block"></blog>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog3 style="display:inline-block"></blog3>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog4 style="display:inline-block"></blog4>
 <div style="display:inline-block;width:20px;height:260px;"></div>
</div>


<div style="margin-top:40px"></div>

<!--row3-->
<div style="">
  <blog6 style="display:inline-block"></blog6>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog7 style="display:inline-block"></blog7>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog7 style="display:inline-block"></blog7>
 <div style="display:inline-block;width:20px;height:260px;"></div>
</div>

<div style="margin-top:120px"></div>


    <h3>Links</h3>
    <ul>
 
      <li>
        <a href="https://github.com/forever404" target="_blank">Github</a>
      </li>
      <li>
        <a href="http://ctf.ever404.com" target="_blank">CTF</a>
      </li>
      <li>
        <a href="https://home.ever404.com" target="_blank">Home</a>
      </li>
      <br>

    </ul>
  </div>
</template>

<script>
import blog from "./Blog.vue";
import blog1 from "./Blog1.vue";
import blog2 from "./Blog2.vue";
import blog3 from "./Blog3.vue";
import blog4 from "./Blog4.vue";
import blog5 from "./Blog5.vue";
import blog6 from "./Blog6.vue";
import blog7 from "./Blog7.vue";
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Hack not only for function but for fun"
    };
  },
  components:{
    blog,
    blog1,
    blog2,
    blog3,
    blog4,
    blog5,
    blog6,
    blog7
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
  font-family: 'Franklin Gothic Medium';
  color:rgb(99, 91, 111);
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
  font-size: 20px;
  color: #42b983;
}
.blog {
  display: inline-block;
}
</style>
