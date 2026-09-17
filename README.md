# InspiraSTEM 2026 — Ciencia de Datos e Inteligencia Artificial Aplicada a Redes Eléctricas

## Resumen del taller

Este taller introduce la transformación de la red eléctrica y los desafíos asociados con la integración de energías renovables, vehículos eléctricos, centros de datos y otras tecnologías inteligentes. Los estudiantes conocerán cómo variables como el voltaje, la frecuencia y la potencia permiten evaluar el comportamiento dinámico del sistema, así como el papel de SCADA y las unidades de medición fasorial (PMU) en su monitoreo.

Mediante actividades grupales y prácticas en Google Colab, los participantes visualizarán series de tiempo, identificarán características de diferentes eventos eléctricos y analizarán el efecto del ruido en las mediciones. Posteriormente, utilizarán modelos básicos de aprendizaje automático para clasificar condiciones normales, disparos de generadores, cortocircuitos, incrementos de carga y pérdidas de carga.

Finalmente, aplicarán lo aprendido en un proyecto de análisis y clasificación de eventos, evaluando el desempeño y la confiabilidad de los resultados.

## Datos del workshop

| | |
|---|---|
| **Título** | Redes eléctricas inteligentes: mediciones, ciencia de datos e inteligencia artificial |
| **Fechas** | 19–21 de septiembre de 2026 |
| **Instructor** | Francisco Zelaya, Ph.D. |
| **Email** | [fzelaya223@gmail.com](mailto:fzelaya223@gmail.com) |
| **Afiliación** | Dominion Energy Virginia |
| **Bio** | Francisco es ingeniero eléctrico salvadoreño con un doctorado en Ingeniería Eléctrica por la Universidad de Tennessee, Knoxville. Actualmente trabaja como Senior Engineer en Dominion Energy, donde participa en iniciativas relacionadas con la integración de nuevas tecnologías y grandes cargas a la red eléctrica. Su experiencia profesional y de investigación incluye operación y dinámica de sistemas eléctricos, mediciones sincronizadas, ciencia de datos e inteligencia artificial aplicada al monitoreo y control de la red. Le interesa acercar estas herramientas a estudiantes y promover oportunidades de formación e innovación en STEM en El Salvador y Centroamérica. |
| **LinkedIn** | [www.linkedin.com/in/franciscozelaya](https://www.linkedin.com/in/franciscozelaya) |
| **Google Scholar** | [Perfil de Google Scholar](https://scholar.google.com/citations?user=PfaEoQEAAAAJ&hl=es) |

## Audiencia

El taller está dirigido a estudiantes de tercero a quinto año de Ingeniería Eléctrica, Ingeniería Energética, Ingeniería en Computación, Ingeniería de Software, Ciberseguridad, Ciencia de Datos y carreras afines.

## Requisitos previos

- Conocimientos básicos de ingeniería, matemáticas o programación.
- No se requiere experiencia previa en aprendizaje automático.
- No se requiere tener MATLAB ni Python instalados.
- Las actividades prácticas se realizarán mediante Google Colab.
- Se recomienda llevar una computadora con acceso a internet.

## Día 1 — Transformación de la red y mediciones inteligentes

### Meta

Comprender cómo está cambiando la red eléctrica, cuáles son los principales retos de esta transformación y cómo las mediciones permiten observar su comportamiento.

### Temas y actividades

- Funcionamiento básico de la red eléctrica.
- Diferencias entre una red eléctrica tradicional y una red inteligente.
- Integración de energías renovables, vehículos eléctricos, centros de datos y cargas inteligentes.
- Introducción a los recursos basados en inversores y sus diferencias respecto a las máquinas síncronas.
- Conceptos básicos de voltaje, frecuencia, estabilidad y confiabilidad.
- Retos asociados con la operación, los datos, las comunicaciones y la ciberseguridad.
- Introducción a los sistemas SCADA, PMU y mediciones sincronizadas.
- Uso de mediciones de voltaje, frecuencia y potencia para comprender el estado de la red.
- Actividades grupales para analizar los retos de la red inteligente y proponer posibles soluciones.
- Introducción a la aplicación de la ciencia de datos y la inteligencia artificial en sistemas eléctricos.

---

## Día 2 — Análisis de señales y clasificación de eventos eléctricos

### Meta

Utilizar mediciones de la red eléctrica para reconocer el comportamiento de diferentes eventos y entrenar modelos básicos de clasificación.

### Temas y actividades

- Introducción a Google Colab y al análisis de datos con Python.
- Carga, exploración y organización de series de tiempo.
- Visualización de señales de voltaje, frecuencia y potencia activa y reactiva.
- Comparación entre la operación normal y diferentes eventos eléctricos.
- Identificación manual de patrones y características relevantes en las señales.
- Cálculo de valores mínimos, máximos, cambios, tiempos y características de las oscilaciones.
- Análisis de los siguientes eventos:
  - Operación normal.
  - Disparo de generador.
  - Cortocircuito.
  - Incremento de carga.
  - Pérdida de carga.
- Introducción al ruido gaussiano y análisis de su efecto sobre las mediciones.
- Preparación y división de los datos para entrenamiento, validación y prueba.
- Entrenamiento y evaluación de modelos básicos de clasificación.
- Comparación del desempeño de los modelos utilizando señales limpias y señales con ruido.
- Interpretación de métricas de desempeño y matrices de confusión.
- Discusión sobre las capacidades y limitaciones de la inteligencia artificial en el monitoreo de la red.

---

## Día 3 — Proyecto: análisis inteligente de eventos eléctricos

### Meta

Aplicar herramientas de ciencia de datos e inteligencia artificial para analizar series de tiempo, clasificar eventos eléctricos y evaluar la confiabilidad de los resultados.

### Actividades

- Exploración de series de tiempo representativas de mediciones PMU.
- Aplicación de un modelo de clasificación temporal.
- Clasificación de condiciones normales y eventos eléctricos.
- Evaluación del desempeño del modelo bajo diferentes condiciones de medición.
- Análisis de predicciones incorrectas o de baja confianza.
- Generación de un reporte automático de eventos.
- Presentación de resultados y discusión de posibles aplicaciones en redes eléctricas inteligentes.

## Referencias

- [¿Qué es la red eléctrica?](https://www.youtube.com/watch?v=v1BMWczn7JM)
- [Unidades de medición fasorial (PMU)](https://share.google/K0mebZoAdvNJOvNHu)
- [Power System Simulator](https://github.com/PSSim/PSSim)
- [Introducción a Google Colab y Python](https://www.youtube.com/playlist?list=PLKd7y--oK26dWXHV0Aoi5eOgoikk3Fp-J)

## Aviso

Este taller fue desarrollado con fines educativos para InspiraSTEM 2026. Las opiniones y los materiales presentados son responsabilidad del instructor y no representan la posición de su empleador.
