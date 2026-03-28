# NeuroFarmac: Plataforma Integrada de Neurofarmacología en un Chip

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

**Sistema in vitro para evaluación de fármacos cerebrales con barrera hematoencefálica funcional y monitoreo electrofisiológico en tiempo real.**

NeuroFarmac integra organoides cerebrales humanos 3D, una barrera hematoencefálica (BHE) funcional y arreglos de microelectrodos (MEA) para evaluar la eficacia y neurotoxicidad de fármacos con relevancia fisiológica.

---

## Problema que Resuelve

- **Modelos actuales:** Pruebas en células 2D no predicen respuesta en cerebro humano; modelos animales son costosos, éticamente complejos y a menudo no trasladables.
- **Barrera hematoencefálica:** La mayoría de los fármacos candidatos no alcanzan el cerebro porque no se evalúa su capacidad de cruzar la BHE.
- **Monitoreo funcional:** Las pruebas tradicionales miden muerte celular, no modificaciones en la actividad de redes neuronales (que es lo que determina eficacia en enfermedades neurológicas).

**NeuroFarmac permite evaluar en un solo sistema:** cruce de BHE, interacción con tejido cerebral, y modulación de actividad neuronal en tiempo real.

---

## Arquitectura (Tres Capas Integradas)

| Capa | Función | Especificación |
|------|---------|----------------|
| **1. Interfaz Vascular** | Simula flujo sanguíneo, sostiene co-cultivo de células de BHE | Microfluidos con flujo pulsátil (0.5–5 µL/min), endotelio + pericitos + astrocitos |
| **2. Tejido Neural** | Sustrato biológico de prueba | Organoide cerebral humano 3D (células madre pluripotentes), 2–4 mm diámetro, 6–12 meses maduración |
| **3. Lectura Electrofisiológica** | Monitoreo en tiempo real | MEA de alta densidad (256 electrodos, 20 µm espaciado), muestreo >20 kHz, impedancia <1 MΩ |

---

## Principio de Operación


Fármaco en flujo → Cruce de BHE → Interacción con organoide → Lectura en MEA → Análisis de datos


El sistema permite evaluar:
- **Permeabilidad de BHE:** ¿Qué fracción del fármaco llega al compartimiento cerebral?
- **Efecto sobre actividad neuronal:** ¿Aumenta? ¿Disminuye? ¿Desincroniza?
- **Toxicidad funcional:** ¿La red neuronal colapsa? ¿Hay recuperación?

---

## Especificaciones Técnicas

### Microfluidos (Capa Vascular)

| Parámetro | Valor |
|-----------|-------|
| Flujo | Pulsátil, 0.5–5 µL/min (ajustable) |
| Material | PDMS (polidimetilsiloxano) o vidrio grabado |
| Canales | 100–200 µm ancho, 50–100 µm alto |
| Células BHE | Endotelio (hCMEC/D3), pericitos, astrocitos (co-cultivo) |
| Temperatura | 37°C |
| CO₂ | 5% |

### Organoide Cerebral

| Parámetro | Valor |
|-----------|-------|
| Origen | Células madre pluripotentes inducidas (iPSC) |
| Diámetro | 2–4 mm (maduro) |
| Tiempo de maduración | 6–12 meses |
| Control de calidad | Inmunocitoquímica para marcadores neuronales, astrocíticos y de progenitores |

### Arreglo de Microelectrodos (MEA)

| Parámetro | Valor |
|-----------|-------|
| Número de electrodos | 256–1024 |
| Espaciado | 20–50 µm |
| Impedancia | <1 MΩ (a 1 kHz) |
| Frecuencia de muestreo | >20 kHz |
| Amplificación | ×1000–×5000 |

---

## Validación Científica

Basado en estudios revisados por pares:

- **Organoides cerebrales:** Lancaster, M.A., & Knoblich, J.A. (2014). *Generation of cerebral organoids from human pluripotent stem cells*. Nature Protocols, 9(10), 2329–2340.
- **BHE en chip:** Bang, S., et al. (2021). *A microphysiological system for the evaluation of drug delivery across the blood-brain barrier*. Lab on a Chip, 21(12), 2386–2397.
- **MEA para redes neuronales:** Obien, M.E.J., et al. (2015). *Revealing neuronal function through microelectrode array recordings*. Frontiers in Neuroscience, 8, 423.

---

## Estado actual

✅ Concepto arquitectónico definido  
✅ Especificaciones técnicas preliminares  
✅ Validación científica documentada  
🔲 Diseño detallado del chip microfluídico  
🔲 Protocolos de cultivo de organoides estandarizados  
🔲 Integración con sistema MEA comercial o propio  
🔲 Software de análisis de señales  
🔲 Validación con fármacos de referencia

---

## Próximos pasos

1. **Diseño del chip** — Esquemáticos en FreeCAD/CAD para microfluidos.
2. **Protocolos de cultivo** — Estandarizar generación de organoides cerebrales.
3. **Integración MEA** — Seleccionar sistema comercial o desarrollar interfaz propia.
4. **Pruebas de concepto** — Validar con fármacos de permeabilidad conocida (ej. cafeína vs. anticuerpos).

---

## Proyectos relacionados

- **DeepSeek Research Tools** — herramientas de IA para investigación científica  
  [Repositorio](https://github.com/enriqueherbertag-lgtm/deepseek-research-tools)
- **ENA** — interfaz cerebro-máquina no invasiva  
  [Repositorio](https://github.com/enriqueherbertag-lgtm/ENA-Enlace-Neural-Avatar)
- **CORPUS** — sistema corporal artificial para IA  
  [Repositorio](https://github.com/enriqueherbertag-lgtm/Corpus)

---

## Licencia

**CC BY-NC 4.0 (Attribution-NonCommercial 4.0 International)**

Este proyecto está liberado bajo una licencia Creative Commons que permite:
- ✅ Compartir y modificar
- ✅ Uso personal, investigación, prototipos
- ❌ **No permite uso comercial sin autorización expresa**

**¿Quieres usar este diseño comercialmente?**  
Contacta para una licencia comercial: **eaguayo@migst.cl**

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## Autor

**Enrique Aguayo H.**  
Investigador independiente, Mackiber Labs  
Contacto: eaguayo@migst.cl  
ORCID: 0009-0004-4615-6825  
GitHub: [@enriqueherbertag-lgtm](https://github.com/enriqueherbertag-lgtm)
