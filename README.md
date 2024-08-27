# Node.js Payment Services

Este repositorio contiene un servidor desarrollado en Node.js que integra y gestiona tres procesadores de pago distintos. El servidor está diseñado para recibir y manejar las notificaciones de los webhooks provenientes de estos procesadores de pago, facilitando la integración con otras aplicaciones y servicios.

## Características

- **Integración de Procesadores de Pago:** Soporta tres procesadores de pago diferentes, permitiendo la gestión y el procesamiento de transacciones desde múltiples fuentes.
- **Manejo de Webhooks:** Recibe y procesa notificaciones de eventos desde los procesadores de pago, asegurando que otras aplicaciones puedan reaccionar en tiempo real a eventos de pago.
- **Notificaciones:** Envía actualizaciones a aplicaciones y sistemas externos basados en los eventos recibidos de los webhooks.
- **Escalabilidad y Mantenimiento:** Diseñado con una arquitectura modular que facilita la adición de nuevos procesadores de pago o la modificación de los existentes sin afectar el funcionamiento general.

## Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone <url-del-repositorio>
2. Navega al directorio del proyecto:
   ```bash
   cd <nombre-del-repositorio>
3. Instala las dependencias:
   ```bash
   npm install
4. Configura las variables de entorno necesarias para cada procesador de pago y para las notificaciones de webhooks.
5. Inicia el servidor:
   ```bash
   npm start
   
