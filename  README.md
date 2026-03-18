# NeuroFarmac: Plataforma Integrada de Neurofarmacología en un Chip

**Propiedad Intelectual - Concepto en Desarrollo**

> Un marco para un sistema *in vitro* que integra organoides cerebrales, una barrera hematoencefálica funcional y arreglos de microelectrodos (MEA) para la evaluación en tiempo real de fármacos.

## Visión

Crear un puente funcional entre los avances en organoides cerebrales 3D y la necesidad crítica de la industria farmacéutica de evaluar la **eficacia y neurotoxicidad real de los fármacos**, incluyendo su capacidad para cruzar la barrera hematoencefálica y modular la actividad de redes neuronales.

## Arquitectura Conceptual (Las Tres Capas Integradas)

1. **Capa de Entrada/Interfaz Vascular:** Sistema de microfluidos que simula un flujo sanguíneo pulsátil y sostiene un co-cultivo de células de la **Barrera Hematoencefálica (BHE)**.
2. **Capa de Tejido Neural:** **Organoide cerebral humano** 3D, derivado de células madre, que sirve como sustrato biológico de prueba.
3. **Capa de Lectura/Output:** **Arreglo de Microelectrodos (MEA)** de alta densidad que monitorea en tiempo real la **actividad electrofisiológica espaciotemporal** de la red neuronal en respuesta a los estímulos.

## Principio de Operación

El sistema permite un experimento cíclico cerrado:

`Fármaco en flujo → Cruce de la BHE → Interacción con el organoide → Lectura de actividad en MEA → Análisis de datos`

Esta integración permite no solo preguntar *"¿El fármaco mata las células?"*, sino *"¿Cómo modula el fármaco la dinámica y conectividad de una red neuronal realista, y a qué concentración accesible?"*.

## Estructura de Este Repositorio (Preliminar)

- `/device-designs` - Esquemáticos y planos para el chip de microfluidos y la interfaz MEA.
- `/analysis-software` - Código para el procesamiento de señales del MEA y análisis de datos.
- `/cell-protocols` - Protocolos para la generación de organoides y cultivo de células BHE.
- `/references` - Artículos clave y literatura de fondo.

*(Nota: Las carpetas y su contenido son ilustrativas y estarán sujetas a desarrollo futuro.)*

## Estado y Licencia

- **Estado Actual:** Este repositorio se encuentra en **fase de conceptualización y diseño inicial**.
- **Propiedad Intelectual:** El concepto arquitectónico integral de **NeuroFarmac** es propiedad intelectual de su autor.
- **Licencia:** Por definir. Probablemente seguirá un modelo de licencia dual similar a OsteoFlux/RizoRhythm (Apache con restricción comercial para código, CC BY-NC-ND para documentación).

## Autor

**Enrique Aguayo H.**  
Investigador independiente.  
Contacto: eaguayo@migst.cl | ORCID: 0009-0004-4615-6825

---

*"La mejor prueba para un fármaco cerebral no es si se une a un receptor, sino cómo modula la conversación de la red."*
