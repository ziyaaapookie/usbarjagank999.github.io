<template>
    <div>
      <!-- Our Product -->
      <div class="our-house" id="our-house">
        <div class="container">
          <h1 data-aos="fade-up" data-aos-duration="1000">Produk Kami</h1>
          <p data-aos="fade-up" data-aos-delay="200" data-aos-duration="1000">
            Produk terbaik Rice Milling Kami
          </p>
          <!-- Product List -->
          <div class="product-list">
            <div class="product-item">
              <img src="@/assets/images/alat1.jpg" alt="house-img" />
              <div class="house-desc">
                <h2>Paket 1-2 Ton/Jam Siap Konsumsi</h2>
                <h4>&#9745; Elvator 3 Unit 5/6in</h4>
                <h4>&#9745; Huller Yanmar 2 Unit</h4>
                <h4>&#9745; Saringan Gabah 1 Unit</h4>
                <h4>&#9745; Polisher 2 Unit N70</h4>
                <h4>&#9745; Penggerak Mesin Mobil P100</h4>
              </div>
            </div>
            <div class="product-item">
              <img src="@/assets/images/alat2.jpg" alt="house-img" />
              <div class="house-desc">
                <h2>Paket 3-5 Ton/Jam Glosor & Poles</h2>
                <h4>&#9745; Elvator 8 Unit 6in</h4>
                <h4>&#9745; Huller hu 1 Unit</h4>
                <h4>&#9745; Polisher 2 Unit N70</h4>
                <h4>&#9745; Separator</h4>
                <h4>&#9745; Seed Cleaner</h4>
                <h4>&#9745; Cello / Tandon Beras</h4>
              </div>
            </div>
            <div class="product-item">
              <img src="@/assets/images/alat3.jpg" alt="house-img" />
              <div class="house-desc">
                <h2>Paket 1,5-2 Ton/Jam Poles Satake</h2>
                <h4>&#9745; Elvator 3 Unit 5/6in</h4>
                <h4>&#9745; Polisher Satake</h4>
                <h4>&#9745; Ayakan Mesin</h4>
                <h4>&#9745; PK HU</h4>
              </div>
            </div>
            <div class="product-item">
              <img src="@/assets/images/alat4.jpg" alt="house-img" />
              <div class="house-desc">
                <h2>Paket Selepan Keliling</h2>
                <h4>&#9745; Huller Yanmar/LM 1 Unit</h4>
                <h4>&#9745; Polisher N70 1 Unit</h4>
                <h4>&#9745; Penggerak Disel 1 Unit</h4>
                <h4>&#9745; Sasis</h4>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Our Product -->
    </div>
  </template>
  
 
  
  <style scoped>
  .our-house {
    padding: 50px 0;
    background-color: #f9f9f9;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
  }
  
  h1 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
  }
  
  p {
    font-size: 16px;
    line-height: 1.5;
    color: #666;
    text-align: center;
    margin-bottom: 40px;
  }
  
  .product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  
  .product-item {
    flex: 1 1 45%;
    margin-bottom: 30px;
    text-align: center;
  }
  
  .product-item img {
    width: 70%;
    height: 200px;
    object-fit: cover;
    border-radius: 20px 20px 20px 20px;
  }
  
  .house-desc {
    margin-top: 10px;
  }
  
  .house-desc h2 {
    font-size: 24px;
    margin-bottom: 10px;
  }
  
  .house-desc h4 {
    color: rgba(0, 0, 0, 0.8);
  }
  
  /* Responsive styling */
  @media (max-width: 768px) {
    .product-item {
      flex: 1 1 100%;
    }
    
    .product-item img {
      height: auto;
    }
    
    h1 {
      font-size: 28px;
    }
  
    p {
      font-size: 14px;
    }
  }
  
  @media (max-width: 480px) {
    h1 {
      font-size: 24px;
    }
  
    p {
      font-size: 12px;
    }
  
    .house-desc h2 {
      font-size: 20px;
    }
  
    .house-desc h4 {
      font-size: 14px;
    }
  }
  </style>
  