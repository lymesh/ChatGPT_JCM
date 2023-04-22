<template>
  <div class="setting">
    <el-container>
      <el-header>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <h3>开源地址</h3>
          </div>
        </transition>
      </el-header>
      <el-main>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <span>
             提供网页服务 by 探索分享，开源项目见github，如需要key可以查看<a href="shop.iosshop.xyz">Shop探索分享OpenAI</a> 
            <div>
              开源地址<a href="https://space.bilibili.com/326625155?spm_id_from=333.337.0.0">BliBili</a>---<a href="https://github.com/202252197/ChatGPT_JCM">GitHub</a>
            </div>
            <div>
              <h3></h3>
            </div>
          </div>
        </transition>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      show: false,
    };
  },
  mounted() {
    this.show = true;
  },
};
</script>

<style>
  .transition-box {
    text-align: center;
    margin-top: 5%;
    color: #F2F6FC;
    font-size: 30px;
  }
  h1 {
    color: aliceblue;
    font-size: 80px;
  }
  a {
    text-decoration: none;
    color: #67C23A;
  }
</style>
