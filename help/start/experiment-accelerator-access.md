---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Mejore su capacidad para realizar experimentos de forma eficaz y generar datos
topic: Content Management
role: User
level: Beginner
keywords: contenido, experimento, múltiple, público, tratamiento
source-git-commit: 020ed6c652c66ed78789a5a90dfc8c8dece624a9
workflow-type: tm+mt
source-wordcount: '507'
ht-degree: 18%

---

# Acceder a Journey Optimizer Experimentation Accelerator

Después de [crear y configurar tu experimento](https://experienceleague.adobe.com/es/docs/journey-optimizer/using/content-management/content-experiment/content-experiment) y de enviar tus campañas o recorridos a tus perfiles, puedes acceder a **[!UICONTROL Journey Optimizer Experimentation Accelerator]** para profundizar en el rendimiento de tu experimento.

Puede acceder a **[!UICONTROL Journey Optimizer Experimentation Accelerator]** desde el menú de la izquierda de la lista desplegable [!UICONTROL Experimentación] o a través del conmutador Aplicaciones. Tenga en cuenta que los usuarios que solo tengan una licencia de Target solo pueden acceder a ella a través del conmutador Aplicaciones.

![](assets/access.png)

Los experimentos disponibles dependen de la configuración:

* **Para usuarios de Adobe Journey Optimizer**: los experimentos configurados en la zona protegida de su organización habilitada se incluyen automáticamente.

* **Para usuarios de Adobe Target con Journey Optimizer**: todas las actividades A/B de Target aparecen en **[!UICONTROL Journey Optimizer Experimentation Accelerator]** en la zona protegida de producción de Journey Optimizer.

* **Para usuarios solo de Adobe Target**: todas las actividades A/B de su organización de Target se incluyen en la zona protegida de producción de Journey Optimizer.

Para usar **[!UICONTROL Journey Optimizer Experimentation Accelerator]**, necesita acceso a la zona protegida y los siguientes permisos relacionados:

* **[!UICONTROL Ver experimentos]**
* **[!UICONTROL Administrar metadatos de experimento]**

+++ Obtenga información sobre cómo asignar permisos relacionados con Experimentos con una licencia de Adobe Experience Platform o Adobe Recorrido Optimizer

1. En el producto **[!DNL Permissions]**, vaya a la ficha **[!UICONTROL Roles]** y seleccione el **[!UICONTROL Rol]** que desee.

1. Haga clic en **[!UICONTROL Editar]** para modificar los permisos.

1. Agregue el recurso **[!UICONTROL Acelerador de experimentos]** y, a continuación, seleccione **[!UICONTROL Ver experimentos]** o **[!UICONTROL Administrar metada de experimento]** en el menú desplegable.

   ![](assets/permissions-experiment.png)

1. Haga clic en **[!UICONTROL Guardar]** para aplicar los cambios.

Los permisos de los usuarios que ya estén asignados a esta función se actualizarán automáticamente.

Para asignar esta función a nuevos usuarios:

1. Vaya a la ficha **[!UICONTROL Usuarios]** en el panel de funciones y haga clic en **[!UICONTROL Agregar usuario]**.

1. Introduzca el nombre del usuario y su dirección de correo electrónico, o selecciónelo en la lista, y haga clic en **[!UICONTROL Guardar]**.

   Si el usuario no se creó anteriormente, consulte [esta documentación](https://experienceleague.adobe.com/es/docs/experience-platform/access-control/abac/permissions-ui/users).

El usuario recibirá un correo electrónico con instrucciones para acceder a su instancia.

+++

</br>

+++ Obtenga información sobre cómo asignar permisos relacionados con experimentos con licencias de Adobe Target

1. Abra **[Admin Console](http://adminconsole.adobe.com/)**.

1. En **[!UICONTROL Productos]**, elija **[!UICONTROL Adobe Experience Platform]**.

1. Haga clic en **[!UICONTROL Nuevo perfil]**.

   ![](assets/permission-target.png)

1. Escriba un **[!UICONTROL Nombre]** y una **[!UICONTROL Descripción]** para el perfil y, a continuación, haga clic en **[!UICONTROL Guardar]**.

1. Abra el **[!UICONTROL perfil]** recién creado y vaya a la ficha **[!UICONTROL Permisos]**.

1. Haga clic en ![](assets/do-not-localize/Smock_Edit_18_N.svg) junto al permiso **[!UICONTROL acelerador de experimentación]**.

   ![](assets/permission-target-1.png)

1. Añada los permisos que debe tener este perfil, como **[!UICONTROL Ver experimentos]** y **[!UICONTROL Administrar metadatos de experimento]**, y luego haga clic en **[!UICONTROL Guardar]**.

   >[!TIP]
   >
   > Cree perfiles independientes cuando los usuarios necesiten niveles de acceso diferentes. Por ejemplo, cree un perfil de **[!UICONTROL Experimentation Accelerator Viewer]** con solo **[!UICONTROL Ver experimentos]** y un perfil de **[!UICONTROL Experimentation Accelerator Editor]** con **[!UICONTROL Ver experimentos]** y **[!UICONTROL Administrar metadatos de experimento]**.

   ![](assets/permission-target-2.png)

1. En la ficha **[!UICONTROL Permisos]**, seleccione **[!UICONTROL Zonas protegidas]**.

1. Agregue las zonas protegidas en las que los usuarios deben poder usar Journey Optimizer Experimentation Accelerator y luego haga clic en **[!UICONTROL Guardar]**.

1. Abra la ficha **[!UICONTROL Usuarios]** y haga clic en **[!UICONTROL Agregar usuarios]**.

   ![](assets/permission-target-3.png)

1. Agregue los usuarios que deben recibir este acceso y luego haga clic en **[!UICONTROL Guardar]**.

Los usuarios añadidos a este perfil ahora pueden acceder a Journey Optimizer Experimentation Accelerator desde el conmutador de aplicaciones.

+++


<!--
table style="table-layout:fixed"><tr style="border: 0;">
<td><img alt="Overview" href="experiment-accelerator-overview.md" src="assets/do-not-localize/experiments-2.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-overview.md">Overview</a></strong></p></div></td>
<td><img alt="Experiments" href="experiment-accelerator-monitor.md" src="assets/do-not-localize/experiment-overview.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-monitor.md">Experiments</a></strong></p></div></td>
<td><img alt="Metrics" href="experiment-accelerator-metrics.md" src="assets/do-not-localize/experiment-metrics.png">
<div align="center"><p><strong><a href="experiment-accelerator-metrics.md">Metrics</a></strong></p></div></td>
</tr></table
-->
