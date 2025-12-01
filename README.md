# Trabajo Final - Evaluación de impacto

 ## 1. Objetivo y Alcance del Estudio

Este proyecto tiene como finalidad aplicar e integrar las competencias desarrolladas en el curso, combinando tres componentes centrales:

1) Construcción, depuración y estandarización de bases panel, incluyendo integración de múltiples fuentes y tratamiento de llaves municipales.
2) Modelación econométrica, implementando Propensity Score Matching (PSM) y Diferencias en Diferencias (DiD) para estimar los efectos del enfoque PDET sobre la evolución de la tasa de empresas turísticas en los municipios priorizados.
3) Comunicación analítica y estructuración de resultados, mediante la generación de tablas, visualizaciones y salidas reproducibles en formato R Markdown.

## 2. Contexto y Pregunta de Investigación

Los Programas de Desarrollo con Enfoque Territorial (PDET) surgieron tras el Acuerdo de Paz de 2016 con el propósito de transformar 170 municipios priorizados, históricamente marcados por el conflicto armado, la pobreza y la falta de presencia estatal. Buscan impulsar el desarrollo rural, la inclusión social y la construcción de paz mediante planes diseñados con la participación activa de las comunidades. Dentro de sus ocho pilares, el pilar 6: centrado en la reactivación económica y la producción agropecuaria, destaca el turismo como sector clave para diversificar la base productiva, dinamizar economías locales y contribuir a la construcción de paz.

El proyecto busca responder: ¿La focalización de municipios bajo los Programas de Desarrollo con Enfoque Territorial (PDET) ha tenido un efecto significativo sobre el desarrollo del turismo en contextos de posconflicto en Colombia? 

## 3. Estructura del Repositorio y Componentes

El repositorio se encuentra organizado según el flujo analítico del proyecto:

Archivo / Carpeta	Tipo de Componente	Descripción Funcional
Trabajo final.RMD	Código Fuente (R Markdown)	Contiene todo el pipeline: carga y limpieza de datos, estandarización de llaves, construcción de panel, matching PSM, estimación de modelos DiD y generación de tablas y gráficos finales.
data/	Datos Depurados	Conjuntos de datos limpios y estandarizados exportados desde el RMD. Listos para análisis en R o uso externo.
Graficos - Tablas/	Resultados Intermedios	Gráficos descriptivos, tablas de correlación, mapas y salidas de modelos generados durante el proceso.
Documentos/	Informe Final	Documento con revisión conceptual, metodología econométrica, resultados e interpretación.
psm_outputs/ (si aplica)	Diagnósticos PSM	Love plots, balance y matrices de pareo utilizados para validar el matching.
