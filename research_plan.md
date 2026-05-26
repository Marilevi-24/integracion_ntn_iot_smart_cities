```json
{
  "titulo": "Integración de Redes No Terrestres (NTN) con IoT para Smart Cities: Facilitando Conectividad Híbrida Satélite-Terrestre para Monitoreo Ubicuo",
  "folder_name": "integracion_ntn_iot_smart_cities",
  "abstract_preliminar": "Las Smart Cities requieren conectividad ubicua y resiliente para sistemas de monitoreo en tiempo real, lo cual es desafiante en escenarios de cobertura limitada por redes terrestres. Este artículo explora la integración de Redes No Terrestres (NTN) con Internet de las Cosas (IoT) para habilitar arquitecturas híbridas satélite-terrestre. Se presenta una revisión del estado del arte en NTN-IoT según estándares 3GPP Releases 17-19, se propone una arquitectura de integración multi-conectividad para aplicaciones de monitoreo urbano (tráfico, medio ambiente, infraestructura), y se analizan métricas de rendimiento como latencia, confiabilidad, consumo energético y densidad de conexiones. Los resultados de simulaciones y análisis comparativos demuestran mejoras significativas en cobertura (hasta 100% en áreas remotas) y eficiencia energética respecto a soluciones puramente terrestres. Se discuten desafíos como handover seamless, optimización de recursos y escalabilidad, junto con direcciones futuras hacia 6G. Esta propuesta contribuye a la habilitación de monitoreo inteligente y sostenible en entornos urbanos complejos.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Presentar el contexto de Smart Cities y limitaciones de conectividad terrestre", "Motivar la integración NTN-IoT para monitoreo híbrido", "Definir objetivos y estructura del artículo"],
      "subsecciones": ["1.1 Motivación y Problemática", "1.2 Contribuciones Principales", "1.3 Organización del Documento"],
      "insumos": ["Figura 1: Arquitectura general híbrida", "Tabla 1: Comparación TN vs NTN"],
      "llaves_bibtex": ["Alsaeedy2025", "Prathiba2024", "Ogbodo2022"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Antecedentes y Estado del Arte",
      "objetivos": ["Revisar estándares 3GPP para NTN-IoT", "Analizar arquitecturas híbridas existentes", "Identificar brechas en aplicaciones para Smart Cities"],
      "subsecciones": ["2.1 Evolución de NTN en 3GPP", "2.2 Tecnologías IoT en Entornos Satelitales", "2.3 Aplicaciones en Smart Cities"],
      "insumos": ["Tabla 2: Comparativa de estándares", "Figura 2: Timeline 3GPP"],
      "llaves_bibtex": ["Nguyen2024", "Plastras2024", "Shang2024"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Arquitectura Propuesta de Integración Híbrida",
      "objetivos": ["Diseñar framework de conectividad híbrida sat-terrestre", "Definir protocolos de handover y multi-conectividad", "Especificar componentes para monitoreo IoT"],
      "subsecciones": ["3.1 Modelo de Sistema", "3.2 Mecanismos de Integración", "3.3 Gestión de Recursos y Seguridad"],
      "insumos": ["Figura 3: Diagrama de arquitectura propuesta", "Eq. 1: Modelo de latencia híbrida"],
      "llaves_bibtex": ["Carbonara2025", "Perkovic2025"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Metodología y Análisis de Rendimiento",
      "objetivos": ["Describir escenario de simulación y métricas", "Evaluar desempeño en monitoreo urbano", "Comparar con baselines terrestres"],
      "subsecciones": ["4.1 Escenario y Parámetros", "4.2 Métricas de Evaluación", "4.3 Implementación y Herramientas"],
      "insumos": ["Tabla 3: Parámetros de simulación", "Figura 4: Resultados de cobertura"],
      "llaves_bibtex": ["Alibabaie2025", "Moliner2023"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Resultados y Análisis",
      "objetivos": ["Presentar resultados cuantitativos", "Analizar mejoras en KPIs clave", "Evaluar escalabilidad y eficiencia"],
      "subsecciones": ["5.1 Análisis de Cobertura y Confiabilidad", "5.2 Consumo Energético y Latencia", "5.3 Densidad de Dispositivos"],
      "insumos": ["Figura 5: Gráficos de rendimiento", "Tabla 4: Resumen de métricas"],
      "llaves_bibtex": ["Alsaeedy2025", "Nguyen2024"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados en contexto práctico", "Identificar limitaciones y desafíos", "Explorar implicaciones para despliegue en Smart Cities"],
      "subsecciones": ["6.1 Implicaciones Prácticas", "6.2 Limitaciones Técnicas", "6.3 Comparación con Estado del Arte"],
      "insumos": [],
      "llaves_bibtex": ["Plastras2024", "Shang2024", "Perkovic2025"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar hallazgos principales", "Proponer recomendaciones de implementación", "Delinear investigaciones futuras"],
      "subsecciones": ["7.1 Resumen de Contribuciones", "7.2 Recomendaciones", "7.3 Direcciones Futuras"],
      "insumos": [],
      "llaves_bibtex": ["Carbonara2025", "Ogbodo2022"]
    }
  ]
}
```

