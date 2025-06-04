<template>
  <div class="block">
    <el-divider>
      <div class="title">WHO WE ARE</div>
      <div class="title-1">Satu Visi Konsultan（SVK）</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">Professional consulting services</div>
          <p>
            SVK is a leading independent consulting firm that focuses on using advanced social science research methods and rigorous evaluation frameworks to help businesses, international organizations, and non-profit organizations understand complex social issues, scientifically evaluate policy and project effectiveness, and provide practical recommendations to improve decision-making quality.
          </p>
        </div>
        <div style="width:500px;position:absolute;right:0;top:0">
          <img width="500px" src="../../../assets/img/aboutUs/about1.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content right">
          <div class="title">Globally-covered Business</div>
          <p>
            Rooted in Indonesia and expanding its business to overseas markets, the business scope radiates globally, covering major political and business centers such as Southeast Asia, Hong Kong and mainland China, New York City in the United States, London in the United Kingdom, Paris in France, Vancouver in Canada, and Brussels in Belgium. It is committed to deepening its vertical fields and segmented functions in the industries it focuses on.
          </p>
        </div>
        <div style="width:500px;position:absolute;left:0;top:0">
          <img width="500px" src="../../../assets/img/aboutUs/about2.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">Professional Consultancy Team</div>
          <p>
            Backed by strong customer resources, our professional consulting team has rich research experience and profound knowledge reserves, and knows how to use effective strategies to help enterprises seize market change opportunities. SVK has won honors such as "Best Consulting Service Provider" in the industry for many years.
          </p>
        </div>
        <div style="width:500px;position:absolute;right:0;top:0">
          <img width="500px" src="../../../assets/img/aboutUs/about3.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box u-tac" style="margin-top:50px">
      <el-button
        type="primary"
        icon="el-icon-phone"
        style="padding: 15px 40px;font-size:18px"
        @click="$router.push('./aboutUs/contactUs')"
        >CONTACT US</el-button
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
.title {
  font-size: 24px;
  color: #333;
  text-align: center;
}
.title-1 {
  font-size: 14px;
  color: #ccc;
  text-align: center;
}
.bg-box {
  background-color: #f9f9f9;
  position: relative;
  margin-top: 40px;
}
.bg-box .title {
  font-size: 20px;
  padding-left: 30px;
  text-align: left;
  position: relative;
  margin-bottom: 30px;
}
.bg-box .title::after {
  content: "";
  display: block;
  width: 3px;
  height: 18px;
  background: #606ecd;
  left: 0;
  top: 5px;
  position: absolute;
}
.bg-box .bg-content {
  margin-right: 500px;
  padding: 70px 120px 0;
  height: 333px;
}
.bg-box .bg-content.right {
  margin-right: 0;
  margin-left: 500px;
}
.bg-box .bg-content p {
  line-height: 28px;
  color: #888;
  font-size: 15px;
}
</style>
