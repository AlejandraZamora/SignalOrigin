# SignalOrigin
# SignalPrototype
___

![Logo](https://github.com/AlejandraZamora/HealthImages/blob/master/imagenes/logo.png)![Logo ECI](https://github.com/AlejandraZamora/HealthImages/blob/master/imagenes/logoEscuela.jpg)

___

## Efficient and scalable Architecture for stream processing of health signals

## Aplicación desplegada:
 [Signal Protoype](https://signalprotoype.herokuapp.com)


## Guía para el desarrollador
___

## API REST

Tipo de datos manejado:  ***JSON***

### Recursos

El API ofrece el siguiente recurso principal:

- signal

Este se puede usar así:

### Componentes de los recursos

| Recurso | Topico | Descripción | Parametro | Retorno |
| :------ | :----- | :---------- | :-------- | :------ |
| `/signal/begin/{pId}` | `/signal/topic/signal` | Envia la señal al servidor. | **Long** | **DataPOJO** |

### Parametros de URL

| Nombre | Tipo | Descripción |
| :----- | :--- | :---------- |
| *pId* | **Long**| Número de identificación del paciente. |

_______

### Manual de descarga e instalación de la aplicación
_______

Para realizar el proceso es necesario contar previamente con:
- git ([descargar](https://git-scm.com/downloads))
- maven ([descargar](https://maven.apache.org/download.cgi))
- bower ([descargar](https://bower.io/#install-bower))
- Tener una cuenta activa en GitHub

_______

#### Descarga de la aplicación

Para descargar la aplicación siga estas instrucciones:

1. Abrir el repositorio de la aplicación en GitHub. [Signal Prototype](https://github.com/AlejandraZamora/SignalOrigin.git)

2. Copiar el enlace para clonar el proyecto

3. Abrir la terminal y ubicarse en el directorio en donde se desea guardar el proyecto con el comando cd:
	- cd Directorio deseado

4. Una vez ubicados en el directorio deseado procedemos a clonar el proyecto con el comando git clone y la dirección copiada anteriormente en la página del repositorio:
	- git clone https://github.com/AlejandraZamora/SignalOrigin.git

#### Ejecutar el proyecto de manera local

1. para poder ejecutar el proyecto vamos a utilizar el comando de maven para compilarlo y después de este el comando para correrlo:
	- mvn compile
	- mvn spring-boot:run
Debemos ubicarnos en el directorio del proyecto:
	- cd SignalPrototype/

2. Para probar el funcionamiento de la aplicación abrimos en el browser la dirección:
	- http://localhost:8080/app/index.html

3. Para detener el servidor volvemos a la terminal en la que se encuentra corriendo el proyecto y oprimimos ctrl+c lo que detendrá el proceso.
_______
