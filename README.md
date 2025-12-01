# Trabajo Final - Evaluación de impacto

 ## 1. Objetivo y Alcance del Estudio

Este proyecto tiene como finalidad aplicar e integrar las competencias desarrolladas en el curso, combinando tres componentes centrales:

1) Construcción, depuración y estandarización de bases panel, incluyendo integración de múltiples fuentes y tratamiento de llaves municipales.
2) Modelación econométrica, implementando Propensity Score Matching (PSM) y Diferencias en Diferencias (DiD) para estimar los efectos del enfoque PDET sobre la evolución de la tasa de empresas turísticas en los municipios priorizados.
3) Resultados mediante la generación de tablas, visualizaciones y salidas reproducibles en formato R Markdown.

## 2. Contexto y Pregunta de Investigación

Los Programas de Desarrollo con Enfoque Territorial (PDET) surgieron tras el Acuerdo de Paz de 2016 con el propósito de transformar 170 municipios priorizados, históricamente marcados por el conflicto armado, la pobreza y la falta de presencia estatal. Buscan impulsar el desarrollo rural, la inclusión social y la construcción de paz mediante planes diseñados con la participación activa de las comunidades. Dentro de sus ocho pilares, el pilar 6: centrado en la reactivación económica y la producción agropecuaria, destaca el turismo como sector clave para diversificar la base productiva, dinamizar economías locales y contribuir a la construcción de paz.

El proyecto busca responder: *¿La focalización de municipios bajo los Programas de Desarrollo con Enfoque Territorial (PDET) ha tenido un efecto significativo sobre el desarrollo del turismo en contextos de posconflicto en Colombia?*

## 3. Datos
| **Fuente de datos**         | **Tipo de información**                                   | **Descripción**                                                                                                                                                           |
| --------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Consultora (Sector Turismo) | Variable dependiente: tasa de empresas turísticas activas | Bases de datos del sector turismo 2013–2024 con desagregación municipal para los municipios PDET.                                                                         |
| Panel Municipal CEDE        | Información municipal general                             | Presenta información sobre características generales de los municipios, variables fiscales, indicadores de conflicto y violencia, sector agrícola y tierras, y educación. |
| Ministerio de Turismo       | Estadísticas del sector turismo                           | Presenta un registro anual, desagregado por municipio, que recopila los indicadores más relevantes sobre estadísticas territoriales de turismo.                           |
| Censo DANE                  | Demografía poblacional                                    | Con base en el Censo General 2005, que elabora proyecciones demográficas nacionales, departamentales y municipales, se toman datos sobre población.                       |
| Estadística DANE            | Indicadores económicos                                    | Calcula indicadores del Valor Agregado por actividades económicas para cada municipio.                                                                                    |


## 4. Estructura del Repositorio y Componentes
El repositorio se encuentra organizado según el flujo analítico del proyecto:
| **Archivo / Carpeta**      | **Tipo de Componente**     | **Descripción Funcional**                                                                                                                                                                   |
| -------------------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Trabajo final.RMD`        | Código Fuente (R Markdown) | Contiene todo el pipeline: carga y limpieza de datos, estandarización de llaves, construcción del panel, matching PSM, estimación de modelos DiD y generación de tablas y gráficos finales. |
| `data/`                    | Datos Depurados            | Conjuntos de datos limpios y estandarizados exportados desde el RMD. Listos para análisis en R o uso externo.                                                                               |
| `Graficos - Tablas/`       | Resultados Intermedios     | Gráficos descriptivos, tablas de correlación, mapas y salidas de modelos generados durante el proceso.                                                                                      |
| `Propuesta/`               | Documento de Propuesta     | Contiene la propuesta inicial del trabajo, objetivos, motivación y lineamientos metodológicos.                                                                                              |
| `Documentos/`              | Informe Final              | Documento con revisión conceptual, metodología econométrica, resultados e interpretación.                                                                                                   |                                                                                           |