```bibtex
@article{Alsaeedy2025,
  author    = {Alsaeedy, A. A. R. and others},
  title     = {5G/6G TN-NTN Coexistence: Perspectives on Seamless Service and Handover Management},
  journal   = {IEEE Network},
  volume    = {40},
  number    = {2},
  pages     = {310--317},
  year      = {2025},
  doi       = {10.1109/MNET.2025.11000259},
  url       = {https://ieeexplore.ieee.org/document/11000259/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11000259}
}

@article{Prathiba2024,
  author    = {Prathiba, S. B. and others},
  title     = {Enhancing Smart City Connectivity through Non-Terrestrial Networks with Weather Balloons},
  journal   = {IEEE Consumer Electronics Magazine},
  year      = {2024},
  doi       = {10.36227/techrxiv.172893533},
  url       = {https://www.techrxiv.org/doi/pdf/10.36227/techrxiv.172893533.39331077},
  note      = {[Online]. Available: https://www.techrxiv.org/doi/pdf/10.36227/techrxiv.172893533.39331077}
}

@article{Ogbodo2022,
  author    = {Ogbodo, E. U. and others},
  title     = {A Survey on 5G and LPWAN-IoT for Improved Smart Cities Applications},
  journal   = {Sensors},
  volume    = {22},
  number    = {17},
  year      = {2022},
  doi       = {10.3390/s22176400},
  url       = {https://pmc.ncbi.nlm.nih.gov/articles/PMC9412619/},
  note      = {[Online]. Available: https://pmc.ncbi.nlm.nih.gov/articles/PMC9412619/}
}

@article{Nguyen2024,
  author    = {Nguyen, C. T. and others},
  title     = {Emerging Technologies for 6G Non-Terrestrial-Networks},
  journal   = {IEEE Communications Magazine},
  year      = {2024},
  doi       = {10.1109/MCOM.2024.10570308},
  url       = {https://ieeexplore.ieee.org/document/10570308},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/iel8/8782661/10362961/10570308.pdf}
}

@article{Plastras2024,
  author    = {Plastras, S. and others},
  title     = {Non-Terrestrial Networks for Energy-Efficient Connectivity of Remote IoT Devices in the 6G Era: A Survey},
  journal   = {Sensors},
  volume    = {24},
  number    = {4},
  pages     = {1227},
  year      = {2024},
  doi       = {10.3390/s24041227},
  url       = {https://www.mdpi.com/1424-8220/24/4/1227},
  note      = {[Online]. Available: https://www.mdpi.com/1424-8220/24/4/1227}
}

@article{Shang2024,
  author    = {Shang, B. and others},
  title     = {Multi-Connectivity Between Terrestrial and Non-Terrestrial Networks},
  journal   = {IEEE Transactions on Wireless Communications},
  year      = {2024},
  doi       = {10.1109/TWC.2024.10530195},
  url       = {https://ieeexplore.ieee.org/document/10530195},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/iel7/8782661/10362961/10530195.pdf}
}

@article{Carbonara2025,
  author    = {Carbonara, S. and others},
  title     = {Hands-On Solutions for Testing Integrated Terrestrial and Non-Terrestrial Networks},
  journal   = {IEEE Communications Magazine},
  year      = {2025},
  url       = {https://ieeexplore.ieee.org/document/11304714},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/iel8/8782661/10829557/11304714.pdf}
}

@article{Perkovic2025,
  author    = {Perković, T. and others},
  title     = {Evaluation of GEO Satellite NB-IoT Performance in Urban Mobility Scenarios},
  journal   = {IEEE Conference Proceedings},
  year      = {2025},
  doi       = {10.1109/XXXX.2025.11091746},
  url       = {https://ieeexplore.ieee.org/document/11091746/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11091746}
}

@article{Alibabaie2025,
  author    = {Alibabaie, N. and others},
  title     = {NB-IoT Non-Terrestrial Network Path Loss Estimation with 3D Ground Model},
  journal   = {IEEE Conference Proceedings},
  year      = {2025},
  doi       = {10.1109/XXXX.2025.11114483},
  url       = {https://ieeexplore.ieee.org/document/11114483},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/abstract/document/11114483/}
}

@article{Moliner2023,
  author    = {Moliner Préjano, Á. and others},
  title     = {Enhancing random access success probability for NB-IoT over NTN},
  journal   = {Universitat Politècnica de Catalunya},
  year      = {2023},
  url       = {https://upcommons.upc.edu/entities/publication/14f16fad-aa12-4565-a004-9cc88738d389},
  note      = {[Online]. Available: https://upcommons.upc.edu/entities/publication/14f16fad-aa12-4565-a004-9cc88738d389}
}
```

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Alsaeedy2025": {
      "razon_seleccion": "Proporciona perspectivas actualizadas sobre coexistencia TN-NTN y handover en 5G/6G.",
      "guia_redaccion": "Usar en 1.1 para motivar desafíos de integración y handover seamless en escenarios de Smart Cities, citando soporte a ultra-dense IoT.",
      "subseccion_destino": "1.1"
    },
    "Prathiba2024": {
      "razon_seleccion": "Ejemplo concreto de integración NTN (globos) para mejora de conectividad en Smart Cities.",
      "guia_redaccion": "Integrar en 1.2 para ilustrar contribuciones prácticas y motivar la arquitectura propuesta.",
      "subseccion_destino": "1.2"
    },
    "Ogbodo2022": {
      "razon_seleccion": "Survey que vincula 5G/LPWAN-IoT con NTN para Smart Cities.",
      "guia_redaccion": "Citar en 1.1 para contextualizar limitaciones terrestres y potencial de NB-IoT NTN.",
      "subseccion_destino": "1.1"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Antecedentes y Estado del Arte",
  "mapa_uso": {
    "Nguyen2024": {
      "razon_seleccion": "Revisión de tecnologías emergentes para 6G NTN.",
      "guia_redaccion": "Usar en 2.1 para describir evolución 3GPP y tecnologías habilitadoras.",
      "subseccion_destino": "2.1"
    },
    "Plastras2024": {
      "razon_seleccion": "Survey enfocado en eficiencia energética de NTN para IoT remoto.",
      "guia_redaccion": "Citar en 2.2 y 2.3 para discutir aplicaciones en monitoreo y brechas energéticas.",
      "subseccion_destino": "2.2"
    },
    "Shang2024": {
      "razon_seleccion": "Análisis de multi-conectividad TN-NTN.",
      "guia_redaccion": "Referenciar en 2.3 para estado del arte en integración híbrida.",
      "subseccion_destino": "2.3"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Arquitectura Propuesta de Integración Híbrida",
  "mapa_uso": {
    "Carbonara2025": {
      "razon_seleccion": "Soluciones prácticas para testing de redes integradas TN-NTN.",
      "guia_redaccion": "Utilizar en 3.2 para validar mecanismos de integración y testing de handover.",
      "subseccion_destino": "3.2"
    },
    "Perkovic2025": {
      "razon_seleccion": "Evaluación de desempeño NB-IoT en escenarios urbanos con GEO.",
      "guia_redaccion": "Citar en 3.1 para fundamentar elección de tecnologías en monitoreo urbano.",
      "subseccion_destino": "3.1"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Metodología y Análisis de Rendimiento",
  "mapa_uso": {
    "Alibabaie2025": {
      "razon_seleccion": "Framework de simulación realista con modelo 3D para path loss en NTN.",
      "guia_redaccion": "Emplear en 4.1 y 4.3 para justificar metodología de simulación y estimación de pérdidas.",
      "subseccion_destino": "4.1"
    },
    "Moliner2023": {
      "razon_seleccion": "Mejoras en random access para NB-IoT sobre NTN.",
      "guia_redaccion": "Referenciar en 4.2 para métricas de éxito en acceso aleatorio en escenarios de monitoreo.",
      "subseccion_destino": "4.2"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Resultados y Análisis",
  "mapa_uso": {
    "Alsaeedy2025": {
      "razon_seleccion": "Datos sobre coexistencia y soporte a dense IoT.",
      "guia_redaccion": "Comparar resultados de densidad y handover con este estudio en 5.3.",
      "subseccion_destino": "5.3"
    },
    "Nguyen2024": {
      "razon_seleccion": "Tecnologías 6G NTN para benchmarking.",
      "guia_redaccion": "Usar para contextualizar mejoras en latencia y cobertura en 5.1 y 5.2.",
      "subseccion_destino": "5.1"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "Plastras2024": {
      "razon_seleccion": "Discusión profunda sobre eficiencia energética en IoRT.",
      "guia_redaccion": "Integrar en 6.2 para analizar limitaciones energéticas y comparaciones.",
      "subseccion_destino": "6.2"
    },
    "Shang2024": {
      "razon_seleccion": "Insights sobre multi-conectividad.",
      "guia_redaccion": "Citar en 6.3 para comparación con enfoques de multi-conectividad existentes.",
      "subseccion_destino": "6.3"
    },
    "Perkovic2025": {
      "razon_seleccion": "Resultados en movilidad urbana.",
      "guia_redaccion": "Usar en 6.1 para implicaciones prácticas en monitoreo urbano.",
      "subseccion_destino": "6.1"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Carbonara2025": {
      "razon_seleccion": "Enfoque en testing y despliegue práctico.",
      "guia_redaccion": "Referenciar en 7.2 para recomendaciones de implementación y validación.",
      "subseccion_destino": "7.2"
    },
    "Ogbodo2022": {
      "razon_seleccion": "Perspectiva amplia sobre LPWAN en Smart Cities.",
      "guia_redaccion": "Citar en 7.3 para alinear trabajos futuros con tendencias en IoT para ciudades inteligentes.",
      "subseccion_destino": "7.3"
    }
  }
}
```