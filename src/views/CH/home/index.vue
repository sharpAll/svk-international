<template>
  <div class="block">
    <el-carousel height="400px">
      <el-carousel-item>
        <div class="carousel-bg bg-2"></div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="carousel-bg bg-1"></div>
      </el-carousel-item>
    </el-carousel>
    <el-divider>
      <span class="divider-title">社会研究 & 公共政策</span>
    </el-divider>
    <div class="divider-info">
      Satu Visi Konsultan通过严谨的研究和评估，为更有效的公共政策和社会变革提供证据基础。为决策者赋能，以数据驱动的方式改善社会成果。
    </div>
    <div class="center-box">
      <el-row :gutter="20">
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-1"></div>
            <div class="home-title">1325家签约客户</div>
            <div class="home-content">
              SVK已经与30个行业的1325家企业建立了合作伙伴关系。
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-2"></div>
            <div class="home-title">跨国公司</div>
            <div class="home-content">
              用出色的咨询服务赢取众多跨国公司的合作，以“双赢”发展战略赢取市场发展空间。
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-3"></div>
            <div class="home-title">大中型企业</div>
            <div class="home-content">
              大中型企业占SVK客户60%以上，80%的客户选择再次合作，35%客户向其他公司推荐SVK，
              500多家客户获得迅猛发展，实现了利润几何级增长。
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-4"></div>
            <div class="home-title">初创公司</div>
            <div class="home-content">
              截至2025年，SVK有上百家初创企业客户已发展成上市公司，
              对市场与政策的研究成为其成功的关键因素。SVK的咨询服务支持让初创公司走得更远。
            </div>
          </div>
        </el-col>
      </el-row>
    </div>
    <el-divider>
      <span class="divider-title">SVK期待与您合作</span>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <ul>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >根据您的需求高效寻访、筛选、测评、推荐、做背景调查
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >采用前沿的混合研究方法（定量+定性），确保研究既深刻又具有统计代表性
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >专注于将复杂的评估结果转化为可操作的策略建议
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >拥有强大的跨学科团队，融合社会学、经济学、公共政策、数据科学等专业背景
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >与您共享行业洞见与一手资讯，立足印尼，辐射全球
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >定期参访国内外优秀企业，与您共享全球先进经营管理理论与实务
            </li>
          </ul>
        </div>
        <div style="width:500px;position:absolute;right:0;top:0">
          <img width="500px" src="../../../assets/img/home/home-info.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box u-tac" style="margin-top:50px">
      <el-button
        type="primary"
        icon="el-icon-s-flag"
        style="padding: 15px 40px;font-size:18px"
        @click="$router.push('./trade')"
        >专注行业及领域</el-button
      >
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style scoped>
.carousel-bg {
  width: 100%;
  height: 100%;
}
.carousel-bg.bg-1 {
  background: center url(../../../assets/img/1.jpg) no-repeat;
  background-size: cover;
}
.carousel-bg.bg-2 {
  background: center url(../../../assets/img/2.jpg) no-repeat;
  background-size: cover;
}
.home-icon {
  width: 100px;
  height: 100px;
  margin: 20px auto 15px;
}
.home-icon.icon-1 {
  background: #1b3045 center url(../../../assets/img/home/icon-home1.png)
    no-repeat;
  background-size: cover;
}
.home-icon.icon-2 {
  background: #1b3045 center url(../../../assets/img/home/icon-home2.png)
    no-repeat;
  background-size: cover;
}
.home-icon.icon-3 {
  background: #1b3045 center url(../../../assets/img/home/icon-home3.png)
    no-repeat;
  background-size: cover;
}
.home-icon.icon-4 {
  background: #1b3045 center url(../../../assets/img/home/icon-home4.png)
    no-repeat;
  background-size: cover;
}
.home-title {
  color: #333;
  font-size: 18px;
  margin: 8px auto;
  text-align: center;
}
.home-content {
  margin: 0 20px;
  color: #9b9b9b;
  font-size: 14px;
  line-height: 20px;
}
.bg-box {
  background-color: #f9f9f9;
  position: relative;
  margin-top: 40px;
}
.bg-box .bg-content {
  margin-right: 500px;
}
.bg-box .bg-content ul {
  padding: 30px 0 30px 20px;
}
.bg-box .bg-content ul li {
  line-height: 30px;
  font-size: 16px;
  margin: 10px 0;
}
</style>
