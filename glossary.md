# Glosary

## SOA architecture

* Es auto-contenida (self-contained).

* Es una caja negra para sus consumidores

* Representa una actividad de negocio con un fin específico.

## Web Services

* La manera en la que se implementan las arquitecturas SOA.


### SOAP standard

* Utiliza XML

* Provee un protocolo de mensajería muy claro.

### RESTful HTTP

* El objetivo es que las aplicaciones no afecten a otras directamente.

* Depende fuertemente del protocolo HTTP.

### GraphQL

* Funciona como un _query language_ para las API.

## The twelve-factor app

### Codebase

* Uso de control de versiones.

* Una sola fuente (dev, prod, etc).

### Dependencies

* Dependencias __explícitamente__ declaradas e isoladas.

* Se puede usar por medio de __virtualenv__ o __docker__.

### Configuration

* Almacena la configuración como variables de entorno.

### Backing services

* Pueden conectarse/desconectarse a voluntad.

* Cualquier servicio que la aplicación pueda consumir através de la red (Ej: bd, mensajería, envío de emails, caché).

### Build, release, run

* Separa _estrictamente_ las etapas de construcción y las de ejecución.

### Processes

* Ejecuta la app como uno o más procesos sin estado.

### Dev/Prod parity

* Reducir la diferencia entre entornos.

* Reducir tiempos entre deploys.

### Admin processes

* Tratar los procesos administrativos como algo completamente diferente de la app (Ej. Limpiar datos).

### Other

* Port binding
* Concurrency
* Disposability
* Logs

## Docker!

* No necesita un 'Guest OS'.

* Usa muy poca memoria.

* Fácil de replicar y controlar.

* Fácil de compartir.
