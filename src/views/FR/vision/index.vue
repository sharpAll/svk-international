<template>
  <div class="block">
    <el-divider>
      <div class="title">Visi kami</div>
    </el-divider>
    <div class="title-1">
      <p>
        Mencerahkan kebijakan dengan bukti untuk mengevaluasi perubahan yang mendorong dan memberikan dasar teoritis untuk pengambilan keputusan besar yang lebih efisien dan ilmiah.
      </p>
    </div>
    <div class="center-box" style="width:100%">
      <img
        style="margin:auto"
        width="100%"
        src="../../../assets/img/vision/vision-1.jpg"
      />
    </div>
    <el-divider>
      <div class="title">Misi Kami</div>
    </el-divider>
    <div class="title-1">
      <p>
        Menjadi mitra layanan konsultasi pilihan pelanggan
      </p>
      <p>
        Berkomitmen untuk memungkinkan perusahaan yang hebat menemukan platform dan peluang yang paling sesuai dengan nilai-nilai mereka
      </p>
      <p>
        Berdedikasi untuk membangun tim konsultan ahli terbaik
      </p>
    </div>
    <div class="center-box" style="width:100%">
      <img
        style="margin:auto"
        width="100%"
        src="../../../assets/img/vision/vision-2.jpg"
      />
    </div>
    <el-divider>
      <div class="title">Keuntungan kami</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box" style="height:500px">
        <div class="vision-content">
          <div class="vision-title">Pemimpin Evaluasi Kebijakan</div>
          <p>
            SVK memiliki keterampilan dan fleksibilitas dalam menerapkan kerangka kerja penilaian kebijakan domestik utama internasional (seperti standar OECD-DAC, Evaluasi Berdorong Teori, Evaluasi Realis, Analisis Kontribusi) dan dapat menyesuaikan program penilaian sesuai dengan karakteristik proyek.
          </p>
        </div>
        <div class="vision-content">
          <div class="vision-title">Pengalaman Praktik</div>
          <p>
            Tim konsultan profesional SVK memiliki rata-rata lebih dari 5 tahun pengalaman dalam industri konsultasi dan telah dilatih secara profesional dan sistematis dalam SVK untuk mengikuti secara ketat alur kerja standar. Memiliki latar belakang praktis dalam industri yang difokuskan adalah kekuatan unik tim SVK, yang dapat memberikan pemahaman yang lebih mendalam tentang industri dan memberikan layanan yang lebih akurat kepada pelanggan dan calon.
          </p>
        </div>
        <div class="vision-content">
          <div class="vision-title">
            Fokus pada bidang vertikal
          </div>
          <p>
            Konsultan SVK dibagi dalam industri menjadi lebih dari selusin tim, setiap tim berkomitmen untuk mengembangkan sektor vertikal yang berfokus pada industri, memahami sepenuhnya status dan tren industri, memposisikan pasar secara akurat, berusaha untuk menyediakan layanan yang lebih profesional dan efisien dan lebih dekat dengan permintaan perusahaan.
          </p>
        </div>
        <div style="position:absolute;right:0;top:0;overflow:hidden">
          <img
            width="460px"
            height="500px"
            src="../../../assets/img/vision/vision-4.jpg"
          />
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
  margin: 20px auto;
  font-size: 16px;
  color: #bbb;
  text-align: center;
}
.title-1 p {
  line-height: 25px;
}
.bg-box {
  background-color: #f9f9f9;
  position: relative;
  margin-top: 40px;
}
.bg-box .vision-title {
  font-size: 20px;
  padding-left: 30px;
  text-align: left;
  position: relative;
  margin-bottom: 10px;
}
.bg-box .vision-title::after {
  content: "";
  display: block;
  width: 3px;
  height: 18px;
  background: #606ecd;
  left: 0;
  top: 5px;
  position: absolute;
}
.bg-box .vision-content {
  margin-right: 500px;
  padding: 20px 20px 0;
  height: auto;
}
.bg-box .vision-content.right {
  margin-right: 0;
  margin-left: 500px;
}
.bg-box .vision-content p {
  line-height: 24px;
  color: #888;
  font-size: 15px;
}
</style>
