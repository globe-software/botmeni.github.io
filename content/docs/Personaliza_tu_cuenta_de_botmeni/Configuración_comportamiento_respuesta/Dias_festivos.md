---
weight: 548
title: "Comportamiento para una fecha calendario"
description: "Comportamiento definido para fechas específicas"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---
### Establecer Comportamiento para fechas específicas

Es posible que necesites definir días del año en que no quieres que se aplique la configuración establecida. Por ejemplo, durante días festivos o feriados.
Para ello, puedes establecer un comportamiento específico que se aplicará específicamente para las fechas que tu definas, dentro de la sección Configuración de días no laborables.<br></br>
Para establecer el comportamiento recién descripto:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Configuraciones de días no laborables
{{< figure width="700px" height="500px" src="/images/general/nolaborables1.png" >}}
4. Selecciona el tipo de gestión de respuesta general que deseas aplicar en las fechas a especificar.
{{< figure width="700px" height="500px" src="/images/general/nolaborables2.png" >}}
5. Presiona sobre el ícono Lapiz, se desplegará un calendario.
{{< figure width="700px" height="500px" src="/images/general/nolaborables3.png" >}}
6. Selecciona (haciendo clik o presionando) los días a incluir. Puedes seleccionar todos los que necesites.
{{< figure width="700px" height="500px" src="/images/general/nolaborables4.png" >}}
7. Presiona fuera del recuadro, visualizarás los días que quedaron seleccionados.
{{< figure width="700px" height="500px" src="/images/general/nolaboables5.png" >}}
6. Para desmarcar alguno de los días, sólo tienes que presionar sobre la X a la derecha del día que deseas desmarcar.
{{< figure width="700px" height="500px" src="/images/general/nolaboables6.png" >}}

### Establecer respuesta automática fija para fechas específicsa

Dentro de nuestra plataforma es posible establecer una Respuesta automática fija que se enviará sólo para las fechas que definas.<br></br>
La misma puede establecerse para todas las preguntas que ingresen en una franja horaria, o sólo para un tipo particular de pregunta o respuesta.<br></br>
Para utilizar la Respuesta Automática fija debes tener configurado al menos un horario en la sección Horario, siguiendo los pasos 1 a 8 detallados en la sección [Establecer Horario](../../Personaliza_tu_cuenta_de_botmeni/Configuración_comportamiento_respuesta/Horarios_solo_analizar.md)<br></br>

Para establecer la respuesta automática fija, luego de que ya has configurado el horario:
1. Selecciona el tipo de comportamiento general que deseas para el horario, puede ser Automático o Solo analizar.
{{< figure width="700px" height="500px" src="/images/general/horario10.png" >}}
2. Selecciona el check box: Ignorar configuración anterior y utilizar solo esta respuesta fija.
{{< figure width="700px" height="500px" src="/images/general/horario12.png" >}}
3. En el campo Respuesta fija ingresa la respuesta que deseas que se envíe.
{{< figure width="700px" height="500px" src="/images/general/horario13.png" >}}
4. A continuación, se muestra un ejemplo de una configuración de Respuesta automática fija.
{{< figure width="700px" height="500px" src="/images/general/horario14.png" >}}
<br></br>
Esta configuración tendrá prioridad sobre el modo de respuesta establecido para el horario, y también sobre las configuraciones definidas en la sección Configuraciones Particulares, y por producto, categoría y vertical de negocio.

### Establecer respuesta automática fija por horario según características particulares de la pregunta o respuesta

Si lo que deseas es establecer una respuesta automática fija, para un determinado horario, y sólo para preguntas o respuestas con una característica en particular:
1. Configura el horario en la sección Horario, siguiendo los pasos 1 a 8 detallados en la sección [Establecer Horario](../../Personaliza_tu_cuenta_de_botmeni/Configuración_comportamiento_respuesta/Horarios_solo_analizar.md).
{{< figure width="700px" height="500px" src="/images/general/horario16.png" >}}
2. Selecciona el tipo de comportamiento general que deseas para el horario, puede ser Automático o Solo analizar.
{{< figure width="700px" height="500px" src="/images/general/horario17.png" >}}
3. Despliega las opciones de comportamiento presionando sobre el ícono triángulo invertido, en el tipo de pregunta o respuesta que desesas configurar.
{{< figure width="700px" height="500px" src="/images/general/horario18.png" >}}
4. Selecciona Respuesta fija. Por ejemplo, en la imagen siguiente se configura Respuesta fija para las preguntas que ingresen en el horario definido y que sean del tipo Preguntas por stock.
{{< figure width="700px" height="500px" src="/images/general/horario19.png" >}}
5. Ingresa el mensaje que deseas se envíe como respuesta automática.
{{< figure width="700px" height="500px" src="/images/general/horario20.png" >}}

Así, siguiendo los pasos recién detallados, puedes configurar para un dado horario una respuesta automática fija para preguntas relacionadas con stock, compatibilidad, que especifican número de chasis o que corresponden a una venta reciente. También lo puedes establecer para respuestas que contienen link a otros ítems, o que fueron calificadas de baja calidad por nuestra plataforma al momento de evaluar la calidad de la respuesta generada.
Esta configuración tendrá prioridad sobre el modo de respuesta establecido para el horario, y también sobre las configuraciones definidas en la sección Configuraciones Particulares, y por producto, categoría y vertical de negocio.

