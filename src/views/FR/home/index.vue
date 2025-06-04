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
      <span class="divider-title">Penelitian Sosial & Kebijakan Publik</span>
    </el-divider>
    <div class="divider-info">
      Satu Visi Konsultan memberikan dasar bukti untuk kebijakan publik dan perubahan sosial yang lebih efektif melalui penelitian dan penilaian yang ketat. Memberdayakan pembuat keputusan untuk meningkatkan hasil sosial dengan cara yang didorong data.
    </div>
    <div class="center-box">
      <el-row :gutter="20">
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-1"></div>
            <div class="home-title">1.325 Pelanggan</div>
            <div class="home-content">
              SVK telah menjalin kemitraan dengan 1.325 perusahaan di 30 industri.
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-2"></div>
            <div class="home-title">Perusahaan multinasional</div>
            <div class="home-content">
              Menangkan kerjasama dari banyak perusahaan multinasional dengan layanan konsultasi yang luar biasa untuk memenangkan ruang pengembangan pasar dengan strategi pengembangan "win-win".
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-3"></div>
            <div class="home-title">
              Perusahaan besar dan menengah
            </div>
            <div class="home-content">
              Perusahaan besar dan menengah menyumbang lebih dari 60% pelanggan SVK, 80% pelanggan memilih untuk bekerja sama lagi, 35% pelanggan merekomendasikan SVK kepada perusahaan lain, lebih dari 500 pelanggan mendapatkan perkembangan cepat dan mencapai pertumbuhan geometri keuntungan.
            </div>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <div class="home-icon icon-4"></div>
            <div class="home-title">Perusahaan awal</div>
            <div class="home-content">
              Pada tahun 2025, ratusan klien startup SVK telah berkembang menjadi perusahaan terdaftar, dan penelitian pasar dan kebijakan menjadi faktor kunci keberhasilannya. Dukungan layanan konsultasi SVK membuat startup berjalan lebih jauh.
            </div>
          </div>
        </el-col>
      </el-row>
    </div>
    <el-divider>
      <span class="divider-title"
        >SVK berharap untuk bekerja sama dengan Anda</span
      >
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
              >Mencari, menyaring, menguji, merekomendasikan, dan melakukan pemeriksaan latar belakang secara efisien sesuai dengan kebutuhan Anda
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >Menggunakan metode penelitian campuran mutakhir (kuantitatif + kualitatif) untuk memastikan penelitian mendalam dan representatif secara statistik
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >Fokus pada mengubah hasil penilaian yang kompleks menjadi saran strategis yang dapat dioperasikan
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >Memiliki tim interdisipliner yang kuat yang menggabungkan latar belakang profesional seperti sosiologi, ekonomi, kebijakan publik, dan ilmu data
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >Berbagi Wawasan Industri dan Informasi Langsung Tangan dengan Anda, Berbasis di Indonesia, Radiasi Global
            </li>
            <li>
              <i
                class="el-icon-check"
                style="color:#606ecd;font-size:20px;margin-right:10px"
              ></i
              >Kunjungi secara teratur perusahaan luar negeri dan dalam negeri untuk berbagi teori dan praktik manajemen bisnis canggih global dengan Anda
            </li>
          </ul>
        </div>
        <div style="width:500px;position:absolute;right:0;top:0">
          <img width="500px" height="335px" src="../../../assets/img/home/home-info.jpg" />
        </div>
      </div>
    </div>
    <div class="center-box u-tac" style="margin-top:50px">
      <el-button
        type="primary"
        icon="el-icon-s-flag"
        style="padding: 15px 40px;font-size:18px"
        @click="$router.push('./trade')"
        >Fokus pada industri dan bidang</el-button
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
  padding: 10px 0 6px 20px;
}
.bg-box .bg-content ul li {
  line-height: 20px;
  font-size: 16px;
  margin: 10px 0;
}
</style>
