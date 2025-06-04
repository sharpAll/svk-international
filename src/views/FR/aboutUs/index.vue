<template>
  <div class="block">
    <el-divider>
      <div class="title">Tentang Satu Visi Konsultan</div>
      <div class="title-1">Satu Visi Konsultan（SVK）</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">Layanan konsultasi profesional</div>
          <p>
            SVK adalah perusahaan konsultan independen terkemuka yang berfokus pada penerapan metode penelitian ilmu sosial canggih dan kerangka penilaian yang ketat untuk membantu perusahaan, organisasi internasional, dan lembaga nirlaba memahami masalah sosial yang kompleks, mengevaluasi secara ilmiah keberhasilan kebijakan dan proyek, dan memberikan saran praktis untuk meningkatkan kualitas pengambilan keputusan.
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
          <div class="title">Bisnis di seluruh dunia</div>
          <p>
            Berakar di Indonesia dan memperluas operasi ke pasar luar negeri, bercakupan global mencakup pusat-pusat bisnis utama global seperti Asia Tenggara, Hong Kong dan daratan Cina, New York, Amerika Serikat, London, Inggris, Paris, Prancis, Vancouver, Kanada, dan Brussels, Belgia, berkomitmen untuk mengembangkan fungsi sektor vertikal dan segmen industri yang berfokus.
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
          <div class="title">Tim Konsultan Profesional</div>
          <p>
            Didukung oleh sumber daya pelanggan yang kuat, tim konsultan profesional kami memiliki pengalaman penelitian yang luas dan cadangan pengetahuan yang mendalam untuk membantu perusahaan memanfaatkan peluang perubahan pasar dengan strategi yang telah terbukti. SVK telah memenangkan penghargaan kehormatan seperti "Penyedia Layanan Konsultan Terbaik" dalam industri selama bertahun-tahun berturut-turut.
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
        >Hubungi Kami</el-button
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
  padding: 70px 80px 0;
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
