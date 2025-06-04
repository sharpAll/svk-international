<template>
  <div class="block">
    <el-divider>
      <div class="title">OUR SERVICES</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">Public Policy Evaluation</div>
          <p>
            Systematically and independently evaluate the effectiveness of policies and regulations formulated by the government. We evaluate the efficiency, effectiveness, relevance, sustainability, and impact of policies, identify successful experiences and challenges, and provide scientific basis for policy adjustment, optimization, or termination.
          </p>
        </div>
        <div style="width:500px;position:absolute;right:0;top:0">
          <img width="500px" src="../../../assets/img/range/range-1.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content right">
          <div class="title">Social Depth Research</div>
          <p>
            Thoroughly investigate and analyze complex social phenomena, group behavior, public attitudes, and social needs. Our research provides a solid empirical foundation for policy formulation, project design, and social problem diagnosis.
          </p>
        </div>
        <div style="width:500px;position:absolute;left:0;top:0">
          <img width="500px" src="../../../assets/img/range/range-2.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">Project Monitoring &. Evaluation</div>
          <p>
            Provide full cycle monitoring and evaluation services for important projects of enterprises. We help clients track project progress, resource utilization, and initial results in real-time, and regularly evaluate project effectiveness, efficiency, and sustainability to ensure that the project progresses as planned and achieves expected goals.
          </p>
        </div>
        <div style="width:500px;position:absolute;right:0;top:0">
          <img width="500px" src="../../../assets/img/range/range-3.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content right">
          <div class="title">Data Collection &. Analysis</div>
          <p>
            SVK provides professional, efficient, and high-quality data collection and in-depth analysis services, covering both quantitative and qualitative data, to provide solid data support for your decision-making.
          </p>
        </div>
        <div style="width:500px;position:absolute;left:0;top:0">
          <img width="500px" src="../../../assets/img/range/range-4.jpg" />
        </div>
      </div>
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
