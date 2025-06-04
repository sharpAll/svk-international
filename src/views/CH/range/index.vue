<template>
  <div class="block">
    <el-divider>
      <div class="title">服务范畴</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">公共政策评估</div>
          <p>
            对政府制定的政策法规进行系统性、独立性的成效评估。我们评估政策的效率、效果、相关性、可持续性及影响力，识别成功经验与挑战，为政策调整、优化或终止提供科学依据。
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
          <div class="title">社会深度研究</div>
          <p>
            深入调查和分析复杂的社会现象、群体行为、公众态度及社会需求。我们的研究为政策制定、项目设计和社会问题诊断提供坚实的实证基础。
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
          <div class="title">项目监测与评估</div>
          <p>
            为企业的重要项目提供全周期的监测与评估服务。我们帮助客户实时追踪项目进展、资源使用和初步成果，并定期评估项目的效果、效率和可持续性，确保项目按计划推进并达成预期目标。
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
          <div class="title">数据收集与分析</div>
          <p>
            SVK提供专业、高效、高质量的数据采集与深度分析服务，涵盖定量与定性数据，为您的决策提供坚实的数据支撑。
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
