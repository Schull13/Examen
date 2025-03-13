# Examen de Configuración de Red

Este es un examen práctico que documenta la configuración de routers, switches y PCs para establecer una red funcional. A continuación se detallan las configuraciones, conexiones y el estado actual del proyecto.

## Configuración de los Routers

![Comandos desde terminal](./imagenes/examen1.png)

Se utilizó la configuración mostrada en la imagen para cada router. Cada router se conecta a través de una red **Clase A** usando una conexión **WAN** y está conectado a los routers de manera **serial** para garantizar que las conexiones entre ellos sean posibles.

## Conexión entre Routers, Switches y PCs

![Comandos desde terminal](./imagenes/examen2.png)

En esta imagen, se muestra la conexión entre los **routers**, **switches** y **PCs**. Cada dispositivo está configurado para poder comunicarse entre sí, lo que permite una red funcional.

## Conexión de los Routers a los Switches

![Comandos desde terminal](./imagenes/examen3.png)

Aquí se puede ver cómo se conecta cada **router** a un **switch** para usar las interfaces **FastEthernet**. Esta conexión es similar para todos los switches, cambiando las direcciones según sea necesario para que las conexiones funcionen correctamente.

## Configuración Estática de las PCs

![Comandos desde terminal](./imagenes/examen4.png)

En esta sección se observa la configuración estática de las direcciones IP para cada una de las **PCs**, asegurando que puedan comunicarse correctamente y transferir archivos entre ellas. Sin embargo, a pesar de la configuración correcta, actualmente las PCs no pueden realizar un **ping** entre ellas.

## Problema y Solución Pendiente

A pesar de que la configuración parece correcta, las PCs no pueden hacer **ping** entre ellas. Esto indica que hay algún problema en la comunicación entre los dispositivos de la red. Se necesita revisar y solucionar este problema para que las PCs puedan intercambiar archivos correctamente.

### Tareas pendientes:
- Verificar la conectividad entre las PCs y los routers.
- Revisión de las tablas de enrutamiento.
- Asegurar que las direcciones IP y las máscaras de subred estén configuradas correctamente.
- Solucionar cualquier posible conflicto de configuración o de hardware.

