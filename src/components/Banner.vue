<template>
  <div class="banner">
    <div class="container">
      <div class="banner-content">
        <div class="main-banner">
          <div class="img-container">
            <img src="../assets/Images/Banner1.png" alt="" />

            <div class="img-content">
              <span>Banner</span>
              <h3>Your Title text</h3>
            </div>
          </div>
        </div>
        <div class="category-banner">
          <div class="top">
            <div class="img-container">
              <img src="../assets/Images/Banner3.png" alt="" style="width: 305px; height: 300px;"/>

              <div class="img-content">
              <h3>women</h3>
              </div>
            </div>
            <div class="img-container">
              <img src="../assets/Images/Banner2.png" alt="" style="width: 305px; height: 300px;" />

              <div class="img-content">
                <h3>Men</h3>
              </div>
            </div>
            
          </div>
          <div class="bottom">
            <div class="img-container">
              <img src="../assets/Images/Banner4.png" alt="" />

              <div class="img-content">
                <h3>Accessories</h3>
              </div>
            </div>
          </div>
        </div>
        

      </div>
      <div class="banner-servieces">
        <div class="service">
            <span class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#000000"><path d="M240-160q-50 0-85-35t-35-85H40v-440q0-33 23.5-56.5T120-800h560v160h120l120 160v200h-80q0 50-35 85t-85 35q-50 0-85-35t-35-85H360q0 50-35 85t-85 35Zm0-80q17 0 28.5-11.5T280-280q0-17-11.5-28.5T240-320q-17 0-28.5 11.5T200-280q0 17 11.5 28.5T240-240ZM120-360h32q17-18 39-29t49-11q27 0 49 11t39 29h272v-360H120v360Zm600 120q17 0 28.5-11.5T760-280q0-17-11.5-28.5T720-320q-17 0-28.5 11.5T680-280q0 17 11.5 28.5T720-240Zm-40-200h170l-90-120h-80v120ZM360-540Z"/></svg>    
            </span>
            <div class="details">
                <h6>FREE SHIPING</h6>
                <p>On all UA order or Order Above Rs1000</p>
            </div>
        </div>
        <div class="service">
            <span class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#000000"><path d="M240-160q-50 0-85-35t-35-85H40v-440q0-33 23.5-56.5T120-800h560v160h120l120 160v200h-80q0 50-35 85t-85 35q-50 0-85-35t-35-85H360q0 50-35 85t-85 35Zm0-80q17 0 28.5-11.5T280-280q0-17-11.5-28.5T240-320q-17 0-28.5 11.5T200-280q0 17 11.5 28.5T240-240ZM120-360h32q17-18 39-29t49-11q27 0 49 11t39 29h272v-360H120v360Zm600 120q17 0 28.5-11.5T760-280q0-17-11.5-28.5T720-320q-17 0-28.5 11.5T680-280q0 17 11.5 28.5T720-240Zm-40-200h170l-90-120h-80v120ZM360-540Z"/></svg>    
            </span>
            <div class="details">
                <h6>FREE SHIPING</h6>
                <p>On all UA order or Order Above Rs1000</p>
            </div>
        </div>
        <div class="service">
            <span class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#000000"><path d="M240-160q-50 0-85-35t-35-85H40v-440q0-33 23.5-56.5T120-800h560v160h120l120 160v200h-80q0 50-35 85t-85 35q-50 0-85-35t-35-85H360q0 50-35 85t-85 35Zm0-80q17 0 28.5-11.5T280-280q0-17-11.5-28.5T240-320q-17 0-28.5 11.5T200-280q0 17 11.5 28.5T240-240ZM120-360h32q17-18 39-29t49-11q27 0 49 11t39 29h272v-360H120v360Zm600 120q17 0 28.5-11.5T760-280q0-17-11.5-28.5T720-320q-17 0-28.5 11.5T680-280q0 17 11.5 28.5T720-240Zm-40-200h170l-90-120h-80v120ZM360-540Z"/></svg>    
            </span>
            <div class="details">
                <h6>FREE SHIPING</h6>
                <p>On all UA order or Order Above Rs1000</p>
            </div>
        </div>
    </div>
    </div>
    
  </div>
</template>

<script setup></script>

<style scoped>
img {
  height: 100%;
}
.banner {
    border: 2px solid #f8f8f8;
    margin-bottom: 100px;
}
.banner .container {
  max-width: calc(1440px - 170px);
  
  width: 100%;
  margin: auto;
}

.banner-content {
  display: flex;
  justify-content: space-between;
  padding: 40px 0px;
}

.banner-content >div{
    flex: 0 0 calc(50% -20px);
    max-width: calc(50% - 20px);
    width: 100%;
}

.img-container{
    position: relative;
    height: 100%;
    width: 100%;
}

.img-container img{
    width: 100%;

    object-fit: cover;
}

.img-container .img-content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: #ffffff;
    border-radius: 4px;
    padding: 16px 32px;
    text-align: center;
}

.img-content span {
    font-weight: 600;
    font-size: 12px;
    line-height: 13px;
    color: #121212;   
    opacity: 0.4;

}

.img-content h3{
    font-weight: 600;
    font-size: 22px;
    line-height: 25px;
    color: #121212;
    text-transform: uppercase;
    margin-top: 5px;
}

.category-banner .top{
    display: flex;
    justify-content: space-between;
    margin-bottom: 30px;
}

.category-banner .top > div {
    flex: 0 0 calc(50% -20px);
    max-width: 0 0 calc(50% - 20px);
    width: 100%;
}

.banner-servieces{
    display: flex;
    justify-self: space-between ;
    margin-bottom: 30px;
    align-items: center;
}
.banner-servieces > div{
    flex: 0 0 calc(33.33% -20px);
    max-width: 0 0 calc(33.33% - 20px);
    width: 100%;
    display: flex;
    align-items: center;
}

.service .details{
    margin-left: 10px ;
}

.details h6{
    font-weight: 600;
    font-size: 12px;
    line-height: 13px;
}

.details p{
    font-weight: 500;
    font-size: 12px;
    line-height: 22px;
    opacity: 0.9;
}
</style>
