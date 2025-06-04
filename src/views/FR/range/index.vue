<template>
  <div class="block">
    <el-divider>
      <div class="title">Kategori Layanan</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box">
        <div class="bg-content">
          <div class="title">Penilaian Kebijakan Publik</div>
          <p>
            Membuat penilaian efektivitas yang sistematis dan independen terhadap kebijakan dan peraturan yang dibuat pemerintah. Kami menilai efisiensi, efektivitas, relevansi, keberlanjutan, dan dampak kebijakan, mengidentifikasi pengalaman dan tantangan yang sukses, dan memberikan dasar ilmiah untuk penyesuaian, optimasi, atau penghentian kebijakan.
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
          <div class="title">Penelitian sosial mendalam</div>
          <p>
            Menyelidiki dan menganalisis secara mendalam fenomena sosial yang kompleks, perilaku kelompok, sikap masyarakat dan kebutuhan sosial. Penelitian kami memberikan dasar empiris yang kuat untuk pembuatan kebijakan, desain proyek, dan diagnosis masalah sosial.
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
          <div class="title">Pemantauan dan Evaluasi Proyek</div>
          <p>
            Menyediakan layanan pemantauan dan evaluasi siklus penuh untuk proyek-proyek penting perusahaan. Kami membantu pelanggan melacak kemajuan proyek, penggunaan sumber daya, dan hasil awal secara real-time dan secara teratur mengevaluasi efektivitas, efisiensi, dan keberlanjutan proyek untuk memastikan proyek berjalan sesuai rencana dan mencapai tujuan yang diinginkan.
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
          <div class="title">Pengumpulan dan analisis data</div>
          <p>
            SVK menawarkan layanan pengambilan data dan analisis mendalam yang profesional, efisien dan berkualitas tinggi yang mencakup data kuantitatif dan kualitatif untuk memberikan dukungan data yang kuat untuk pengambilan keputusan Anda.
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
