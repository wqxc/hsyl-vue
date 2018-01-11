<template>
  <div class="case">
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple-dark">
        <img  v-bind:src='caseUrl'   alt="" class="img-responsive">
      </div></el-col>
    </el-row>
    <div class="section-2">
      <h3>上海站项目</h3>
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='jianjieUrl'  alt="">
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目简介:</span></h3>
          <p class="sp">
            上海站位于上海市静安区秣陵路303号，是上海市乃至全国最为重要的火车站，每天接待大量来自全国各地的旅客。</p>
        </div></el-col>
      </el-row>
    </div>
    <div class="section-2">
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目定位:</span></h3>
          <p class="sp">以文化中国的理念与人文自然为主旨，匠心造就，以精益求精的工匠精神，筑就中国式火车站绿化典范。</p>
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='dingweiUrl'  alt="">
        </div></el-col>
      </el-row>
    </div>
    <div class="section-2">
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='teseUrl'  alt="">
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目特色:</span></h3>
          <p class="sp">绿植与花团锦簇寓意祖国欣欣向荣，将绿色与现代交通完美融合。构筑效果磅礴大气而又贴合自然。为匆匆而行的旅客心头添一抹绿色，也添一些清新。</p>
        </div></el-col>
      </el-row>
    </div>
    <!--别墅项目  -->
    <div class="section-2">
      <h3>政立路别墅项目</h3>
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='bieshu1url'  alt="">
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目简介:</span></h3>
          <p class="sp">
            政立路别墅是由上海中球实业有限公司开发。该项目坐拥百亩天然湿地公园，地处城市副中心的核心优越位置！整体设计风格为新中式纯墅社区</p>
        </div></el-col>
      </el-row>
    </div>
    <div class="section-2">
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目定位:</span></h3>
          <p class="sp">致力于打造上海市高端人文名仕尊邸。整体设计风格更彰显天人合一理念，园林设计与别墅群整体的风格相呼应，于闹中更显安静。</p>
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='bieshu2url'  alt="">
        </div></el-col>
      </el-row>
    </div>
    <div class="section-2">
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='bieshu3url'  alt="">
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目特色:</span></h3>
          <p class="sp">将中国传统的园林建筑规范与现代科技结合，北承西山皇家气象，南荟江南园林风情，溯源院子系坊巷规制。清新自然幽静。</p>
        </div></el-col>
      </el-row>
    </div>

    <!--其他什么项目  -->
    <div class="section-2">
      <h3>越虹广场企业园项目</h3>
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='xiezilou1Url'  alt="">
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目简介:</span></h3>
          <p class="sp">
            上海H88越虹广场位于徐汇区虹漕路（漕河泾开发区核心区域），由国际知名建筑机构阿特金斯进行规划设计，率先引入Office Park（商务花园）概念，意图打造一个融合 “办公/创意/休闲配套” 三大功能的综合性创意园。</p>
        </div></el-col>
      </el-row>
    </div>
    <div class="section-2">
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目定位:</span></h3>
          <p class="sp">致力于打造上海市高端写字楼，力求科技与自然的融合。在水泥森林之中种植绿色。为都市白领的单调生活增添绿色。简单自然大方是本次项目的立意所在。</p>
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='xiezilou2Url'  alt="">
        </div></el-col>
      </el-row>
    </div>
    <div class="section-2">
      <el-row class="sss">
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple">
          <img  v-bind:src='xiezilou3Url'  alt="">
        </div></el-col>
        <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12"><div class="grid-content bg-purple-light">
          <h3><span>项目特色:</span></h3>
          <p class="sp">在两栋主体写字楼间构架独立空中花园。绿植采用垂钓为主，都市与原野的一次完美结合。春天花开浓郁，夏天绿荫庇人，更显人文关怀之意。</p>
        </div></el-col>
      </el-row>
    </div>
  </div>


</template>

<script>
  export default{
    name: 'outVue',
    data () {
      return {
        caseUrl: '../../static/case.jpg',
        jianjieUrl: '../static/shanghaizhan0.jpg',
        dingweiUrl: '../static/shanghaizhan1.jpg',
        teseUrl: '../static/shanghaizhan2.jpg',
        bieshu1url: '../static/bieshu1.jpg',
        bieshu2url: '../static/bieshu2.jpg',
        bieshu3url: '../static/bieshu3.jpg',
        xiezilou1Url: '../static/xiezilou1.jpg',
        xiezilou2Url: '../static/xiezilou2.jpg',
        xiezilou3Url: '../static/xiezilou3.jpg'
      }
    }
  }
</script>
<style lang="scss">
.img-responsive {
  display: inline-block;
  height: auto;
  max-width: 100%;
  }
  .case{
    .section-2{
      h3{
        height: 100px;
        text-align: center;
        line-height: 100px;
        color: green;
      }
      .el-row{
        width: 90%;
        margin-left: 5%;
        border-top: 1px dashed #ccc;
        border-bottom: 1px dashed #ccc;
        p{
          // margin-top: 20px;
        }
        img{
          margin-top: 50px;
        }
        .el-col:first-child{
          text-align: center;
        }
        .el-col{
          // border: 1px solid #ccc;
          text-align: left;
          line-height: 180%;
          height: 300px;
          color: #999;
          // img{
          //   height: 300px;
          // }
          .bg-purple-light{
            padding: 20px 80px;
          }
          p {
              span{
                font-weight: bold;
                color: black;
            }
          }
        .el-button{
              border: 1px solid red;
              float: right;
              bottom: 0px;
              // margin-top: 15%;
              // margin-top:-150px;

            }
          }
      }

    }
  }
</style>
