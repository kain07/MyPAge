<style>

  h1{
      color: #0F4C75;
  }

  h3 {
      color:#3282b8; 
  }

.container-services{
  
  flex-wrap: wrap;
}

.subservicios{
  width: 800px;
  justify-content: space-around;
  /* border: 1px solid #0F4C75; */
}

  @media (max-width: 1020px) {
    .subservicios{
      max-width: 100%;
    }
  }
</style>

<svelte:head>
  <title>WLANTech-Servicios</title>
</svelte:head>

<h1><strong> Servicios </strong></h1>
<br>
<br>
      <div class="container-services">
          <div class="subservicios">
            <h3><strong> Serviciós de red</strong> </h3>
                <div>
                <li>Administración de redes Wi-Fi</li>
                <li>Consultoria de redes Wireless</li>
                <li> Wireless Site survey.</li>
                </div>
          </div>
          <br>
          <div class="subservicios">
            <h3><strong>  Servicios de instalación </strong> </h3>
                <div>
                    <li>Instalación de redes inalambricas para oficinas, bodegas de almacenamiento, colegios y universidades</li>
                </div>
        </div>
          <br>
          <div class="subservicios">
            <h3><strong> Alquiler de soluciones Wi-Fi </strong> </h3>
                <div>
                <li>Internet WiFi temporal para eventos</li>
                <li>Portal cautivo para redes WiFi de eventos</li>
                </div>
          </div>
      </div>
 
