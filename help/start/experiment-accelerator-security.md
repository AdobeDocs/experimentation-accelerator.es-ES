---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Uso de datos en IA con Journey Optimizer Experimentation Accelerator
topic: Content Management
role: User
level: Beginner
keywords: contenido, experimento, múltiple, público, tratamiento
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b3538224-471e-4c63-a444-9b19d89ae29cid: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dcid: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: d095671a-1355-40aa-8b5f-06c33c68080bid: e1e0219c-f879-479f-8427-888ed2a6e9c2id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 2%

---

# Uso de datos en IA con Journey Optimizer Experimentation Accelerator{#experiment-accelerator-security}

**Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator** le permite descubrir automáticamente información y recomendar oportunidades para mejorar sus experimentos y programas de experimentación. La solución aprovecha la IA y el aprendizaje automático para ofrecer estas recomendaciones. Esta instrucción aclara cómo se usan los datos de los clientes en **Journey Optimizer Experimentation Accelerator**.

## ¿Qué datos utiliza Journey Optimizer Experimentation Accelerator?

Actualmente hay tres tipos de datos usados por **Journey Optimizer Experimentation Accelerator**:

* **Metadatos del experimento**: nombre del experimento, definición de la audiencia utilizada en el experimento y tratamientos en el experimento, por ejemplo: nombre, porcentajes de división, ubicación o superficie en la que se proporcionó el experimento.

* **Rendimiento de los tratamientos**: número de personas, media de la métrica de éxito y desviación estándar de cada tratamiento.

* **Contenido del tratamiento**: el HTML procesado y la captura de pantalla del tratamiento tal como lo vería un usuario en su sitio web.

## ¿Qué hace Journey Optimizer Experimentation Accelerator con estos datos?

**Journey Optimizer Experimentation Accelerator** toma el contenido de cada tratamiento y crea una incrustación, es decir, una representación matemática del contenido, y luego correlaciona esas incrustaciones con el rendimiento de los tratamientos. Este proceso permite extraer los atributos de contenido que tienen el mejor rendimiento para un uso futuro. Estos atributos se incorporan a un modelo de lenguaje grande alojado en Adobe, que los convierte en declaraciones legibles por humanos utilizadas para generar perspectivas y sugerir oportunidades.

## ¿Qué restricciones tiene Journey Optimizer Experimentation Accelerator sobre los datos utilizados?

Cada cliente se asigna a una organización y zona protegida específicas. Se entrena un modelo dedicado para cada zona protegida. Al eliminar una zona protegida, todos los datos, señales y modelos relacionados se eliminan de forma permanente.

* Solo utilizamos los datos del cliente para entrenar o ajustar el modelo de ese cliente.

* Nunca mezclamos clientes para entrenar o afinar un modelo.

## ¿Cambiarán los modelos de Adobe o la IA la experiencia de usuario de una marca automáticamente?

No. **Journey Optimizer Experimentation Accelerator** solo recomienda qué se puede cambiar y cómo se puede cambiar. Solo los usuarios que tengan permisos para cambiar la experiencia con Journey Optimizer o Target podrán seguir estas recomendaciones. Todas las recomendaciones se pueden revisar y editar antes de ser eliminadas.

## ¿Existe algún riesgo para la estabilidad de sus datos o del sistema?

**Journey Optimizer Experimentation Accelerator** solo ingiere y analiza datos, produciendo información y recomendaciones para futuras pruebas. No tiene acceso para modificar ninguna configuración de prueba. Todas las sugerencias generadas dentro de la herramienta se envían a Target y Journey Optimizer para su implementación, lo que garantiza que no afecten a las actividades actuales de los clientes.
