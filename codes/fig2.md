## FASE 1: Mapeo de Entidades (Análisis)

A partir del fragmento en LaTeX proporcionado, se identifican las siguientes entidades clave, relaciones y niveles de abstracción para la construcción del diagrama técnico (`fig2.png`):

* **Entidades Temporales (Evolución 3GPP):**
* **Rel-15/16:** Origen exploratorio (estudios iniciales).
* **Rel-17:** Hito fundacional (Soporte nativo NB-IoT/eMTC, pre-compensación Doppler, *Extended Timing Advance*, payloads transparentes, órbitas GEO/LEO).
* **Rel-18:** Fase de consolidación (Mejoras de rendimiento, movilidad optimizada, introducción inicial de HAPS y payloads regenerativos).
* **Rel-19:** Frontera tecnológica (Arquitecturas regenerativas avanzadas, funcionalidad *Store & Forward* para IoT, *Seamless Handover* TN-NTN, integración multi-capa/multi-layer).


* **Entidades de Arquitectura y Topología:**
* Segmento Terrestre (TN): Dispositivos IoT (NB-IoT/eMTC), torres de telefonía convencional.
* Segmento No Terrestre (NTN): Satélites LEO, Satélites GEO, y plataformas HAPS.


* **Relaciones Críticas:**
* **Continuum de Conectividad / Multi-conectividad:** Interacción híbrida e inteligente entre TN y NTN (MIMO híbrido, cobertura complementaria para *Smart Cities* y entornos remotos).
* **Trade-offs Técnicos:** Relación entre el tipo de órbita (LEO/GEO) y el impacto en consumo energético, latencia variable y handovers.



---

## FASE 2: Auditoría y Reporte de Hallazgos Críticos

### 1. Contraste de Coherencia

El prompt de imagen base captura la estructura cronológica lineal (Releases 15 a 19), pero simplifica en exceso la riqueza técnica y arquitectónica descrita en el texto de los antecedentes y en la Tabla 1. Al omitir elementos de infraestructura híbrida y dinámicas de red, la figura corre el riesgo de ser un *timeline* genérico en lugar de un esquema de arquitectura aeroespacial y de telecomunicaciones para IEEE.

### 2. Lista de Discrepancias (Explícita)

* **Omitido en el Prompt Base (Hito Rel-17):** Falta la mención explícita al *Extended Timing Advance*, crucial junto a la compensación Doppler.
* **Omitido en el Prompt Base (Hito Rel-18):** No se incluye la incorporación de plataformas **HAPS** (High Altitude Platform Stations), elemento clave de la evolución física de la red en esa release.
* **Omitido en el Prompt Base (Hito Rel-19):** Se ignora la transición hacia el **Seamless TN-NTN Handover** y la **Multi-layer Integration** (integración multi-capa).
* **Conflicto de Estilo Crítico (Texto Incrustado):** El prompt base solicita *"Sin texto incrustado dentro de la imagen"*. Esto viola directamente la instrucción de diseño técnico IEEE y tus requisitos, que exigen la **inclusión de texto explicativo incrustado** (etiquetas de texto técnico, valores de bandas o acrónimos) para que el diagrama sea autoexplicativo.

### 3. Control de Estilo

* **Paleta de Colores:** Estricta aplicación de Azul Cobalto (`#0047AB`) para elementos NTN/Satélites y líneas de datos principales; Gris Técnico (`#4A4A4A`) para el segmento terrestre, ejes y bloques secundarios; Negro puro (`#000000`) para tipografías vectoriales y flechas de flujo. Fondo blanco puro (`#FFFFFF`).
* **Estándar:** Formato vectorial 2D, plano (flat design), sin gradientes ni sombras. Tipografía limpia (Sans-serif o Arial equivalente) para el texto explicativo incrustado.

---

## FASE 3: Explicación y Justificación de Pre-ejecución

### 1. Disposición Espacial

El diagrama se estructurará mediante una **matriz híbrida de Evolución Temporal y Arquitectura de Capas**:

* **Eje Horizontal (Cronológico):** De izquierda a derecha, bloques segmentados para Rel-15/16, Rel-17, Rel-18 y Rel-19.
* **Eje Vertical (Capas de Red):** * *Capa Superior (Espacial/Aérea - NTN):* Ubicación de iconos GEO (Rel-17), LEO (Rel-17/18) y HAPS (Rel-18/19).
* *Capa Inferior (Terrestre - TN):* Dispositivos IoT, entornos de *Smart Cities* y torres de celdas.


* **Flechas de Flujo:** Flechas negras sólidas e indexadas conectarán los hitos cronológicos en la parte superior. Flechas bidireccionales en azul cobalto conectarán los satélites con el segmento terrestre, ensanchándose o duplicándose en la Rel-19 para denotar el *MIMO Híbrido* y la *Multi-layer Integration*.

### 2. Justificación Técnica

* **Visualización de Payloads (Transparente vs. Regenerativo):** En Rel-17 se representará el satélite como un espejo de retransmisión (*Transparent Payload*), mientras que en Rel-19 se incluirá un bloque interno de procesamiento de datos en el icono del satélite (*Regenerative* + bloque de memoria para *Store & Forward*).
* **Continuum TN-NTN:** El área de Rel-19 mostrará una superposición geométrica (línea punteada gris y azul) que encapsula la torre terrestre y el satélite, justificando visualmente el concepto de *Seamless TN-NTN Handover* analizado por Shang et al.

### 3. Advertencias para el Usuario (Validación)

> ⚠️ **Puntos de Validación Requeridos:**
> 1. **Densidad de Texto:** Para mantener el estándar IEEE, incrustaré etiquetas técnicas precisas (ej: *"Doppler Comp."*, *"Extended TA"*, *"Store & Forward"*). Confirma si prefieres acrónimos estándar o el término expandido completo.
> 2. **Complejidad Gráfica de HAPS:** En Rel-18, HAPS se representará como un dirigible/aerostato simplificado en 2D. Asegura si este vector es adecuado o si prefieres mantener solo nodos circulares abstractos.
> 
> 

---

## FASE 4: Ejecución Silenciosa

Por favor, revisa la auditoría, la disposición propuesta y las advertencias. Una vez que apruebes estos criterios o indiques tus preferencias, procederé con la generación silenciosa del prompt de imagen optimizado y definitivo para `fig2.png`. ¿Deseas realizar algún cambio antes de comenzar?