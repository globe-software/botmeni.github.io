---
weight: 570
title: "Comportamiento según Horarios"
description: "Comportamiento para un horario en particular"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---
### Establecer Horario

En la sección Horario, puedes configurar el comportamiento de respuesta para un dado horario. Esta configuración tiene prioridad sobre la de productos, categorías y vertical de negocio que hayas definido, según se explica en las siguientes secciones.<br></br>
Para personalizar los horarios:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Horario
{{< figure width="700px" height="500px" src="/images/general/horario1.png" >}}
4. Selecciona los días para los que vas a establecer el horario.
{{< figure width="700px" height="500px" src="/images/general/horario2.png" >}}
5. Presiona el botón Agregar Horario
{{< figure width="700px" height="500px" src="/images/general/horario3.png" >}}
6. Establece las horas, deslizando los círculos hasta llegar al punto deseado.
{{< figure width="700px" height="500px" src="/images/general/horario4.png" >}}
7. Si necesitas agregar otra franja horaria para los mismos días, presiona nuevamente el botón AGREGAR HORARIO.
{{< figure width="700px" height="500px" src="/images/general/horario5.png" >}}
8. Establece las horas, deslizando los círculos hasta llegar al punto deseado.
{{< figure width="700px" height="500px" src="/images/general/horario6.png" >}}
9. Una vez que has definido el o los días y las horas, debes seleccionar el comportamiento de respuesta deseado para el horario definido.
{{< figure width="700px" height="500px" src="/images/general/horario10.png" >}}
10. A su vez, puedas definir dentro de dicho horario comportamientos de respuesta específicos para preguntas o respuestas con características particulares. Esta configuración tendrá prioridad sobre el comportamiento definido para el horario en el paso anterior (paso 9), excepto que selecciones la opción NO APLICA, según se explica en los siguientes pasos.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario1.png" >}}
11. Para configurar los comportamientos específicos, despliega los comportamientos disponibles presionando el triángulo invertido, y selecciona el tratamiento de respuesta específico que deseas configurar para las preguntas o respuestas con una determinada característica particular.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario2.png" >}}
12. Si el comportamiento de respuesta para el horario está definido en Automático, en el recuadro Calidad de respuesta automática podrás establecer la calidad mínima que deben tener las respuestas para que sean enviadas de modo automático a Mercado Libre, en dicho horario.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario3.png" >}}
13. En la imagen a continuación se muestra una configuración donde para el horario definido, la configuración de respuesta es automática, excepto para las preguntas relacionadas con stock, para las cuales la plataforma generará la respuesta pero la misma no se enviará (quedará pendiente para que el usuario la envíe manualmente).
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario4.png" >}}
14. En caso de no seleccionar comportamientos específicos por tipo de pregunta/respuesta, se aplicará la configuración establecida en la sección Configuraciones Particulares, tal cual se detalla en naranja debajo de cada categoría.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario5.png" >}}
14. Si deseas que las preguntas/respuestas con características particulares no tomen la configuración establecida en la sección Configuraciones Particulares, sino que se comporten según el comportamiento general seleccionado para el horario, selecciona el modo de comportamiento NO APLICA. Se muestra un ejemplo a continuación.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario6.png" >}}
15. Puedes configurar nuevos grupos de horarios, presionando el botón NUEVO GRUPO.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario7.png" >}}
<br></br>
Siguiendo los pasos detallados en la sección [Funcionalidades y beneficios incluidos según el plan](../../Suscripcíon_y_Pagos/Tu_Suscripcion/Conocer_beneficios_planes.md) podrás visualizar cuáles planes tienen incluida la funcionalidad recién detallada.

### Eliminar una configuración de horario

Si necesitas eliminar una configuración de Horario:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Horario
{{< figure width="700px" height="500px" src="/images/general/horario1.png" >}}
4. Si necesitas eliminar alguna de las franjas horarias definidas, presiona el ícono X a la derecha de la franja que deseas eliminar.
{{< figure width="700px" height="500px" src="/images/general/horario7.png" >}}
5. Para eliminar un conjunto entero de configuraciones, presiona el ícono papelera a la derecha del grupo que deseas eliminar.
{{< figure width="700px" height="500px" src="/images/general/horario9.png" >}}

### Establecer respuesta automática fija por horario

Dentro de nuestra plataforma es posible establecer una Respuesta automática fija, para un determinado horario.<br></br>
La misma puede establecerse para todas las preguntas que ingresen en una franja horaria, o sólo para un tipo particular de pregunta o respuesta.<br></br>
Para utilizar la Respuesta Automática fija por horario debes primero configurar un horario en la sección Horario, siguiendo los pasos 1 a 8 detallados en la sección [Establecer Horario](../../Personaliza_tu_cuenta_de_botmeni/Configuración_comportamiento_respuesta/Horarios_solo_analizar.md)<br></br>

Para establecer la respuesta automática fija, luego de que ya has configurado el horario:
1. Selecciona el comportamiento Automático
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario11.png" >}}
2. Selecciona el check box: Ignorar configuración anterior y utilizar solo esta respuesta fija.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario8.png" >}}
3. En el campo Respuesta fija ingresa la respuesta que deseas que se envíe.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario9.png" >}}
4. A continuación, se muestra un ejemplo de una configuración de Respuesta automática fija.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario10.png" >}}
<br></br>
Esta configuración tendrá prioridad sobre el modo de respuesta establecido en la sección Configuraciones Particulares, y para producto, categoría y vertical de negocio.

### Establecer respuesta automática fija por horario según características particulares de la pregunta o respuesta

Si lo que deseas es establecer una respuesta automática fija, para un determinado horario, y sólo para preguntas o respuestas con una característica en particular:
1. Configura el horario en la sección Horario, siguiendo los pasos 1 a 8 detallados en la sección [Establecer Horario](../../Personaliza_tu_cuenta_de_botmeni/Configuración_comportamiento_respuesta/Horarios_solo_analizar.md).
{{< figure width="560px" height="400px" src="/images/general/configuracion_horario12.png" >}}
2. Selecciona el tipo de comportamiento Automático.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario11.png" >}}
3. Despliega las opciones de comportamiento presionando sobre el ícono triángulo invertido, en el tipo de pregunta o respuesta que desesas configurar.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario13.png" >}}
4. Selecciona Respuesta fija. Por ejemplo, en la imagen siguiente se configura Respuesta fija para las preguntas que ingresen en el horario definido y que sean del tipo Preguntas por stock.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario14.png" >}}
5. Ingresa el mensaje que deseas se envíe como respuesta automática.
{{< figure width="700px" height="500px" src="/images/general/configuracion_horario15.png" >}}

Así, siguiendo los pasos recién detallados, puedes configurar para un dado horario una respuesta automática fija para preguntas relacionadas con stock, compatibilidad, que especifican número de chasis o que corresponden a una venta reciente. También lo puedes establecer para respuestas que contienen link a otros ítems, o que fueron calificadas de baja calidad por nuestra plataforma al momento de evaluar la calidad de la respuesta generada.
Esta configuración tendrá prioridad sobre el modo de respuesta establecido para el horario, y también sobre las configuraciones definidas en la sección Configuraciones Particulares, y para producto, categoría y vertical de negocio.
