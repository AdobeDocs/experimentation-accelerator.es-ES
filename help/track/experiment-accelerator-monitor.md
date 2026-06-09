---
solution: Journey Optimizer
product: journey optimizer
title: monitor de Journey Optimizer Experimentation Accelerator
description: Mejore su capacidad para realizar experimentos de forma eficaz y generar datos
topic: Content Management
role: User
level: Beginner
keywords: contenido, experimento, múltiple, público, tratamiento
TQID: https://experienceleague.adobe.com/IYG2Jag2XtctyPaYmQfhdMm0Ac5tEg7EA7gOw7GzUk4
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: d556b755-390a-43f0-be32-a08cf6236126
  - id: d998adac-2f81-400b-a669-d07bb196e4eb
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: c07dc7f896f9c65980339f4a7fc94123fa8afe71
workflow-type: tm+mt
source-wordcount: 1367
ht-degree: 2%

---

# Seguir los experimentos {#monitor}

La pestaña **[!UICONTROL Experimentos]** centraliza el seguimiento y el análisis de las pruebas de Adobe Journey Optimizer y Adobe Target. Puede ver todos los experimentos, revisar los KPI y filtrar o buscar pruebas específicas.

## Panel de control {#dashboard}

Al acceder a la pestaña Experimentos, todos los experimentos disponibles de Journey Optimizer y Adobe Target se muestran en una vista consolidada. Esto le permite revisar y comparar rápidamente experimentos en ambas plataformas en un solo lugar.
La lista Experimentos incluye:

* Experimentos de Journey Optimizer creados en Campaign o en Recorrido.

* Experimentos de Adobe Target disponibles en la zona protegida predeterminada de producción de Journey Optimizer y vinculados a la misma organización de IMS.

La sección KPI proporciona métricas clave, como el número total de experimentos creados y el número en curso, y ofrece una instantánea de la actividad de experimentación general

Obtenga acceso a los filtros haciendo clic en ![](assets/do-not-localize/Smock_Filter_18_N.svg), que ofrece opciones específicas del contexto, como filtrar por **[!UICONTROL Tipo]**, **[!UICONTROL Estelar]**, **[!UICONTROL Estado]** o **[!UICONTROL Source]**. Por ejemplo, puede filtrar para mostrar solo los experimentos activos de Journey Optimizer.

También puede encontrar rápidamente su experimento escribiendo su nombre en la barra de búsqueda.

![](assets/experiment-monitor-dashboard.png)

## Monitorización de experimentos {#monitor-page}

Para acceder y monitorizar tus experimentos, selecciona tu experimento configurado previamente de tu lista de experimentos de la pestaña **[!UICONTROL Experimentos]**, o usa el menú avanzado para **[!UICONTROL Ver detalles]** o **[!UICONTROL Abrir en código fuente]**.

![](assets/experiment-accelerator-1.png)

La página de detalles del experimento se divide en la siguiente sección:

