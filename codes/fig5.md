Procesando el par de datos según el protocolo de validación y auditoría científica para la figura **`fig5.png`**.

---

## FASE 1: Mapeo de Entidades (Análisis)

A partir del fragmento de LaTeX proporcionado, se identifican las siguientes entidades y relaciones clave:

* **Sistemas en comparación:** Red Terrestre Pura (**Baseline TN**) frente a la Red Híbrida Terrestre-No Terrestre (**Híbrida TN-NTN**).
* **Variables de rendimiento (Métricas cuantitativas):**
* *Latencia:* Reducción de la latencia media de 42 ms (TN) a 18 ms (Híbrida), con un percentil 95 controlado en 68 ms (híbrida general) y <450 ms en escenarios de respaldo GEO selectivo.
* *Consumo Energético:* Reducción del 23% por bit (de 0.87 mJ/bit a 0.67 mJ/bit) debido a la disminución de retransmisiones.
* *Cobertura vs. Densidad:* Incremento de la probabilidad de cobertura de un 76.4% a un 97.8% por encima de -120 dBm, soportando densidades ultra-densas de hasta 1,200 dispositivos por $km^2$ (un 45% más que la baseline).


* **Dinámicas subyacentes:** Mecanismo de multi-conectividad contextual, conmutación proactiva (handover) ante *shadowing* e impacto del *overhead* de señalización en densidades críticas.

---

## FASE 2: Auditoría y Reporte de Hallazgos Críticos

### 1. Contraste de Coherencia y Lista de Discrepancias

Al contrastar el *Prompt de Imagen Base* con el rigor técnico del texto en LaTeX, se detectan las siguientes omisiones y contradicciones críticas:

* **Contradicción en la Paleta de Colores:** El prompt base solicita usar verde para la arquitectura híbrida, rompiendo la restricción estricta de usar solo la paleta técnica aprobada (Azul Cobalto `#0047AB` y Gris Técnico `#4A4A4A`). Se debe reasignar: **Azul Cobalto** para la propuesta Híbrida y **Gris Técnico** para la Baseline TN.
* **Falta de Hitos Críticos en (a) CDF de Latencia:** El texto destaca el percentil 95 ($P_{95}$) como un punto de comparación clave (185 ms vs. 68 ms). El prompt base no solicita marcar estos puntos, indispensables para validar la afirmación del texto.
* **Omisión de Unidades Específicas en (b) Consumo Energético:** El texto mide el consumo en "mJ/bit" (mili-julios por bit) y menciona el consumo acumulado. El gráfico de barras debe reflejar explícitamente estas unidades en el eje Y.
* **Falta del Límite de Saturación en (c) Cobertura vs. Densidad:** El texto menciona un punto de inflexión no lineal donde el *overhead* de señalización degrada el rendimiento más allá de los 1,200 disp/$km^2$. La curva debe reflejar visualmente esta caída o codo de saturación.
* **Infracción de Control de Estilo (Texto Incrustado):** El prompt base pide explícitamente *"sin texto incrustado dentro de la imagen"*, lo cual **viola la instrucción directa del protocolo** que exige *"inclusión de texto explicativo incrustado"* para asegurar el estándar de visualización científica IEEE.

---

## FASE 3: Explicación y Justificación de Pre-ejecución

### 1. Disposición Espacial y Elementos Gráficos

La figura se estructurará en tres paneles bidimensionales alineados horizontalmente (Subfiguras a, b y c), cumpliendo con el formato de ancho de columna completa de IEEE (`\linewidth`):

* **Panel (a) CDF de Latencia:**
* **Ejes:** X = Latencia (ms) [escala de 0 a 200]; Y = Probabilidad Acumulada $F(x)$ [0 a 1].
* **Trazos:** Curva gris (TN) desplazada a la derecha (mayor latencia, pendiente más suave). Curva azul (Híbrida) desplazada a la izquierda (menor latencia, pendiente pronunciada).
* **Líneas de Guía:** Líneas discontinuas finas en $Y = 0.95$ que cruzan horizontalmente para marcar de forma exacta los interceptos en $X = 68\text{ ms}$ (azul) y $X = 185\text{ ms}$ (gris).


* **Panel (b) Consumo Energético por Bit:**
* **Ejes:** X = Escenarios de Carga / Modos de Red; Y = Consumo de Energía Efectivo (mJ/bit) [escala de 0 a 1.0].
* **Barras:** Dos barras principales limpias: Barra Gris (Baseline TN = 0.87 mJ/bit) y Barra Azul (Híbrida = 0.67 mJ/bit). Una flecha de cota técnica unirá la cima de ambas barras indicando "$-23\%$ Eficiencia".


* **Panel (c) Cobertura vs. Densidad:**
* **Ejes:** X = Densidad de Dispositivos (disp/$km^2$) [escala de 0 a 2,000]; Y = Probabilidad de Cobertura ($>-120\text{ dBm}$) [0.5 a 1.0].
* **Trazos:** Línea azul (Híbrida) que se mantiene plana cerca del 97.8% hasta los 1,200 disp/$km^2$, donde empieza a curvarse hacia abajo debido al *overhead*. Línea gris (TN) que decae mucho antes (cerca de los 800 disp/$km^2$) desde su punto de partida en 76.4%. Una etiqueta de texto apuntará al umbral de los 1,200 disp/$km^2$.



### 2. Justificación Técnica

Esta composición es fiel a los datos del usuario porque utiliza los valores exactos tabulados y discutidos en el texto (97.8% de cobertura, 18 ms vs 42 ms de latencia, 0.67 vs 0.87 mJ/bit). Al plasmar el percentil 95 en la CDF y el punto de inflexión en el gráfico de densidad, la imagen deja de ser una ilustración genérica y se convierte en una evidencia visual directa de los modelos matemáticos descritos por el autor.

### 3. ADVERTENCIAS PARA EL USUARIO (Puntos de Validación)

Antes de proceder con la generación de los gráficos vectoriales, verifique los siguientes detalles de diseño:

1. **Representación del Respaldo GEO:** El texto menciona que el respaldo GEO selectivo mantiene la latencia bajo 450 ms en el percentil 95 para escenarios de contingencia extrema. Para mantener la claridad visual de la subfigura (a), se ha omitido la extensión del eje hasta 450 ms para no comprimir visualmente la zona crítica de 18-185 ms. Si prefiere un recuadro interno (*inset plot*) que muestre la cola de la distribución GEO, por favor indíquelo.
2. **Etiquetas de los Ejes:** Las etiquetas de texto explicativo incrustado se generarán en **idioma español** para mantener concordancia exacta con las secciones del artículo (`Latencia (ms)`, `Consumo por bit (mJ/bit)`, `Densidad de Dispositivos (disp/km²)`).

---

## FASE 4: Ejecución Silenciosa

> **Quedo a la espera de su confirmación o de cualquier ajuste en las advertencias mencionadas para proceder con la renderización técnica del diagrama vectorial.**