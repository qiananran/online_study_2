<template>
  <v-footer>
    <div class="decorate">
      <div class="wavefooter-wrapper"></div>
      <div style="width: 100%; height: 400px; background-color: #181819;">
       <v-container>
         <v-row class="justify-center align-center" style="color: #BABABA">
           <v-col cols="3">
             <h3>Online Study</h3>
             <div style="margin-top: 20px;">
               <span style="width: 20px"></span>
             </div>
           </v-col>
           <v-col cols="3" >
             <h3 style="text-align: center">产品</h3>
             <div style="margin-top: 10px; display: flex; flex-direction: column; text-align: center">
               <a href="#" class="color">产品更新日志</a>
               <a  href="#" class="color">使用手册</a>
               <a href="#" class="color">快速上手</a>
               <a href="#" class="color">私有云部署</a>
             </div>
           </v-col>
           <v-col cols="3">
             <h3 style="text-align: center">关于</h3>
             <div style="margin-top: 10px; display: flex; flex-direction: column; text-align: center">
               <a href="#" class="color">FAQ</a>
               <a  href="#" class="color">联系我们</a>
               <a href="#" class="color">建议反馈</a>
               <a href="#" class="color">加入我们</a>
             </div>
           </v-col>
           <v-col cols="3">
             <h3 style="text-align: center">资源</h3>
             <div style="margin-top: 10px; display: flex; flex-direction: column; text-align: center">
               <a href="#" class="color">文档工具</a>
               <a  href="#" class="color">文档管理工具</a>
               <a href="#" class="color">自动化测试工具</a>
               <a href="#" class="color">Mock工具</a>
             </div>
           </v-col>
         </v-row>
       </v-container>
        <br>
        <div class="footer-line"></div>
        <div style="margin-top: 50px">
          <v-row class="justify-center align-center" style="color: #BABABA">
            <v-col style="text-align: center" cols="12">
              友情链接：Dooring·H5制作神器
              Authing
              CODE.FUN
              Tapdata Cloud
              ShowMeBug
              uView
              电鸭社区
              敏捷开发社区
            </v-col>
            <v-col style="text-align: center; margin-top: 20px" cols="12">
              ©2021
              Apifox
              All Rights Reserved
              九江学院
              粤ICP备2021010720号
            </v-col>
          </v-row>
        </div>
      </div>
    </div>
  </v-footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
.color{
    color: #BABABA;
     clear: none;
  text-decoration: none;
  color: #BABABA;
  margin-top: 10px;
}

footer{
  padding: 0;
  background-color: white;
}
.col{
  padding: 0;
}
.decorate{
  width: 100%;
}
.decorate::selection{
  background-color: #f85250;
}
.wavefooter-wrapper {
  height: 120px;
  background: url(https://cdn.apifox.cn/www/assets/image/index/hero-hub-tail.png) no-repeat;
  background-size: cover;
}
.footer-line{
  margin: 0 auto;
  max-width: 1224px;
  height: 1px;
  background: hsla(0,0%,100%,.32);
  margin-top: 20px;
}

</style>