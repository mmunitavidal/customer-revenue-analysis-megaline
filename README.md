Customer Revenue & Plan Performance Analysis (Telecom)
Descripción del proyecto

Este proyecto analiza el comportamiento de consumo y los ingresos generados por clientes de una empresa de telecomunicaciones (Megaline).

El objetivo es evaluar el desempeño de los planes tarifarios y determinar cuál genera mayor rentabilidad, replicando un escenario real de Marketing Analytics y análisis de revenue.

Objetivo
-  Calcular el ingreso mensual por usuario.
- Analizar el consumo promedio de llamadas, SMS e internet.
- Comparar la rentabilidad entre planes.
- Evaluar diferencias estadísticas entre grupos de clientes.
- Proponer recomendaciones estratégicas basadas en datos.

Contexto de negocio

La empresa Megaline ofrece dos planes de telefonía móvil.
La dirección necesita entender:

¿Qué plan genera mayores ingresos?

¿Existen diferencias significativas entre tipos de clientes?

¿Se están cubriendo los costos incluidos en cada plan?

¿Hay oportunidades de optimización de pricing?

Herramientas y librerías:
- Python
- pandas
- numpy
- matplotlib
- scipy (pruebas estadísticas)

Metodología:
1) Limpieza y validación de datos.
2) Consolidación del consumo mensual por usuario.
3) Cálculo del ingreso mensual considerando:
- Llamadas excedentes
- SMS excedentes
- Datos móviles adicionales
4) Análisis comparativo entre planes.
5) Pruebas de hipótesis para evaluar diferencias significativas.
6) Interpretación estratégica de resultados.

Resultados principales:

- Se identificaron diferencias claras en patrones de consumo entre planes.
- Uno de los planes mostró mayor ingreso promedio mensual.
- Se detectaron usuarios que superan sistemáticamente los límites incluidos.
- Las pruebas estadísticas permitieron validar si las diferencias eran significativas.

Conclusión
El análisis permitió determinar cuál plan genera mayor rentabilidad y cómo se comportan los clientes frente a los límites de consumo.

Se recomienda:
- Ajustar estrategia de precios según perfil de usuario.
- Evaluar optimización del plan menos rentable.
- Implementar segmentación basada en consumo para mejorar ingresos.

Estructura del repositorio:
├── notebooks/
│   └── Proyecto_Sprint_5.ipynb
├── data/
│   ├── megaline_users.csv
│   ├── megaline_plans.csv
│   ├── megaline_calls.csv
│   ├── megaline_messages.csv
│   ├── megaline_internet.csv
│   └── README_data.md
├── screenshots/
└── README.md

Archivo principal:

Notebook:
notebooks/Proyecto_Sprint_5.ipynb





Evaluar optimización del plan menos rentable.

Implementar segmentación basada en consumo para mejorar ingresos.
