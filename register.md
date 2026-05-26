```markdown
* **Title**: Integración de Redes No Terrestres (NTN) con IoT para Smart Cities: Facilitando Conectividad Híbrida Satélite-Terrestre para Monitoreo Ubicuo

* **Description**: El proyecto investiga y propone una arquitectura de integración híbrida entre redes terrestres (TN) y no terrestres (NTN) para habilitar conectividad ubicua y resiliente en Smart Cities. Se enfoca en aplicaciones de monitoreo IoT en tiempo real (tráfico, medio ambiente e infraestructura), combinando estándares 3GPP Releases 17-19 con mecanismos de multi-conectividad, handover contextual y orquestación inteligente. Mediante simulaciones de alta fidelidad se validan mejoras en cobertura, latencia, confiabilidad y eficiencia energética frente a soluciones puramente terrestres.

* **General Objective**: Desarrollar y evaluar una arquitectura híbrida TN-NTN que facilite la conectividad ubicua y resiliente para sistemas de monitoreo IoT en entornos de Smart Cities.

* **Specific Objectives**: 
  - Revisar el estado del arte en estándares 3GPP y tecnologías NTN-IoT aplicadas a entornos urbanos.
  - Diseñar un framework de integración multi-conectividad con mecanismos de handover seamless y gestión contextual de recursos.
  - Implementar un escenario de simulación realista en área urbana y evaluar el desempeño en KPIs clave (cobertura, latencia, consumo energético y densidad de dispositivos).
  - Analizar limitaciones técnicas y proponer recomendaciones prácticas para despliegue junto con líneas de investigación futura.

* **Justification**: Las redes terrestres actuales presentan limitaciones significativas de cobertura y resiliencia en entornos urbanos complejos, especialmente ante congestión, obstrucciones o fallos masivos. La integración TN-NTN representa una solución estratégica para lograr monitoreo inteligente y sostenible en Smart Cities, contribuyendo a la eficiencia operativa urbana, la sostenibilidad ambiental y la resiliencia ante desastres. Esta investigación alinea con la evolución hacia 6G y responde a necesidades reales de conectividad ubicua en ciudades modernas.

* **Methodology**: Se emplea una metodología mixta que combina revisión sistemática del estado del arte, diseño de arquitectura propuesta, modelado analítico y extensas simulaciones basadas en NS-3, MATLAB y Python. Se utiliza modelado de propagación 3D urbano para path loss, análisis Monte Carlo (500 réplicas) y comparación con baselines terrestres. La evaluación se centra en métricas cuantitativas orientadas a aplicaciones reales de monitoreo IoT.

* **Scope**: Desarrollo y validación mediante simulación de una arquitectura híbrida TN-NTN para monitoreo IoT en un escenario urbano de 25 km² con 15.000 dispositivos.

* **Activities**: 
  - Revisión bibliográfica y análisis de estándares 3GPP.
  - Diseño detallado de la arquitectura y mecanismos de integración.
  - Implementación del escenario de simulación y definición de KPIs.
  - Ejecución de experimentos y análisis de resultados.
  - Discusión de implicaciones, limitaciones y direcciones futuras.

* **Resources**: Simuladores NS-3 (módulos NTN), MATLAB (propagación 3D), Python (análisis estadístico), modelos 3D de entornos urbanos, acceso a literatura científica IEEE y 3GPP, servidores de computación para simulaciones Monte Carlo.

* **Limitations**: Los resultados se basan principalmente en simulaciones (aunque de alta fidelidad); falta validación en campo a gran escala. Dependencia de suposiciones sobre constelaciones satelitales y condiciones de propagación. Posibles variaciones en rendimiento real derivadas de factores regulatorios, disponibilidad de espectro y costos de despliegue satelital.
```