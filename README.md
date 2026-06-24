# Orbital CAD™
Versión: 0.2.0<br>
Estado: en desarrollo.<br>
Resultados: funcionando.<br>

___

> [!NOTE]
> A continuación estarán los motores encargados del procesamiento, 
análisis y preservación multimedia en Aethra.<br>
<br>

_Orbital CAD_ es responsable de analizar la estructura del archivo multimedia (stream),<br>
procesarlo con los protocolos correctos según su códec/contenedor, y posteriormente<br>
verificar la integridad y preservarlo.<br>

Garantiza la mayor fidelidad posible.

___

<details>
<summary><strong>Orbital CAD</strong></summary>

| Binario | Versión | Función |
|---|---|---|
| `orbital-flac` | v2.3.1 | Validación MD5 e integridad FLAC + MQA |
| `orbital-joc` | v1.4.0 | Análisis Dolby Atmos — JOC, OAMD, objetos (E-AC-3, AC-4) |
| `orbital-remux` | v1.3.0 | Remux FLAC/M4A |
| `orbital-meta` | v1.0.0 | Escritura de metadata (M4A, AAC, FLAC) |
| `orbital-probe` | v2.0.0 | Inspección de códec, sample rate, canales |

- Añadido soporte de formatos abandonados por TIDAL: MQA, 360 RA.

___

Aethra™, NX Orbital™, Lyra™, Orbital CAD™, Oria™ are part of an ecosystem software developed by BDEV.
