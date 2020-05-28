# bancadigital_bd
Reto de programación: Recuperar mi usuario de la banca digital

## Tier Datos
## Pasos para la instalación

Tener git instalado. 


Clonar el repositorio. Ejecutar `git clone https://github.com/Irving1596/bancadigital_bd.git` 

Situarse en el directorio `bancadigital_bd` 

!!!Antes de ejecutar el siguiente paso asegurese de que los puertos `4200, 3200 y 3306` estes disponibles y no los este utilizando algun proceso!!! 

Ejecutar `docker-compose up` Esta instruccion levantara los servicios.

Esperar unos segundo hasta que todos los servicios esten arriba,  luego de que esten arriba navegar a `http://localhost:4200/login`  

Datos
| Cedula|Pasaporte | Pin |
| ------------- | ------------- |
| 1234567890 | 1234  |
| 1111122222 | 1111 |

Tambien con el endpoint http://localhost:3200/cliente_recovery puede listar los usuarios almacenados en la BD

# Documentación
## Justificación de herramientas  

`Web Tier:  Angular` ideal framework frontend capaz de convertir los proyectos desarrollados en PWA,tambien incluye diversar librerias de estilos como Angular Material Design ,proporciona trancisiones y animaciones y pues claro también esta su independencia con el backend.

`App tier: Node.js` es una excelente tecnología para utilizar del lado del backend es liviano, eficiente y asíncrono.

`Data tier: Mysql` es un SGBD relacional sencillo fácil de usar e instalar. En sus últimas release (8.0) ha mejorado en cuanto a rendimiento y features se refiere. 

## IDE utilizado

`Visual Code` super ligero y con una gran variedad de extensiones útiles a la hora de programar.

## Proporciones las instrucciones detalladas para instalar la aplicación en un computador
Configuración recomendada de espacio en disco disponible, memoria RAM y capacidad del procesador 
Específicaciones minímas
- `Disco:  500 GB o 128 SSD`
- `Memoria: Ram: 2 GB `
- `Procesador: 1 nucleo intel core i3`

 Configuraciones especiales como variables de entorno del sistema: `null`.
 Cambios en archivos de configuración de la propia aplicación: `null`.
Instalación de aplicaciones de terceros, por ejemplo: el motor de base de datos o el lenguaje
Programas requerido:
- `Docker 19.03`
- `Angular 9`
- `NPM 6.14.5`
- `Express `
- `Node.js 13`
- `Mysql 8.0.20`

## Base de Datos 
- `El script SQL DDL esta en el repositorio`

- `Diagrama de entidad y relación`

<img src="https://github.com/Irving1596/bancadigital_bd/blob/master/MER.png" width="320">

## Tablero Trello
- https://trello.com/b/zTL2SlF0 