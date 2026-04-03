# Pruebas - NeuroFarmac

Esta carpeta contiene los protocolos de validación del sistema.

## Contenido planificado

- `bhe_permeability_test.md` — protocolo para medir permeabilidad de la BHE.
- `organoid_viability_test.md` — protocolo para verificar viabilidad del organoide.
- `mea_calibration.md` — calibración del arreglo de microelectrodos.
- `drug_validation.md` — validación con fármacos de referencia (cafeína vs. anticuerpos).

## Protocolos de prueba

| Prueba | Descripción | Criterio de aceptación |
|--------|-------------|------------------------|
| Permeabilidad BHE | Medir paso de molécula fluorescente | Coeficiente de permeabilidad conocido |
| Viabilidad del organoide | Inmunocitoquímica + actividad eléctrica | Marcadores neuronales presentes, actividad espontánea |
| Ruido del MEA | Medir impedancia y ruido de fondo | Impedancia <1 MΩ, ruido <10 µV |
| Fármaco de referencia | Cafeína (cruza BHE) vs. anticuerpo (no cruza) | Señal detectable solo con cafeína |

## Estado

- Protocolos definidos.
- Pruebas pendientes de ejecución.
