<style>

  h1{
      color: #0F4C75;
  }

  h3 {
      color:#3282b8; 
  }

.container-services{
  display:flex;
  flex-wrap: wrap;
}

.subservicios{
  width: 400px;
  justify-content: space-around;
  /* border: 1px solid #0F4C75; */
  padding: 10px;
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

<h1><strong> NuestrosServicios </strong></h1>
<br>
<br>
      <div class="container-services">
          <div class="subservicios">
            <img  src="consultoria.png" alt="wlan_Assessment"/>
            <div>
            <h3><strong> Consultoria de WLAN</strong> </h3>
            <h4>Se realiza una auditoria de la actual WLAN y se generan recomendaciones, usualmente con un nuevo diseño.  </h4>
            </div>
          </div>
          <div class="subservicios">
            <img  src="diseno.png" alt="diseño"/>
            <h3><strong>  Diseño de WLAN </strong> </h3>
                <div>
                <h4>Diseñamos las redes Wi-Fi para obtener una excelente experiencia de usuario segun las buenas practicas de los fabricantes. </h4>
                </div>
          </div>
          <div class="subservicios">
            <img  src="survey.png" alt="site_survey"/>
            <h3><strong> Estudios de sitio (Site Surveys)</strong> </h3>
                <div>
                <h4>Realizamos estudios de sitio para redes tanto internas (indoor) como de exteriores (outdoor).</h4>
                </div>
          </div>
          <div class="subservicios">
            <img  src="tshoot.png" alt="tshoot"/>
            <h3><strong> Solución de problemas (Troubleshooting) </strong> </h3>
                <div>
                <h4>Usamos herramientas especializadas para solucionar cualquier problema relacioando con las redes WI-Fi. </h4>
                </div>
          </div>
          <div class="subservicios">
            <img  src="WiFi.png" alt="alquiler"/>
            <h3><strong> Alquiler de soluciones Wi-Fi </strong> </h3>
                <div>
                <h4>Proveemos la infraestructura de red necesaria para cualquier tipo de evento.</h4>
                </div>
          </div>
          <div class="subservicios">
            <img  src="implementacion.png" alt="implementacion"/>
            <h3><strong>  Servicios de instalación </strong> </h3>
                <div>
                <h4>Instalación de redes inalambricas para oficinas, bodegas de almacenamiento, colegios y universidades.</h4>
                </div>
          </div>
      </div>
 
