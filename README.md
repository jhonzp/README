## README
# ASPECTOS TÉCNICOS

<p align="center"><img src="https://www.siigo.com/wp-content/uploads/2019/05/Logo-Siigo.png" width="150"></p>


### Script de control para crear un SP que se usa para obtener las conexiones de los clientes.
- **Fecha**			    31/07/2019
- **Tarea**				[4176](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4716)
- **Creado Por**		JHON ZUÑIGA
### Actividad a Realizar
Ejecutar el script de control 01.01.80
### Despliegues
- **QA** 			              
  - [x] dev
  - [x] stage 
  - [ ] master
- **ISIIGO2**
  - [x] master
- **ISIIGO3**
  - [x] master
- **DEMOS**
  - [x] master
- **DEMOSBASE**
  - [x] master
- **DIVULGACION ACADEMICA**
  - [x] master
- **SENA**
  - [x] master
### FIN


### Setting en el DataProvider 
- **Fecha**			    31/07/2019
- **Tarea**				[4176](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4716)
- **Creado Por**		JHON ZUÑIGA
### Actividad a Realizar
(APLICA EN rama dev solamente de momento)
En todos los web.config de ISIIGO, API, function en el objeto CloudDataProvider adicoinar esta propiedad
<add name="CloudDataProvider" .......  HandleGUIDToConnections="False" />
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN


### copiado de templates
- **Fecha**			    06/08/2019
- **Tarea**				
- **Creado Por**		Ivan Corchuelo
### Actividad a Realizar
Copiar archivo PayrollBankConfig10524.json, PayrollBankConfig99998.json y SettlementStub.xsl a templates DEV
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN


### Setting en el Market 
- **Fecha**			    13/08/2019
- **Tarea**				[4586](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/4586)
- **Creado Por**		David Penagos
### Actividad a Realizar
Cambiar la siguiente key en el market     

<!--RegularExpression para campos Email. Se usa la expresión regular de https://haacked.com/archive/2007/08/21/i-knew-how-to-validate-an-email-address-until-i.aspx/ 
      ,se modifica para que permita mayúsculas, con esta expresión se evita crear usuarios que tengan vocales con tildes y los siguientes caracteres ¬"()\¡¿¨´[]:,;<> -->

<add key="RegularExpression_Email" value="^(?!\.)(&quot;([^&quot;\r\\]|\\[&quot;\r\\])*&quot;|([-a-zA-Z0-9!#$%&amp;'*+/=?^_`{|}~]|(?&lt;!\.)\.)*)(?&lt;!\.)@[a-zA-Z0-9][\w\.-]*[a-zA-Z0-9]\.[a-zA-Z][a-zA-Z\.]*[a-zA-Z]$" />
### Despliegues
- **QA** 			              
  - [ ] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN


### configurar api.config.json 
- **Fecha**			    17/08/2019
- **Tarea**				
- **Creado Por**		David Penagos
### Actividad a Realizar
Configurar en el api.config.json el api de aprovisionamiento de FE

    {
    "apiName": "eSiigoACGeneralService",
    "apiUrl": "https://esiigogeneralservicev3.azurewebsites.net/api/",
    "version": "v1"
  }
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN

### Copiar Templates 
- **Fecha**			    19/08/2019
- **Tarea**				[2806](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/2806)
- **Creado Por**		Manuel Salazar
### Actividad a Realizar
Copiar en la carpeta Layout: 
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasic.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasic2.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasic2HalfLetter.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasic2HalfLetterPDF.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasicAuto.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasicHalfLetter.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasicHalfLetterPDF.xsl
\CloudFramework\General.Web\Layout\Template\ERPDocInvoiceBasicPeriod.xsl
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN

### Setting ACEntryService 
- **Fecha**			    19/08/2019
- **Tarea**				[6830](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/6830)
- **Creado Por**		Juan Carlos Guarin
### Actividad a Realizar
Adicionar la siguiente key al Web.config de BPM.Service.ACEntryService
<add key="eSiigoBillingAPIURLv3" value="https://esiigobillingservicev3.azurewebsites.net/api/"/>
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN

### Setting ACEntryService 
- **Fecha**			    19/08/2019
- **Tarea**				[6830](https://dev.azure.com/SiigoDevOps/Siigo/_workitems/edit/6830)
- **Creado Por**		Juan Carlos Guarin
### Actividad a Realizar
Adicionar la siguiente key al Web.config de BPM.Service.ACEntryService
<add key="eSiigoBillingAPIURLv3" value="https://esiigobillingservicev3.azurewebsites.net/api/"/>
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN

### Configuraciones ElectronicInvoice 
- **Fecha**			    21/08/2019
- **Tarea**				
- **Creado Por**		Andres Ruiz
### Actividad a Realizar
Configurar API ElectronicInvoice en STAGE, se debe configurar conexion de REDIS, BD, y ServerPriority 

Ajustar  rutas de apis de a ambiente de stage. 
 <add key="CloudAuthenticationAPI" value="http://co076nt35:8681/CloudAuthentication/api/" />
 <add key="ACDocumentAPI" value="http://co076nt35:8681/ACDocument/api/v1/" />
 <add key="ACGeneralAPI" value="http://co076nt35:8681/ACGeneral/api/v1/" />
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN

### Copiar templates 
- **Fecha**			    22/08/2019
- **Tarea**				
- **Creado Por**		Ivan corchuelo
### Actividad a Realizar
Copiar archivo PayrollBankConfig10524.json a templates DEV
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN

### Nuevo archivo en el proceso (fix)
- **Fecha**			    23/08/2019
- **Tarea**				
- **Creado Por**		Andres Ruiz
### Actividad a Realizar
Es necesario ajustar al atualizar 

Ajustar  rutas de apis de a ambiente de stage. 
 <add key="CloudAuthenticationAPI" value="http://co076nt35:8681/CloudAuthentication/api/" />
 <add key="ACDocumentAPI" value="http://co076nt35:8681/ACDocument/api/v1/" />
 <add key="ACGeneralAPI" value="http://co076nt35:8681/ACGeneral/api/v1/" />
### Despliegues
- **QA** 			              
  - [x] dev
  - [ ] stage 
  - [ ] master
- **ISIIGO2**
  - [ ] master
- **ISIIGO3**
  - [ ] master
- **DEMOS**
  - [ ] master
- **DEMOSBASE**
  - [ ] master
- **DIVULGACION ACADEMICA**
  - [ ] master
- **SENA**
  - [ ] master
### FIN