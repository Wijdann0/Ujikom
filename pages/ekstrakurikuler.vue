<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-6 p-4">
            <h1 class="section-title pb-1">
                <strong>EKSTRAKURIKULER</strong>
            </h1>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3 d-flex justify-content-center pb-3">
                <div class="card custom-card rounded-4" style="width: 15rem; height: 100%;">
                    <div class="image-bang rounded-4">
                        <img src="/assets/image/Sepak.webp" class="d-block w-100 rounded-4" alt="Gambar Guru">
                        <div class="overlay rounded-4">
                            <p class="overlay-text">LAB BARU PPLG</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3 d-flex justify-content-center pb-3">
                <div class="card custom-card rounded-4" style="width: 15rem; height: 100%;">
                    <div class="image-bang rounded-4">
                        <img src="/assets/image/Paskib.webp" class="d-block w-100 rounded-4" alt="Gambar Guru">
                        <div class="overlay rounded-4">
                            <p class="overlay-text">LAB BARU PPLG</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3 d-flex justify-content-center pb-3">
                <div class="card custom-card rounded-4" style="width: 15rem; height: 100%;">
                    <div class="image-bang rounded-4">
                        <img src="/assets/image/Pks.webp" class="d-block w-100 rounded-4" alt="Gambar Guru">
                        <div class="overlay rounded-4">
                            <p class="overlay-text">LAB BARU PPLG</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3 d-flex justify-content-center pb-3">
                <div class="card custom-card rounded-4" style="width: 15rem; height: 100%;">
                    <div class="image-bang rounded-4">
                        <img src="/assets/image/Sfr.webp" class="d-block w-100 rounded-4" alt="Gambar Guru">
                        <div class="overlay rounded-4">
                            <p class="overlay-text">LAB BARU PPLG</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3 d-flex justify-content-center pb-3">
                <div class="card custom-card rounded-4" style="width: 15rem; height: 100%;">
                    <div class="image-bang rounded-4">
                        <img src="/assets/image/Prmk.webp" class="d-block w-100 rounded-4" alt="Gambar Guru">
                        <div class="overlay rounded-4">
                            <p class="overlay-text">LAB BARU PPLG</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3 d-flex justify-content-center pb-3">
                <div class="card custom-card rounded-4" style="width: 15rem; height: 100%;">
                    <div class="image-bang rounded-4">
                        <img src="/assets/image/Fut.webp" class="d-block w-100 rounded-4" alt="Gambar Guru">
                        <div class="overlay rounded-4">
                            <p class="overlay-text">LAB BARU PPLG</p>
                        </div>
                    </div>
                </div>
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

  .image-bang {
    position: relative;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

.image-bang:hover .overlay{
    opacity: 2;
}

.image-bang img {
    object-fit: cover;
    height: 100%;
    width: 100%;
}
</style>