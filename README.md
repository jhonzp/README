# README
## ASPECTOS TÉCNICOS

<p align="center"><img src="https://siigonube.siigo.com/ISIIGO/Images/Portals/Siigo-Contador-Nube-Logo.png" width="250"></p>

#### Script de control para crear un SP que se usa para obtener las conexiones de los clientes.
####   
**Fecha**					31/07/2019
**Creado Por**				@SIIGO/GOME109070				
####  
**Actividad a Realizar**	Adicionar la siguiente configuración en app.config.json que se encuentra en assets/data de la aplicación Web:
  {
    "apiName": "WorkFlowService",
    "apiUrl": "http://localhost:8671/WorkFlow/api/",
    "version": "v1"
  }
STAGE

####  
**Tarea**					[4176](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4716)
**QA** 						[x]dev [x]stage []master
**ISIIGO2** 				[x]master
**ISIIGO3** 				[x]master
**DEMOS** 					[X]master
**DEMOSBASE** 				[X]master
**DIVULGACION ACADEMICA**	[X]master
**SENA**	 				[X]master
####  


#### Script de control para crear un SP que se usa para obtener las conexiones de los clientes.
#####_
**Fecha**					31/07/2019
**Creado Por**				@SIIGO/ZUNI230669				
####  
**Actividad a Realizar**	Ejecutar el script de control 01.01.80

####  
**Tarea**					[4176](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4716)
**QA** 						[x]dev [x]stage []master
**ISIIGO2** 				[x]master
**ISIIGO3** 				[x]master
**DEMOS** 					[ ]master
**DEMOSBASE** 				[ ]master
**DIVULGACION ACADEMICA**	[ ]master
**SENA**	 				[ ]master
####  


#### Propiedad en el DP para habilitar o deshabilitar funcionalidad de conexiones por companykey
####  
**Fecha**					31/07/2019
**Creado Por**				@SIIGO/zuni230669				
####  
**Actividad a Realizar**	(APLICA EN rama dev solamente de momento)
							En todos los web.config de ISIIGO, API, function en el objeto CloudDataProvider adicoinar esta propiedad
							<add name="CloudDataProvider" .......  HandleGUIDToConnections="False" />
							DEV
####  
**Tarea**					[4176](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4716)
**QA** 						[ ]dev [ ]stage []master
**ISIIGO2** 				[ ]master
**ISIIGO3** 				[ ]master
**DEMOS** 					[ ]master
**DEMOSBASE** 				[ ]master
**DIVULGACION ACADEMICA**	[ ]master
**SENA**	 				[ ]master
####  



#### Propiedad en el DP para habilitar o deshabilitar funcionalidad de conexiones por companykey
**Fecha					31/07/2019
**Creado Por**				@SIIGO/zuni230669				
####  
**Actividad a Realizar**	(APLICA EN rama dev solamente de momento)
							En todos los web.config de ISIIGO, API, function en el objeto CloudDataProvider adicoinar esta propiedad
							<add name="CloudDataProvider" .......  HandleGUIDToConnections="False" />
							DEV
####  
**Tarea**					[4176](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4716)
**QA** 						[ ]dev [ ]stage []master
**ISIIGO2** 				[ ]master
**ISIIGO3** 				[ ]master
**DEMOS** 					[ ]master
**DEMOSBASE** 				[ ]master
**DIVULGACION ACADEMICA**	[ ]master
**SENA**	 				[ ]master
####  


