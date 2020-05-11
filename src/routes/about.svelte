<svelte:head>
	<title>About</title>
</svelte:head>


<style>
    .certificaciones {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 8px;
        text-align: center;
		align-items: center;
    }

	caption {
		align-items: center;
		text-align: center;
	}
	figure {
		align-items: center;
		text-align: center;
	}	
	img {
		width: 100px;
		height: 100px;
		border-radius: 100px;
		margin-right: 20px;
	}

</style>

<h1>Hola, Soy César Alexander Gómez</h1>
<div>
	<strong>¿Quien soy?</strong>
		<p>Soy consultor de redes wireless, con mas de 12 años de experiencia en telecomunicaciones, desarrollador full stack junior. </p>
		<strong>Trayectoria</strong>
	<p> 
		<li>
		Ingeniero preventa Senior
		</li> 
		<li>
		Gerente de producto tecnico
		</li> 
		<li>
		Gerente de diseño y desarrollo de soluciones
		</li> 
		<li>
		Arquitecto de soluciones de RF
		</li> 
		<li>
		Instructor Sena
		</li> 
		<li>
		Jefe de conectividad
		</li> 
		<li>
		Ingeniero de Aprovisionamiento y Backbone
		</li> 
	</p>
	<strong>Certificaciones</strong>
	<div>
		<div class="certificaciones">
    		<figure>
				<caption>CWNA</caption>
     		   	<img src="https://www.cwnp.com/uploads/cwna_c.png" alt="CWNA">
    		</figure>
			<figure>
				<caption>CWSP</caption>
        		<img src="https://www.cwnp.com/uploads/cwsp_c.png" alt="CWSP">
    		</figure>
			<figure>
				<caption>CWDP</caption>
        		<img src="https://www.cwnp.com/uploads/cwdp_c.png" alt="CWDP">
    		</figure>
		</div>
	</div>
</div>
