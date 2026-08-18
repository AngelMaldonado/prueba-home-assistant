# Prueba técnica — Dispositivo IoT simulado con integración a Home Assistant

## Objetivo

Construir la simulación de un dispositivo IoT que corra localmente, exponga su propio servidor web y pueda ser controlado y monitoreado desde Home Assistant.

La prueba evalúa criterio técnico: el diseño del dispositivo, de su API y de la integración es parte de lo que se está calificando, por lo que las decisiones quedan en tus manos.

## Requerimientos

1. **Simulación del dispositivo**

   Un proceso que se ejecute en tu computadora y se comporte como un dispositivo IoT real: mantiene un estado interno, lo actualiza con el tiempo y responde a comandos. El tipo de dispositivo lo eliges tú (por ejemplo un termostato, un foco, un sensor ambiental, una cerradura, etc.).

2. **Servidor web propio**

   El dispositivo debe levantar su propio servidor web y exponer una interfaz para consultar su estado y operarlo. Piensa en cómo lo haría un dispositivo comercial que vive en la red local.

3. **Integración con Home Assistant**

   El dispositivo debe aparecer en Home Assistant como una o más entidades, reflejar su estado en tiempo razonable y poder controlarse desde la interfaz de Home Assistant. Existe más de un camino válido para lograrlo; elige uno y justifica por qué.

## Entregables

- El código fuente del dispositivo simulado y de la integración.
- Instrucciones para levantar todo desde cero (dependencias, comandos, configuración de Home Assistant).
- Un documento breve donde expliques tu arquitectura, las decisiones de diseño que tomaste y los trade-offs que consideraste.
- Evidencia de que funciona: capturas o un video corto del dispositivo operando desde Home Assistant.

## Consideraciones

- Puedes usar el lenguaje, framework y herramientas que prefieras.
- Puedes correr Home Assistant como prefieras (Docker, entorno virtual, instalación nativa).
- El uso de librerías y de herramientas de IA está permitido; se espera que puedas explicar y defender cada parte del código que entregues.
- Si algo del enunciado te parece ambiguo, documenta el supuesto que tomaste y continúa.

## Qué se evalúa

- Que funcione de extremo a extremo y sea fácil de levantar siguiendo tus instrucciones.
- La calidad del diseño: separación de responsabilidades, manejo de errores y de estado, claridad del código.
- El realismo de la simulación y de la integración frente a cómo se comporta un dispositivo real.
- La claridad con la que comunicas y justificas tus decisiones.

## Alcance sugerido

Entre 4 y 8 horas de trabajo. Preferimos un alcance acotado y bien resuelto sobre uno amplio e incompleto; si dejas cosas fuera, anótalas como trabajo pendiente.
