# Arquitectura de Microservicios con Java y Spring 🚀

Este proyecto implementa una arquitectura de microservicios utilizando tecnologías basadas en Java y Spring.

## Descripción

La arquitectura consta de cinco microservicios, cada uno con su propia responsabilidad y funcionalidad:

- **Eureka**: Servidor de registro y descubrimiento para facilitar la comunicación dinámica entre microservicios.
- **Config**: Gestiona la configuración externa de la aplicación.
- **Gateway**: Punto de entrada único para los clientes, proporcionando enrutamiento de solicitudes y funciones adicionales.
- **Orders**: Gestiona operaciones relacionadas con pedidos.
- **Clients**: Gestiona operaciones relacionadas con clientes.

## Estructura del Proyecto

El repositorio está organizado de la siguiente manera:

- `eureka-service/`: Código fuente del microservicio Eureka.
- `config-service/`: Código fuente del microservicio Config.
- `gateway-service/`: Código fuente del microservicio Gateway.
- `orders-service/`: Código fuente del microservicio Orders.
- `clients-service/`: Código fuente del microservicio Clients.

Cada directorio contiene el código fuente y los archivos de configuración específicos de cada microservicio.

## Uso

1. Clona este repositorio en tu máquina local.
2. Abre cada microservicio en tu IDE favorito.
3. Ejecuta cada microservicio en tu entorno local.
4. ¡Explora la arquitectura de microservicios y realiza pruebas! 
