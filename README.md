# Guia Azure 

**Tipos de nubes**
- Nube hibrida (CAPEX:Gastos de equipo) 
- Nube privada (OPEX:Gastos de operacion)

![](imagenes/índice.jpg)

**Nube privada**
- uso exclusivo de los usuarios o empresas

**Nube publica**
- son empresas privadas que ofrecen los servicios a quien sea

**nube hibrida**
- entorno que combina una nube publica con una nube privada lo que permite
- compartir datos y aplicaciones entre ellas
 
**La nube es elastica**
- los recursos se pueden autoescalar dependiendo de las necesidades actuales
- actual. siempre tienes los recursos necesarios

**Nivel de servicio**
- porcentaje de disponiblidad y rendimiento de los recursos durante un tiempo determinado

**Compute**
- proporciona capacidad de procesamiento

**Network**
- proporciona servicios de red que premiten conectar

**storage** 
- proporciona almacenamiento

**Base de datos**
--proporciona base de datos para una amplia variedad de tipos y volumenes de datos

**Lot**
- proporciona servicios de lot para conectar y recibir informacion de sensores

**Big data**
- proporciona servicios para el procesamiento y analisis de grandes cantidades de registros

**DevOps**
- ayuda a los equipos de desarrollo de software a automatizar y hacer eficientes sus procesos

**Un registro va a pedir**

- nombre de la aplicacion 
- suscripcion
- grupo de recursos
- localizacion

**Creacion de maquina virtuales**
- az group create --name practica-redes-ia --location centralus

az vn create \
- --resource-group practica-redes-ia \
- --location centralus \
- --name vm-practica-redes-ia \
- --image UbuntuLTS \
- --admin-username josejesusguzman \
- --generate-ssh-keys

- copiar ip publica

- az network public-ip list --resource-group practica-redes-ia --querys[].ipAddress

- ssh josedejesusguzman@40.86.100.245

- sudo apt-get moo
