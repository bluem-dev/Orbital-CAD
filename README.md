# Orbital CAD™
Versión: ?.?.?<br>
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
| `orbital-flac` | v2.3.0 | Validación MD5 e integridad FLAC |
| `orbital-joc` | v1.4.0 | Análisis Dolby Atmos — JOC, OAMD, objetos |
| `orbital-remux` | v1.1.0 | Remux FLAC/M4A |
| `orbital-meta` | — | Escritura de metadata (M4A, FLAC) |
| `orbital-probe` | v1.1.0 | Inspección de códec, sample rate, canales |

</details>

<details>
<summary><strong>Orbital CAD ++</strong></summary>

| Binario | Versión | Función |
|---|---|---|
| `orbital-ac4-probe` | — | Inspección de códec, sample rate, canales, atmos |
| `orbital-ac4-decoder` | — | Dec & Play > AC-4 Dolby Atmos |

</details>

___

Aethra™, NX Orbital™, Lyra™, Orbital CAD™, Oria™ are part of an ecosystem software developed by BDEV.

Copyright © 2026 BDEV. All rights reserved.
