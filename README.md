# Semillero_Ejercicio_Sesion_5



## Como vimos el día de hoy, iniciamos creando nuestro primer micro servicio basico. El objetivo es que contienuen implementando el crud para que se puedan registrar, actualziar, consultar y eliminar usuarios en nuestra aplicación.

## Adjunto les envio el proyecto para que contiuen configurando la conexión a la base de datos, documentando con swagger los servicios y haciendo las pruebas con Postman.

## Esta es una guia de lo que deben hacer para que todos puedan cumplir con el ejercicio. Continuamos mañana.

* https://spring.io/guides/gs/accessing-data-mysql/

### El proyecto que cada uno actualice, deberan subirlo en una nueva carpeta en sus repositorio compartido, solo deberan dejarlo hasta lo que se pidio el día de hoy.

CREATE TABLE `usuario` (
  `ID` int NOT NULL AUTO_INCREMENT,
  `NOMBRE` varchar(100) NOT NULL,
  `LOGIN` varchar(200) NOT NULL,
  `PASSWORD` varchar(50) NOT NULL,
  `ESTADO` varchar(20) NOT NULL,
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci COMMENT='Esta tabla almacena la información de los usuarios.'
