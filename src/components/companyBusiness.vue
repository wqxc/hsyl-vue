<template>
  <div class="bussiness">
    <el-row>
    <el-col :span="24"><div class="grid-content bg-purple-dark">
      <img  v-bind:src='bussinessUrl'  alt="" class="img-responsive">
    </div></el-col>
  </el-row>
  <el-row class="bussRange">
    <el-col :span="24" >
        <h3>公司业务范围</h3>
    </el-col>
  </el-row>
  <el-row class="bussList">
    <el-col :span="8"   v-for="item in bussList">
      <el-card :body-style="{ 'text-align':'center' }">
        <img  v-bind:src='item.url'  class="image" >
        <div style="padding: 14px;">
          <span>{{item.name}}</span>
        </div>
      </el-card>
    </el-col>
  </el-row>
  <el-row class="plant">
    <el-col :span="24" >
        <h3>经营植物概览</h3>
    </el-col>
  </el-row>
  <el-row class="plantList">
    <el-col :span="8"   v-for="item in plantList" >
      <el-card :body-style="{ 'text-align':'center' }">
        <img  v-bind:src='item.url'  class="image" >
        <div style="padding: 14px;">
          <span>{{item.name}}</span>
        </div>
      </el-card>
    </el-col>
  </el-row>
  </div>
</template>

<script>
  export default{
    name: 'outVue',
    data () {
      return {
        bussinessUrl: '../../static/bussiness.jpg',
        bussList: [{url: '../../static/public/bieshu.jpg', name: '别墅造型'},
        {url: '../../static/public/wenxinxiaowu.jpg', name: '温馨小屋'},
        {url: '../../static/public/fangguyuanlin.jpg', name: '仿古园林'},
        {url: '../../static/public/jiaotong.jpg', name: '交通绿化'},
        {url: '../../static/public/shangchang1.jpg', name: '商场美化'},
        {url: '../../static/public/xiezilou.jpg', name: '写字楼植物租赁'},
        {url: '../../static/public/shangchang.jpg', name: '卖场装扮'},
        {url: '../../static/public/youyuan.jpg', name: '游乐园装点'},
        {url: '../../static/public/huichang.jpg', name: '会场装饰'}],
        plantList: [
          {url: '../../static/plant/xingfushu.jpg', name: '幸福树'},
          {url: '../../static/plant/sanweikui.jpg', name: '散尾葵'},
          {url: '../../static/plant/wangxingrongshu.jpg', name: '网形榕树'},
          {url: '../../static/plant/baximu.jpg', name: '巴西木'},
          {url: '../../static/plant/dishuiguanyin.jpg', name: '滴水观音'},
          {url: '../../static/plant/jiejiegaoshu.jpg', name: '节节高树'},
          {url: '../../static/plant/junzilan.jpg', name: '君子兰'},
          {url: '../../static/plant/tieshu.jpg', name: '大铁树'},
          {url: '../../static/plant/zhaocaishu.png', name: '招财树'},
          {url: '../../static/plant/zongzhu.jpg', name: '棕竹'},
          {url: '../../static/plant/yipinhong.jpeg', name: '一品红'},
          {url: '../../static/plant/longbo.jpeg', name: '龙柏'}
        ]

      }
    }
  }
</script>
<style lang="scss">
.bussiness{
  .img-responsive {
    display: inline-block;
    height: auto;
    max-width: 100%;
    }
    .bussRange{
      height: 60px;
      line-height: 60px;
      h3{
        text-align: center;
        color: green;
      }
    }
    .bussList{
      .el-col{
        padding: 10px;
      }
    }
    .plant{
      height: 60px;
      line-height: 60px;
      h3{
        text-align: center;
        color: green;
      }
    }
    .plantList{
      .el-col{
        padding: 10px;
      }
    }
}

</style>
