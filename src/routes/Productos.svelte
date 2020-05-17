<style>
  h1{
      color:#0F4C75 ;
  }

  h3 {
      color:#3282b8; 
  }

  .container-products{
    display: flex;
    flex: 1;
    justify-content: space-between;
    min-height: 600px;
    padding: 1%;
    flex-wrap: wrap;
  }

  .products-imageContainer{
    width: 50%;
    height: 10;
    flex-wrap: wrap;
    display: flex;
  }

  .products-imageContainer img {
    max-width: 100%;
    align-items: center;
    padding: 20px;
  }
.sub-products {
  align-items: center;
  justify-content: space-around;
  padding: 10px;
  width: 100%;
  height: 100%;
  display: flex;
  border: 2px solid #bbe1fa;
  border-radius: 10px;
  margin-bottom: 15px;
}

.sub-products div {
  width: 500px;
  padding: 10px;
  margin:10px;
}


.fotos {
    width: 50%;
    height: 100%;
    max-width: 500px;
    max-height: 500px;
    padding: 10px;
    align-items: center;
    flex-shrink: 0;
    
}


  @media (max-width: 1020px) {
  
  .products-imageContainer{
    display: block;
    padding: 0px;
  }
  .sub-products{
    flex-wrap: wrap;
  }

.fotos {
  width:200%;
}
  
  }

</style>

<svelte:head>
  <title>WLANTech-Productos</title>
</svelte:head>
    
    <h1><strong> Productos</strong></h1>
      <section>
      <div class="container-products">
      
        <div class="sub-products">
          <img  src="https://img.icons8.com/ios/50/000000/wifi.png" alt="wifi"/>
          <div>
            <h3><strong> Puntos de Acceso  Wi-Fi</strong> </h3>
            <h4> Ofrecemos tecnologias Wi-Fi de tipo empresarial gestionados desde la nube </h4>
          </div>
            <figure class="products-imageContainer">
              <img class="fotos"  width= "500" src="https://14slph41wbtl2yi39625md6s-wpengine.netdna-ssl.com/wp-content/uploads/2018/07/04-AP-3935_Product-Image_1140x640-500x281.png" alt="AP_extreme">
              <img class="fotos" width="500" src="https://www.ruijienetworks.com/FU/Upload/Product/2020/2-15/20202155929288.png" alt="AP_Ruijie">
            </figure>
              
        </div>
      
        
      
        <div class="sub-products">
            <img class="iconos" src="https://img.icons8.com/ios/50/000000/wired-network.png" alt="switch"/>
          <div>
            <h3><strong>  Switchs </strong> </h3>
            Contamos con switchs de borde y de campus de ultima tecnologia y alto rendimiento
          </div>
            <figure class="products-imageContainer">
              <img class="fotos"  src="https://14slph41wbtl2yi39625md6s-wpengine.netdna-ssl.com/wp-content/uploads/2018/07/29-X620_Product-Image_1140x640-500x281.png" alt="sw_extreme">
              <img class="fotos"  src="https://www.ruijienetworks.com//FU/Upload/Product/2020/2-14/20202149648179.jpg" alt="sw_Ruijie">
            </figure>
              
          </div>
        </div>
      </section>
        
      