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
      <span class="divider-title">Social Research &. Public Policy</span>
    </el-divider>
    <div class="divider-info">
      Satu Visi Konsultan provides an evidence base for more effective public policies and social change through rigorous research and evaluation. 
      Empower decision-makers to improve social outcomes in a data-driven manner.
    </div>
    <div class="center-box">
      <el-row :gutter="20">
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-1"></div>
            <div class="home-title">
              Contracts with 1325 enterprises partners
            </div>
            <div class="home-content">
              SVK has established partnerships with 1325 companies in 30 industries.
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-2"></div>
            <div class="home-title">
              International Companies
            </div>
            <div class="home-content">
              Winning cooperation with numerous multinational companies through excellent consulting services and gaining market development space through a "win-win" development strategy.
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-3"></div>
            <div class="home-title">
              Mid and Large scale private companies
            </div>
            <div class="home-content">
              Large and medium-sized enterprises account for over 60% of SVK customers, 80% of customers choose to cooperate again, and 35% of customers recommend SVK to other companies, More than 500 customers have achieved rapid development and achieved geometric growth in profits.
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-4"></div>
            <div class="home-title" style="line-height: 51.2px;">
              Startups
            </div>
            <div class="home-content">
              As of 2025, SVK has over a hundred start-up clients that have developed into listed companies, The study of markets and policies has become a key factor in its success. SVK's consulting services support enables startups to go further.
            </div>
          </div>
        </el-col>
      </el-row>
    </div>
    <el-divider>
      <span class="divider-title">SVK anticipates to cooperate with you</span>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <ul>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i>
              Efficiently search, screen, evaluate, recommend, and conduct background checks based on your needs
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i>
              Adopting cutting-edge mixed research methods (quantitative+qualitative) to ensure that the research is both profound and statistically representative
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i>
              Focus on transforming complex evaluation results into actionable strategic recommendations
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i>
              Having a strong interdisciplinary team that integrates professional backgrounds in sociology, economics, public policy, data science, and more
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i>
              Sharing industry insights and first-hand information with you, based in Indonesia, radiating globally
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i>
              Regularly visit outstanding domestic and foreign enterprises to share advanced global management theories and practices with you
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
        >SPECIALIZED INDUSTRIES</el-button
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
  height: 307px;
}
.bg-box .bg-content ul {
  padding: 10px 0 10px 20px;
}
.bg-box .bg-content ul li {
  line-height: 16px;
  font-size: 16px;
  margin: 10px 0;
}
</style>
