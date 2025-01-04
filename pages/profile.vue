<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-6 p-4">
            <h1 class="section-title pb-1">
                <strong>Profile</strong>
            </h1>
            </div>
        </div>
        <hr>
        <!-- Sejarah -->
        <div class="row">
          <div class="col">
            <h5 class="section-title fs-3 pb-1" >Sejarah</h5>
            <p style="text-align: justify;">
              <span>
                Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu Kota  Tasikmalaya, terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
              </span>
            </p>
          </div>
        </div>
        <div class="row">
            <div class="col p-3 text-center">
                <button type="button" class="btn btn-success tombol">
                    <a href="/sejarah" class="text-decoration-none text-white">Selengkapnya</a>
                </button>
            </div>
        </div>
        <hr>
        <!-- Visi Misi -->
        <div class="row">
          <div class="col">
            <h5 class="section-title fs-3 pb-1">Visi dan Misi</h5>
          </div>
        </div>
        <div class="row">
          <div class="col">
            <p class="pt-3">
              <span>
                Visi : " Dengan Berlandaskan Iman dan Taqwa Menghasilkan Tamatan yang Cerdas,Akhlak mulia, Kreatif, Aktif, Produktif (CAKAP) "
              </span>
            </p>
            <p>
                Misi : 
              <ol>
                <li>
                   Mengembangkan kecerdasan Peserta didik agar Berprestasi, beriman dan bertaqwa pada Tuhan Yang maha Esa, berakhlak mulia, berkarakter, berwawasan kebangsaan, berjiwa entrepreneur, serta peduli lingkungan.
                </li>
              </ol>
            </p>
          </div>
        </div>
        <div class="row">
            <div class="col p-3 text-center">
                <button type="button" class="btn btn-success tombol">
                    <a href="/visiMisi" class="text-decoration-none text-white">Selengkapnya</a>
                </button>
            </div>
        </div>
        <hr>
        <div class="row">
          <div class="col">
            <h5 class="section-title fs-3 pb-1">Guru dan Staf</h5>
          </div>
        </div>
        <div class="row">
          <div class="col-md-3 d-flex justify-content-center p-4">
            <div class="card custom-card rounded-4" style="width: 15rem; height: 225px;">
              <div class="image-container rounded-4">
                <img src="/assets/image/mas.png" class="d-block w-100" alt="Gambar Guru">
                <div class="overlay">
                  <p class="overlay-text">
                    <span>
                      Kurniawan
                      (Kepala Sekolah)
                    </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-3 d-flex justify-content-center p-4">
            <div class="card custom-card rounded-4" style="width: 15rem; height: 225px;">
              <div class="image-container rounded-4">
                <img src="/assets/image/Fik.webp" class="d-block w-100" alt="Gambar Guru">
                <div class="overlay">
                  <p class="overlay-text">
                    <span>
                      Taufik Hidayat
                      (Kepala Program)
                    </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-3 d-flex justify-content-center p-4">
            <div class="card custom-card rounded-4" style="width: 15rem; height: 225px;">
              <div class="image-container rounded-4">
                <img src="/assets/image/Zul.webp" class="d-block w-100" alt="Gambar Guru">
                <div class="overlay">
                  <p class="overlay-text">
                    <span>
                      Zul Hilmi
                      (Kepala Bengkel)
                    </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-3 d-flex justify-content-center p-4">
            <div class="card custom-card rounded-4" style="width: 15rem; height: 225px;">
              <div class="image-container rounded-4">
                <img src="/assets/image/Lisye.webp" class="d-block w-100" alt="Gambar Guru">
                <div class="overlay">
                  <p class="overlay-text">
                    <span>
                      Lisye Diana
                      (Wali Kelas)
                    </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
            <div class="col p-3 text-center">
                <button type="button" class="btn btn-success tombol">
                    <a href="/guruStaf" class="text-decoration-none text-white">Selengkapnya</a>
                </button>
            </div>
        </div>
        <hr>
        <div class="row">
          <div class="col">
            <h5 class="section-title fs-3 pb-1">Informasi Sekolah</h5>
          </div>
        </div>
    </div>
</template>
<style scoped>
.section-title {
  display: inline-block;
  position: relative;
  font-size: 2.5rem; 
  font-weight: bold;
}

.section-title::after {
  content: "";
  position: absolute;
  width: 50%; 
  height: 4px;
  background-color: #4caf50; 
  bottom: -5px; 
  left: 0; 
}

.tombol{
    width: 200px;
}
.image-container {
    position: relative;
    width: 100%;
    overflow: hidden;
  }
  
  .image-container img {
    display: block;
    width: 100%;
    transition: transform 0.3s ease;
  }
  
  .image-container:hover img {
    transform: scale(1.1); 
  }
  
  
  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 0, 0, 0.5); 
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    transition: opacity 0.3s ease;
  }
  
  .image-container:hover .overlay {
    opacity: 1;
  }
  
  .overlay-text {
    color: #fff;
    font-size: 1rem;
    text-align: center;
  }
</style>