* [Resultado del experimento](#experiment-outcome)
* [Métrica principal](#change-primary-metric)
* [Hipótesis](#hypothesis)
* [Detalles](#details)
* [Oportunidades](#opportunities)
* [Resultados](#results)
* [Perspectivas de experimentación](#insights)

### Resultado del experimento {#experiment-outcome}

![](assets/experiment-monitor-outcome.png)

El **[!UICONTROL resultado del experimento]** le ofrece una vista rápida de la variación ganadora de su experimento.

### Cambio de la métrica principal {#change-primary-metric}

>[!AVAILABILITY]
>
>Solo los usuarios con el permiso **[!UICONTROL Administrar metadatos de experimento]** pueden cambiar la métrica principal.

El cambio de la métrica principal se aplica a los equipos que usan **[!DNL Customer Journey Analytics]** o **[!DNL Adobe Analytics]** como fuente de informes para los experimentos creados en **[!DNL Adobe Target]** o **[!DNL Adobe Journey Optimizer]**.

Tenga en cuenta lo siguiente al establecer o cambiar la métrica principal:

* Se importa una métrica a la vez. Su elección se almacena como métrica principal para ese experimento.

* Las actualizaciones solo se aplican en Journey Optimizer Experimentation Accelerator. No se vuelven a escribir en Adobe Target o Adobe Journey Optimizer.

* Si su organización utiliza únicamente Adobe Target como fuente de informes, no puede cambiar la métrica principal después de publicar la prueba.

Para cambiar la métrica principal de un experimento existente, siga estos pasos:

1. En el experimento, haga clic en **[!UICONTROL Seleccionar métrica principal]** si no se ha asignado ninguna o en **[!UICONTROL Editar]** si desea cambiarla.

   ![](assets/primary-metric-1.png)

1. Seleccione una métrica que coincida con el conjunto de orígenes de informes cuando se creó este experimento en **[!DNL Adobe Target]** o **[!DNL Adobe Journey Optimizer]**.

   Las métricas disponibles están determinadas por el origen de datos configurado en **[!DNL Adobe Target]** o **[!DNL Adobe Journey Optimizer]**. Por ejemplo, si se seleccionó **[!DNL Customer Journey Analytics]** (CJA) como el origen de informes en Target, solo estarán disponibles para la importación las métricas de CJA. No puede cambiar a una métrica desde una fuente de datos diferente y no puede cambiar la métrica principal a una métrica **[!DNL Adobe Target]** nativa.

1. Utilice la búsqueda para buscar una métrica por su nombre o utilice el filtro para ver las métricas que ya se han utilizado en experimentos activos.

   ![](assets/primary-metric-1.png)

1. Guarde la selección.

Al cambiar la métrica principal, las perspectivas y oportunidades generadas anteriormente se borran y regeneran. Durante la regeneración, se muestra el siguiente mensaje:

`Opportunities are being regenerated based on the selected metric. Updates will appear soon.`

### Configuración {#set-up}

La **[!UICONTROL Hipótesis]** captura los cambios planificados que se van a probar y documenta el impacto esperado en la métrica principal. Definir una **[!UICONTROL Hipótesis]** clara garantiza que cada experimento tenga un objetivo mensurable, lo que facilita la evaluación de resultados y la determinación de si los cambios conducen a mejoras significativas.

Tenga en cuenta que para que se generen [datos del experimento](#insights), debe confirmar los detalles de la hipótesis y el tratamiento y la relevancia estadística.

1. Haga clic en **[!UICONTROL Agregar]** para crear una **[!UICONTROL Hipótesis]** para su experimento.

   ![](assets/experiment-monitor-setup-1.png)

1. Escriba su **[!UICONTROL Hipótesis]** detallando los cambios realizados y cómo afectarán a la métrica principal.

   Haga clic en **[!UICONTROL Guardar]**.

1. Haga clic en **[!UICONTROL Revisar]** para agregar o reemplazar la imagen para cada Tratamiento.

   ![](assets/experiment-monitor-setup-2.png)

1. Las imágenes de tratamiento se generan automáticamente, pero si es necesario, puede seleccionar **[!UICONTROL Agregar imagen]** o **[!UICONTROL Reemplazar imagen]** para cargar una captura de pantalla preferida de sus archivos locales para sus **[!UICONTROL Tratamientos]**.

   Tenga en cuenta que la captura de pantalla debe capturar toda la página.

1. Haga clic en el icono ![](assets/do-not-localize/Smock_Edit_18_N.svg) para actualizar la **[!UICONTROL hipótesis]** si es necesario.

Una vez que haya terminado de configurar su **[!UICONTROL Hipótesis]**, necesitará obtener valiosos [Datos](#insights) y [Oportunidades](#opportunities).

### Detalles {#details}

![](assets/experiment-monitor-details.png)

El widget **[!UICONTROL Efecto de experimento]** proporciona una vista detallada de cómo el experimento influyó en los segmentos de audiencia objetivo. Presenta indicadores de rendimiento clave que le ayudan a evaluar la participación y el comportamiento, incluidos los siguientes:

* **[!UICONTROL Métrica de éxito]** de Journey Optimizer o la **[!UICONTROL métrica principal]** de Adobe Target, según lo que se haya configurado durante la creación del experimento.

* **[!UICONTROL Visitantes]**: El número total de visitantes únicos expuestos al experimento.

También puede ver una instantánea en tiempo real del rendimiento del tratamiento inicial mediante las siguientes métricas:

* **[!UICONTROL Responsable actual]**: identifica el tratamiento que actualmente ofrece el mejor rendimiento.

* **[!UICONTROL Alza sobre la línea de base]**: mide la mejora porcentual del tratamiento inicial en comparación con el control o la línea de base.

* **[!UICONTROL Métrica de éxito]** de Journey Optimizer o la **[!UICONTROL métrica principal]** de Adobe Target, según lo que se haya configurado durante la creación del experimento.

En la parte inferior del widget, puede encontrar un resumen conciso de la configuración del experimento, que incluye:

* **[!UICONTROL Métrica de éxito]** de Journey Optimizer o la **[!UICONTROL métrica principal]** de Adobe Target, según lo que se haya configurado durante la creación del experimento.

* **[!UICONTROL Número de tratamientos]**: El número total de variaciones probadas.

* **[!UICONTROL Audiencia]**: Los segmentos de usuario definidos se segmentaron durante el experimento.

### Oportunidades {#opportunities}

>[!AVAILABILITY]
>
>La función de oportunidades se limita a experimentos con cambios basados en texto.

El panel **[!UICONTROL Oportunidades]** muestra recomendaciones generadas por IA diseñadas para mejorar el rendimiento de las pruebas y alinearse con objetivos empresariales y KPI más amplios.

Tenga en cuenta que para que se generen oportunidades de experimento, primero debe [confirmar los detalles de la hipótesis y el tratamiento](#set-up).

1. Examine la oportunidad sugerida y haga clic en **[!UICONTROL Ver oportunidad]**.

   ![](assets/experiment-monitor-opportunities.png)

1. Al seleccionar una oportunidad, se abre la ventana **Detalles de la oportunidad**, que describe un tratamiento específico o una variación sugerida por Journey Optimizer Experimentation Accelerator. Esta vista incluye:

   * **[!UICONTROL Hipótesis]**: Una hipótesis generada por IA que explica el resultado esperado del tratamiento sugerido.

   * **[!UICONTROL Motivo]**: Una explicación de por qué Journey Optimizer Experimentation Accelerator sugirió esta oportunidad.

   * **[!UICONTROL Evaluación de oportunidad]**: Una evaluación dual de la recomendación basada en:

      * **[!UICONTROL Potencial de aprendizaje]**: Una estimación de cuánto insight nuevo podría proporcionar la oportunidad, en función de su diferencia con respecto a lo que se ha probado anteriormente.

      * **[!UICONTROL Potencial de conversión]**: una estimación de la probabilidad de que la oportunidad supere a los tratamientos actuales, basada en similitudes con estrategias que históricamente han funcionado bien.
   <!--
   * **[!UICONTROL New text treatment example]**: Words or phrases that demonstrate the style the AI recommends using.
   -->

   ![](assets/experiment-monitor-opportunities-2.png)

1. Luego puede agregarlo directamente al experimento seleccionando **[!UICONTROL Abrir experimento]**.

1. Si el experimento original se creó y administró en Adobe Journey Optimizer, esta acción abrirá el **[!UICONTROL Panel de experimentación de contenido]** dentro de esa campaña.

   Para los experimentos que se originen desde **[!DNL Adobe Target]**, los cambios sugeridos se cargarán en el flujo de trabajo de experimentación de **[!DNL Adobe Target]**.

   ➡️ [Obtenga más información en la documentación de Adobe Target](https://experienceleague.adobe.com/es/docs/target/using/activities/abtest/test-ab)

1. En la vista de experimento, se puede acceder a las mismas **[!UICONTROL oportunidades de experimentación]** de IA que aparecen en Journey Optimizer Experimentation Accelerator.

   Seleccione **[!UICONTROL Ver]** para abrir los detalles de la oportunidad.

1. Para aplicar los cambios sugeridos, al seleccionar **[!UICONTROL Modificar experimento]** se habilita la edición directa del experimento existente.

### Resultados {#results}

![](assets/experiment-monitor-results.png)

La tabla **[!UICONTROL Results]** proporciona un desglose detallado del rendimiento de cada tratamiento dentro de un experimento. Estos indicadores ayudan a evaluar la eficacia, la participación del usuario y el impacto general en los resultados clave del negocio:

* **[!UICONTROL Lugar]**: Posición de clasificación del tratamiento basada en el rendimiento que indica cómo se compara con otros tratamientos.

* **[!UICONTROL Métrica de éxito]** de Journey Optimizer o la **[!UICONTROL métrica principal]** de Adobe Target, según lo que se haya configurado durante la creación del experimento.

* **[!UICONTROL Personas]**: Número de perfiles de usuario que se califican como perfiles de destino para sus mensajes.

* **[!UICONTROL Alza]**: medición de la mejora porcentual en la tasa de conversión de un tratamiento determinado respecto al valor de referencia.

* **[!UICONTROL Confianza]**: Evidencia de que un tratamiento dado es el mismo que el tratamiento basal. [Más información](http://experienceleague.adobe.com/es/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Tasa de conversión]**: porcentaje de perfiles que completaron la acción deseada (por ejemplo, compra, registro) después de ver el tratamiento.

### Datos del experimento {#insights}

>[!AVAILABILITY]
>
>La función Perspectivas de experimentación se limita a los experimentos con cambios basados en texto.

**[!UICONTROL Perspectivas de experimento]** son aprendizajes generados por IA derivados de este experimento. Estas perspectivas están disponibles una vez que el experimento alcanza la relevancia estadística y proporcionan una comprensión contextual de lo que contribuyó a su éxito. Destacan los atributos clave presentes en el tratamiento ganador, distintos del control, que probablemente influyeron en el resultado.

Tenga en cuenta que para que se generen perspectivas de experimento, primero debe [confirmar los detalles de la hipótesis y el tratamiento](#set-up) y alcanzar la relevancia estadística.

Haga clic en **[!UICONTROL Ver detalles]** para obtener más información sobre cada información.

</br>

![](assets/experiment-monitor-insights.png)
