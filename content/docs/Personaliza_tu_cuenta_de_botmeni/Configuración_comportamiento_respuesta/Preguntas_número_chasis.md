---
weight: 555
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
Existen cuatro opciones de comportamiento:
- No aplica: no se personaliza el comportamiento para las preguntas que contienen el dato de número de chasis, se procesarán según la configuración que esté definida. 
- Manual con respuesta: Botmeni generará la respuesta y quedará pendiente para que tu la revises y la envíes (si la configuración de producto, categoría o vertical que le corresponde está definida en modo Automático o Solo analizar)
- Manual sin respuesta: Botmeni no generará ni enviará respuesta al detectar que se trata de una pregunta sobre compatibilidad (si la configuración de producto, categoría o vertical que le corresponde está definida en modo Automático o Solo analizar).
- Respuesta fija: se enviará como respuesta automática el mensaje definido por el usuario en el campo respuesta fija (si la configuración de producto, categoría o vertical que le corresponde está definida en modo Automático).
<br></br>
Para configurar el comportamiento para preguntas que contienen número de chasis:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Configuraciones Particulares
{{< figure width="840px" height="600px" src="/images/general/particular1.png" >}}
4. Despliega el listado de comportamientos presionando el ícono triángulo invertido.
{{< figure width="840px" height="600px" src="/images/general/particular9.png" >}}
5. Selecciona el comportamiento deseado.
{{< figure width="840px" height="600px" src="/images/general/particular10.png" >}}	
6. En caso de que el comportamiento seleccionado sea Respuesta Fija, ingresa en el campo Respuesta fija el mensaje de debe enviarse como respuesta automática.
{{< figure width="840px" height="600px" src="/images/general/particular11.png" >}}
<br></br>
Independientemente de la selección recién mencionada, las preguntas se consideran procesadas cuando la configuración por producto, categoría, vertical u horario que corresponda esté definida en modo Automático o Solo responder. Esto se debe a que implementar el comportamiento definido en esta sección requiere de análisis previo para identificar el tipo de pregunta del cual se trata.<br></br>
El comportamiento recién descripto puede variar en caso de que hayas definido comportamientos específicos para Horarios o fechas.<br></br>
Para conocer cómo configurar el comportamiento de respuesta en horarios específicos para preguntas que contienen el dato del número de chasis, dirígete a la sección [Comportamiento según horarios](../Configuración_comportamiento_respuesta/Horarios_solo_analizar.md) disponible en la guía.<br></br>
Los pasos para definir el comportamiento de respuesta de preguntas que contienen número de chasis en fechas específicas, están detallados en la sección [Comportamiento según fecha](../Configuración_comportamiento_respuesta/Dias_festivos.md).<br></br>
