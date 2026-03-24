<img width="1977" height="495" alt="Portada" src="https://github.com/user-attachments/assets/47111c2b-8561-4e0b-bf35-42eeb09406aa" />

# N8N-Telegram
Flujo de trabajo simple para un bot de telegram

<img width="947" height="422" alt="image" src="https://github.com/user-attachments/assets/9aa0af1f-603f-48a3-a1ce-91ea8788ac36" />


# **Como funciona:**

Este flujo implementa un agente básico de Telegram que permite interactuar automáticamente con los usuarios mediante mensajes. El proceso comienza cuando el bot recibe un mensaje desde Telegram, el cual es capturado por el flujo para ser procesado. A continuación, el sistema interpreta el contenido del mensaje y genera una respuesta utilizando la lógica configurada en el workflow. Finalmente, el agente envía una respuesta al usuario directamente en el chat de Telegram. Este flujo permite crear asistentes simples, automatizar respuestas o construir interfaces conversacionales básicas integradas con otros servicios y automatizaciones.

# **Caracteristicas principales:**

1. Recepción automática de mensajes
2. Generación automática de respuestas
3. Interacción en tiempo real
4. Integración con automatizaciones

# **Paso a paso:**

1. Nodo Receive a Message

Este nodo se encarga de recibir los mensajes enviados por los usuarios al bot de Telegram.
Cada vez que un usuario interactúa con el bot, el flujo captura el mensaje y lo envía al siguiente paso para su procesamiento.

2. Nodo AI Agent

En este paso se utiliza un agente de inteligencia artificial para interpretar el mensaje recibido y generar una respuesta.

El agente está configurado con:

Simple Memory, que permite mantener contexto básico dentro de la conversación.

Chat Model de Gemini, encargado de procesar el mensaje y generar una respuesta adecuada para el usuario.

Esto permite crear interacciones conversacionales automáticas dentro de Telegram.

3. Nodo Send Message

Finalmente, el flujo envía la respuesta generada por el agente de IA al usuario en Telegram, completando el ciclo de interacción y permitiendo mantener una conversación automática con el bot.

# **Integracion de herramientas**

1. Telegram

# **Claves API necesarias**

1. Telegram 
