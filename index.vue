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
}
</style>
