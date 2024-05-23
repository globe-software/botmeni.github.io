weight: 585
title: "Comportamiento de respuesta para preguntas que contienen número de chasis"
description: "Comportamiento de respuesta para preguntas que contienen número de chasis"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---

Botmeni te brinda la posibilidad de personalizar el comportamiento de respuesta para las preguntas que contengan número de chasis. 
Existen tres opciones de comportamiento:
- Responder: responderá en forma automática (si la configuración de producto, categoría o vertical que le corresponde está definida en modo Automático)
- Pasar a manual generando respuesta: Botmeni generará la respuesta pero quedará pendiente para que tu la revises y la envíes (si la configuración de producto, categoría o vertical que le corresponde está definida en modo Automático o Solo analizar)
- Pasar a manual sin generar respuestas: botmeni no generará ni enviará respuesta al detectar que se trata de una pregunta de stock.
<br></br>
Para configurar el comportamiento para preguntas que contienen número de chasis:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Configuraciones Particulares
{{< figure width="840px" height="600px" src="/images/general/particulares.png" >}}
4. Despliega el listado de comportamientos presionando el ícono triángulo invertido ubicado a la derecha de Pregunta especificando número de chasis. 
{{< figure width="840px" height="600px" src="/images/general/particulares6.png" >}}
5. Selecciona el comportamiento deseado.
{{< figure width="840px" height="600px" src="/images/general/particulares7.png" >}}	
<br></br>
Independientemente de la selección recién mencionada, las preguntas se consideran procesadas cuando la configuración por producto, categoría, vertical u horario que corresponda esté definida en modo Automático o Solo responder. Esto se debe a que implementar el comportamiento definido en esta sección requiere de análisis previo para identificar el tipo de pregunta del cual se trata.<br></br>
El comportamiento recién descripto puede variar en caso de que hayas definido Horarios Solo Analizar y tengas activada la Respuesta Automática Fija. Para conocer más al respecto puedes dirigirte a la sección [Horarios Solo Analizar](../Configuración_comportamiento_respuesta/Horarios_solo_analizar.md) disponible en la guía.

