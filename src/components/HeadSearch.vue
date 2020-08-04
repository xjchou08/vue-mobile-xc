<template>
  <div class="search">
    <div class="search_ipt">
      <span>搜索:目的地/酒店/景点/航班点</span>
    </div>
    <a href="javascript:;" class="login_bt">我 的</a>
  </div>
</template>

<script>
export default {
  name: "head-search",
};
</script>

<style lang="scss" scoped>
.search {
  height: 44px;
  background-color: #fff;
  padding-left: 12px;
  display: flex;
  align-items: center;
  .search_ipt {
    flex: 1;
    position: relative;
    span {
      width: 100%;
      display: block;
      color: #666;
      padding: 3px 5px;
      padding-left: 35px;
      overflow: hidden;
      box-sizing: border-box;
      border-radius: 15px;
      background: rgba(236, 236, 237);
    }
    span::before {
      position: absolute;
      top: 0;
      left: 0;
      transform: translate(40%, 28%);
      width: 35px;
      height: 100%;
      overflow: hidden;
      background: url("../assets/xc-sprite.png") no-repeat;
      background-size: 21px auto;
      content: "";
    }
  }
  .login_bt {
    width: 51px;
    height: 44px;
    color: rgba(34, 34, 34);
    text-align: center;
    padding-right: 5px;
    font-size: 13px;
    display: flex;
    flex-direction: column;
    box-sizing: border-box;
    box-sizing: -webkit-border-box;
    &::before {
      content: "";
      margin: 0 auto;
      width: 30px;
      height: 30px;
      background: url("../assets/xc-sprite.png") no-repeat;
      background-size: 85%;
      background-position: 1px -94px;
    }
  }
}
</style>
