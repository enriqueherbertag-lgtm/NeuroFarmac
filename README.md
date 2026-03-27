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
