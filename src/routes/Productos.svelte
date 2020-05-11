<style>
  h1{
      color: #0F4C75;
  }

  h3 {
      color:#3282b8; 
  }

  .container-products{
    display: flex;
    flex: 1;
    justify-content: space-around;
    margin: 2em 0;
    min-height: 400px;
    margin:0;
    padding: 5%;
  }

img {
  padding: 10px;
}

  @media (max-width: 1020px) {
  
  }
</style>

<svelte:head>
  <title>WLANTech-Productos</title>
</svelte:head>
    
    <h1><strong> Productos</strong></h1>
      <div class="container-products">
        <div>
          <img src="https://img.icons8.com/ios/50/000000/wifi.png" alt="wifi"/>
        </div>
          <div>
            <h3><strong> Puntos de Acceso  Wi-Fi</strong> </h3>
            Ofrecemos tecnologias Wi-Fi de tipo empresarial
          </div>
          <div>
            <img src="https://img.icons8.com/ios/50/000000/wired-network.png" alt="switch"/>
          </div>
          <div>
            <h3><strong>  Switchs </strong> </h3>
            Contamos con switchs de borde y de campus
        </div>
          <div>
            <img src="https://img.icons8.com/ios/50/000000/radio-tower.png" alt="tower"/>
          </div>
          <div>
            <h3><strong> Antenas </strong> </h3>
            Suministramos antenas para bandas licenciadas y no licenciadas.
          </div>
      </div>
 