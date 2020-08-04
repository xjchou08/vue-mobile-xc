<template>
  <div class="home">
    <header class="header">
      <head-search></head-search>
    </header>
    <!-- 头部 end -->
    <div class="container">
      <div class="banner-wrap">
        <img src="../assets/baodi2@v7.15.jpg" alt="" />
      </div>
      <!-- banner end -->
      <div class="local-nav">
        <li>
          <a href="javascript:;"><span>攻略&middot;景点</span></a>
        </li>
        <li>
          <a href="javascript:;"><span>门票&middot;玩乐</span></a>
        </li>
        <li>
          <a href="javascript:;"><span>美食林</span></a>
        </li>
        <li>
          <a href="javascript:;"><span>周边游</span></a>
        </li>
        <li>
          <a href="javascript:;"><span>一日游</span></a>
        </li>
      </div>
      <!--本地导航 end -->
      <nav>
        <div class="nav-common">
          <div class="nav-item item1"><span>酒店</span></div>
          <div class="nav-item item2"><span>民宿&middot;客栈</span></div>
          <div class="nav-item item3"><span>特价&middot;爆款</span></div>
        </div>

        <div class="nav-common">
          <div class="nav-item item4"><span>机票</span></div>
          <div class="nav-item item5"><span>火车票</span></div>
          <div class="nav-item item6"><span>汽车&middot;船票</span></div>
          <div class="nav-item item7"><span>专车&middot;租车</span></div>
        </div>

        <div class="nav-common">
          <div class="nav-item item8"><span>旅游</span></div>
          <div class="nav-item item9"><span>高铁游</span></div>
          <div class="nav-item item10"><span>邮轮游</span></div>
          <div class="nav-item item11"><span>定制游</span></div>
        </div>
      </nav>
      <!--主导航 end -->
      <ul class="main-nav">
        <li>
          <a href="javascript:;"><span class="main-nav-icon1">自由行</span></a>
        </li>
        <li>
          <a href="javascript:;"
            ><span class="main-nav-icon2">WiFi电话卡</span></a
          >
        </li>
        <li>
          <a href="javascript:;"
            ><span class="main-nav-icon3">保险&middot;签证</span></a
          >
        </li>
        <li>
          <a href="javascript:;"
            ><span class="main-nav-icon4">换钞&middot;签证</span></a
          >
        </li>
        <li>
          <a href="javascript:;"
            ><span class="main-nav-icon5">当地向导</span></a
          >
        </li>
        <li>
          <a href="javascript:;"
            ><span class="main-nav-icon6">特价机票</span></a
          >
        </li>
        <li>
          <a href="javascript:;"><span class="main-nav-icon7">礼品卡</span></a>
        </li>
        <li>
          <a href="javascript:;"
            ><span class="main-nav-icon8">电卡&middot;借钱</span></a
          >
        </li>
        <li>
          <a href="javascript:;"><span class="main-nav-icon9">旅 拍</span></a>
        </li>
        <li>
          <a href="javascript:;"><span class="main-nav-icon10">更 多</span></a>
        </li>
      </ul>
      <!-- 自由行 end -->
      <div class="hotAdvise">
        <h2></h2>
        <i class="advise"></i>
        <a href="javascript:;"><span>获取更多福利</span></a>
      </div>
      <!-- 热门活动 end-->
      <div class="row-adv">
        <div></div>
        <div></div>
      </div>
      <!-- 广告 end -->
      <footer class="footer">
        <div class="loadApp">
          <a href="javascript:;"
            ><i class="iconfont">&#xe60f;</i><span>电话预订</span></a
          >
          <a href="javascript:;"
            ><i class="iconfont">&#xe608;</i><span>下载客户端</span></a
          >
          <a href="javascript:;"
            ><i class="iconfont">&#xe61d;</i><span>我 的</span></a
          >
        </div>
        <div class="toolver">
          <a href="javascript:;">网站地图</a>
          <a href="javascript:;">Language</a>
          <a href="javascript:;">电脑版</a>
        </div>
        <div class="copyright">
          &copy;2020携程旅行|备案号
        </div>
      </footer>
      <!-- 底部链接 end -->
    </div>
  </div>
</template>

<script>
import "@/assets/styles/index.scss";
import HeadSearch from "../components/HeadSearch.vue";

export default {
  name: "Home",
  components: {
    HeadSearch,
  },
};
</script>
