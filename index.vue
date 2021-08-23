<template>
    <div >
        <div class="head">
            <div class="img">
                <img src="../assets/img/logo.png" alt="">
            </div>
            <div class="right">
                <div class="mine">
                    <img src="../assets/img/我的.png" alt="">
                    <p>我的</p>
                </div>
                <div class="guide">
                    <img src="../assets/img/更多.png" alt="">
                    <p>导航</p>
                </div>
            </div>
        </div>
        <div class="swiper">
            <img src="../assets/img/banner.jpg" alt="">
        </div>
        <div class="grid">
            <div class="grid1">
                <div class="icon one">
                    <i class="iconfont icon-case"></i>
                </div>
                <p>装修方案</p>
            </div>
            <div class="grid1">
                <div class="icon two">
                    <i class="iconfont icon-pics"></i>
                </div>
                <p>装修方案</p>
            </div>
            <div class="grid1">
                <div class="icon three">
                   <i class="iconfont icon-designer"></i> 
                </div>
                
                <p>设计师</p>
            </div>
            <div class="grid1">
                <div class="icon four">
                    <i class="iconfont icon-construction-site"></i>
                </div>
                <p>装修工地</p>
            </div>
            <div class="grid1">
                <div class="icon five">
                    <i class="iconfont icon-decorate"></i>
                </div>
                <p>装修攻略</p>
            </div>
           <div class="grid1">
                <div class="icon six">
                    <i class="iconfont icon-loans"></i>
                </div>
                <p>装修贷款</p>
            </div>
            <div class="grid1">
                <div class="icon seven">
                    <i class="iconfont icon-pencle"></i>
                </div>
                <p>免费预约</p>
            </div>
            <div class="grid1">
                <div class="icon eight">
                    <i class="iconfont icon-ten"></i>
                </div>
                <p>十秒报价</p>
            </div>

        </div>
    </div>
</template>
<style lang="scss" scoped>
html,
body {
  margin: 0;
  padding: 0;
  .head {
    width: 100%;
    display: flex;
    justify-content: space-between;
    .img {
      width: 40%;
      img {
        width: 150px;
        height: 60px;
        padding: 18px 16px -2px 16px;
      }
    }
    .right {
      display: flex;
      justify-content: space-between;
      .mine {
        img {
          width: 45px;
          height: 45px;
        }
        p {
          margin: 0px;
          text-align: center;
          font-size: 22px;
          color: #999;
        }
      }
      .guide {
        margin-left: 20px;
        img {
          margin-top: 10px;
          width: 33px;
          height: 33px;
          margin-left: 5px;
        }
        p {
          margin: 1px;
          text-align: center;
          font-size: 22px;
          color: #999;
        }
      }
    }
  }
  .swiper {
    width: 100%;

    img {
      width: 100%;
      margin-left: 0px;
      margin-right: 0px;
      padding-left: 0px;
      padding-right: 0px;
    }
  }
  .grid {
    width: 100%;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    .grid1 {
        p{
            text-align: center;
            font-size: 14px;
            color: #333;
        }
      .icon {
        width: 60px;
        height: 60px;
        border-radius: 50%;
        border: 1px solid #ddd;
        margin: 10px;
        i {
          color: white;
          font-size: 34px;
          display: inline-block;
          margin-top: 13px;
          margin-left: 13px;
        }
      }
      .one {
        background-color: #39c894;
      }
      .two{
          background-color: #feb505;
      }
      .three{
          background-color: #eed215;
      }
      .four{
          background-color: #00b2b2;
      }
      .five{
          background-color: #1b9af7;
      }
      .six{
          background-color: #7b72e9;
      }
      .seven{
          background-color: #ff4351;
      }
      .eight{
          background-color: #fe8864;
      }
    }
  }
}
</style>
