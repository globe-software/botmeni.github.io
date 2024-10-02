---
weight: 545
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

En la sección Horario, puedes configurar el comportamiento de respuesta para un dado horario. Esta configuración tiene prioridad sobre la de productos, categorías y vertical de negocio que hayas definido.
Para personalizar los horarios:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Horario
{{< figure width="700px" height="500px" src="/images/general/horario1.png" >}}
4. Selecciona los días para los que vas a establecer el horario en este primer grupo de configuración.
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
10. A su vez, puedas definir dentro de dicho horario comportamientos de respuesta específicos para preguntas o respuestas con características particulares. Esta configuración tendrá prioridad sobre el comportamiento definido para el horario en el paso anterior (paso 9).
{{< figure width="700px" height="500px" src="/images/general/horario11.png" >}}
11. Puedes configurar nuevos grupos de horarios, presionando el botón NUEVO GRUPO.
{{< figure width="700px" height="500px" src="/images/general/horario15.png" >}}
<br></br>
Siguiendo los pasos detallados en la sección [Funcionalidades y beneficios incluidos según el plan](../../Suscripcíon_y_Pagos/Tu_Suscripcion/Conocer_beneficios_planes.md) se pueden visualizar cuáles planes tienen incluida la funcionalidad recién detallada.

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

### Establecer Días no laborables

Es posible que necesites definir días del año en que no quieres que se aplique la configuración establecida en Horario Solo Analizar. Para ello, una vez que hayas definido Horarios Solo analizar, puedes establecer en la sección Configuración de días no laborables, aquellos días en que Botmeni no tomará en cuenta los horarios establecidos en Horario Solo analizar, y seguirá el comportamiento que se haya definido para las Categorías y Productos. o en la secciòn Configuración Particular.<br></br>
Para establecer los días no laborables:
1. Posiciónate en la sección Horario Solo Analizar
{{< figure width="700px" height="500px" src="/images/general/horario1.png" >}}
2. Desplázate hacia abajo en la pantalla hasta visualizar la sección Configuración de días no laborables.
{{< figure width="700px" height="500px" src="/images/general/nolaboables1.png" >}}
3. Presiona el botón AGREGAR DÍAS NO LABORABLES
{{< figure width="700px" height="500px" src="/images/general/nolaboables2.png" >}}
4. Selecciona (haciendo clik o presionando) los días a marcar como no laborables. Puedes seleccionar todos los que necesites.
{{< figure width="700px" height="500px" src="/images/general/nolaboables3.png" >}}
5. Presiona fuera del recuadro y visualizarás los días que quedaron seleccionados.
{{< figure width="700px" height="500px" src="/images/general/nolaboables4.png" >}}
6. Para desmarcar alguno de los días, sólo tienes que presionar sobre la X a la derecha del día que deseas desmarcar.
{{< figure width="700px" height="500px" src="/images/general/nolaboables5.png" >}}

### Establecer respuesta automática fija

Dentro de nuestra plataforma es posible establecer una Respuesta automática fija, que será enviada como respuesta ante determinadas situaciones, para un determinado horario.<br></br>
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
Si lo que deseas es establecer una respuesta automática fija, para un determinado horario, y sólo para preguntas o respuestas con una característica en particular:
1. Configura el horario en la sección Horario, siguiendo los pasos 1 a 8 detallados en la sección [Establecer Horario](../../Personaliza_tu_cuenta_de_botmeni/Configuración_comportamiento_respuesta/Horarios_solo_analizar.md)

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
Esta configuración tendrá prioridad sobre el modo de respuesta establecido para el horario, y también sobre las configuraciones definidas en la sección Configuraciones Particulares, o por producto, categoría y vertical de negocio.
