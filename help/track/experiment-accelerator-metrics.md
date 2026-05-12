---
solution: Journey Optimizer
product: journey optimizer
title: Métricas de Journey Optimizer Experimentation Accelerator
description: Mejore su capacidad para realizar experimentos de forma eficaz y generar datos
topic: Content Management
role: User
level: Beginner
keywords: contenido, experimento, múltiple, público, tratamiento
TQID: https://experienceleague.adobe.com/OrtdIfQfKMIWODRi9fr-dEuc7g06hISv6-Dq-54qGeY
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 364
ht-degree: 6%

---

# Métricas {#experiment-accelerator-metrics}

La página **[!UICONTROL Métricas]** muestra métricas de éxito de experimentos de Journey Optimizer y Target en un solo lugar, lo que permite supervisar el rendimiento, realizar comparaciones y obtener información más detallada.

## Panel de control {#dashboard}

Al acceder a la pestaña **[!UICONTROL Métricas]**, todas las métricas de éxito disponibles de Journey Optimizer y Adobe Target se muestran en una vista consolidada para ayudarle a realizar un seguimiento del rendimiento entre iniciativas, comparar resultados e identificar rápidamente las áreas que requieren atención.

Obtenga acceso a los filtros haciendo clic en ![](assets/do-not-localize/Smock_Filter_18_N.svg), que ofrece opciones específicas del contexto como filtrar por **[!UICONTROL Source]** o **[!UICONTROL Utilizado en experimentos activos]**.

También puede buscar rápidamente cualquier métrica escribiendo su nombre en la barra de búsqueda.

![](assets/experiment-monitor-metrics.png)

## Detalles de métrica {#metric-details}

### Incremental con el tiempo

![](assets/experiment-monitor-metrics-2.png)

El gráfico **[!UICONTROL Incremental en el tiempo]** proporciona un desglose visual de las tendencias de la métrica seleccionada en un intervalo de tiempo seleccionado. Utilice el menú desplegable para alternar entre vistas diarias o semanales y ajustar el nivel de granularidad.

Los siguientes valores de resumen están disponibles para consulta rápida:

* **[!UICONTROL Total]**: El valor acumulado de la métrica seleccionada durante el período de informe.

* **[!UICONTROL Promedio]**: El valor típico de la métrica calculada en el intervalo de tiempo seleccionado. Al equilibrar las fluctuaciones diarias o semanales, ofrece una imagen más clara del rendimiento normal y se puede utilizar como línea de base para la comparación.

* **[!UICONTROL Tasa de conversión]**: porcentaje de perfiles que completaron la acción deseada (por ejemplo, compra, registro) después de ver el tratamiento.

Cada valor incluye un cambio porcentual con respecto al período anterior, lo que facilita ver si el rendimiento mejora, disminuye o permanece estable.

### Efecto del experimento

![](assets/experiment-monitor-metrics-3.png)

Esta sección muestra todos los experimentos activos dentro del lapso de tiempo seleccionado (últimos 90 días, últimos 30 días o últimos 7 días) y destaca su contribución a la métrica.

Las métricas disponibles son las siguientes:

* **[!UICONTROL Alza]**: medición de la mejora porcentual en la tasa de conversión de un tratamiento determinado respecto al valor de referencia.

* **[!UICONTROL Confianza]**: Evidencia de que un tratamiento dado es el mismo que el tratamiento basal. [Más información](http://experienceleague.adobe.com/en/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Contribución]**: La proporción del cambio general en la métrica que puede atribuirse a un experimento o tratamiento específico, lo que permite identificar las iniciativas que ejercen el mayor impacto relativo.
