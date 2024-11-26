---
weight: 575
title: "Comportamiento según fecha calendario"
description: "Comportamiento definido para fechas específicas"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---
### Establecer Comportamiento para fechas específicas

Es posible que necesites definir para días específicos del año un comportamiento de respuesta distinto al configurado. Por ejemplo, para días festivos o feriados.
Dentro de la sección Configuración de días no laborables puedes establecer un comportamiento que se aplicará específicamente para las fechas que tu definas.<br></br>
Esta configuración tendrá prioridad sobre el comportamiento de respuesta definido en las secciones Horarios, y por sobre lo establecido para producto, categoría y vertical de negocio, según se explica en las siguientes secciones.<br></br>
Siguiendo los pasos detallados en la sección [Funcionalidades y beneficios incluidos según el plan](../../Suscripcíon_y_Pagos/Tu_Suscripcion/Conocer_beneficios_planes.md) podrás visualizar cuáles planes tienen incluida la funcionalidad recién detallada.<br></br>
Para establecer el comportamiento de respuesta para fechas específicas:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Haz clic en CONFIGURACIÓN.
{{< figure width="140px" height="100px" src="/images/general/configuracion.png" >}}
3. Posiciónate en la sección Configuraciones de días no laborables
{{< figure width="700px" height="500px" src="/images/general/nolaborables1.png" >}}
4. Selecciona el tipo de comportamiento de respuesta que deseas aplicar en las fechas a especificar.
{{< figure width="700px" height="500px" src="/images/general/nolaborables2.png" >}}
5. Presiona sobre el ícono Lapiz, se desplegará un calendario.
{{< figure width="700px" height="500px" src="/images/general/nolaborables3.png" >}}
6. Selecciona (haciendo clik o presionando) los días a incluir. Puedes seleccionar todos los que necesites.
{{< figure width="700px" height="500px" src="/images/general/nolaborables4.png" >}}
7. Presiona fuera del recuadro, visualizarás los días que quedaron seleccionados.
{{< figure width="700px" height="500px" src="/images/general/nolaborables5.png" >}}
8. Para desmarcar alguno de los días, sólo tienes que presionar sobre la X a la derecha del día que deseas desmarcar.
{{< figure width="700px" height="500px" src="/images/general/nolaborables6.png" >}}
9. Para eliminar la configuración completamente, puedes presionar el ícono x a la derecha del campo de fechas.
{{< figure width="700px" height="500px" src="/images/general/nolaborables7.png" >}}
10. Si el comportamiento de respuesta está definido en Automático, en el recuadro Calidad de respuestas automáticas podrás establecer la calidad mínima que deben tener las respuestas para que sean enviadas de modo automático a Mercado Libre.
{{< figure width="700px" height="500px" src="/images/general/nolaborables20.png" >}}
10. Una vez seleccionadas las fechas y el comportamiento general, se pueden también especificar comportamientos particulares de respuesta en función de las características de las preguntas o respuestas. Para ello, presiona el ícono triángulo invertido en el tipo de pregunta/respuesta que deseas personalizar.
{{< figure width="700px" height="500px" src="/images/general/nolaborables8.png" >}}
11. Selecciona el tipo de comportamiento que debe aplicarse.
{{< figure width="700px" height="500px" src="/images/general/nolaborables9.png" >}}
12. En la imagen a continuación se muestra una configuración donde para las fechas 25/12/2024 y 01/01/2025 la configuración de respuesta es automática. Las respuestas se enviarán de modo automático cuando su calidad sea 3 o superior, excepto para las respuestas que contienen links a otros ítems, para las cuales la plataforma generará la respuesta pero la misma no se enviará (quedará pendiente para que el usuario la envíe manualmente). 
{{< figure width="700px" height="500px" src="/images/general/nolaborables10.png" >}}
13. En caso de no seleccionar comportamientos específicos por tipo de pregunta/respuesta, se aplicará la configuración establecida en la sección Configuración Particular, tal cual se detalla en naranja debajo de cada categoría.
{{< figure width="700px" height="500px" src="/images/general/nolaborables11.png" >}}
14. Si deseas que las preguntas/respuestas con características particulares no tomen la configuración establecida en la sección Configuraciones Particulares, sino que se comporten según el comportamiento general seleccionado para las fechas, selecciona el modo de comportamiento NO APLICA. Se muestra un ejemplo a continuación.
{{< figure width="700px" height="500px" src="/images/general/nolaborables19.png" >}}

### Establecer respuesta automática fija para fechas específicas

Dentro de nuestra plataforma es posible establecer una Respuesta automática fija que se enviará sólo para las fechas que definas.<br></br>
La misma puede establecerse para todas las preguntas que ingresen en las fechas seleccionadas, o sólo para un tipo particular de pregunta o respuesta.<br></br>
Para utilizar la Respuesta Automática fija en una fecha específica debes en primer lugar configurar el comportamiento general en Automático y definir las fechas, siguiendo los pasos 1 a 9 detallados en la sección anterior. A continuación:
1. Selecciona el check box: Ignorar configuración anterior y utilizar solo esta respuesta fija.
{{< figure width="700px" height="500px" src="/images/general/nolaborables12.png" >}}
2. En el campo Respuesta fija ingresa la respuesta que deseas que se envíe.
{{< figure width="700px" height="500px" src="/images/general/nolaborables13.png" >}}
4. A continuación, se muestra un ejemplo de una configuración de Respuesta automática fija para las fechas establecidas.
{{< figure width="700px" height="500px" src="/images/general/nolaborables14.png" >}}
<br></br>

### Establecer respuesta automática fija para fechas específicas según características particulares de la pregunta o respuesta

Si lo que deseas es establecer una respuesta automática fija, para determinadas fechas, y sólo para preguntas o respuestas con una característica en particular:
1. configura el comportamiento general Automático y las fechas, siguiendo los pasos 1 a 9 detallados en la sección [Establecer Comportamiento para fechas específicas](../Configuración_comportamiento_respuesta/Dias_festivos.md).
{{< figure width="700px" height="500px" src="/images/general/nolaborables15.png" >}}
2. Despliega las opciones de comportamiento presionando sobre el ícono triángulo invertido, en el tipo de pregunta o respuesta que desesas configurar.
{{< figure width="700px" height="500px" src="/images/general/nolaborables16.png" >}}
4. Selecciona Respuesta fija. Por ejemplo, en la imagen siguiente se configura Respuesta fija para las preguntas que ingresen en las fechas definidas y que sean sobre la comptabilidad entre el producto publicado y otro producto/accesorio que mencione el cliente.
{{< figure width="700px" height="500px" src="/images/general/nolaborables17.png" >}}
5. Ingresa el mensaje que deseas se envíe como respuesta automática.
{{< figure width="700px" height="500px" src="/images/general/nolaborables18.png" >}}

Así, siguiendo los pasos recién detallados, puedes configurar para fechas específicas una respuesta automática fija para preguntas relacionadas con stock, compatibilidad, que especifican número de chasis o que corresponden a una venta reciente. También lo puedes establecer para respuestas que contienen link a otros ítems, o que fueron calificadas de baja calidad por nuestra plataforma al momento de evaluar la calidad de la respuesta generada.<br></br>
Esta configuración tendrá prioridad sobre el modo de respuesta general establecido para dichas fechas, y también sobre las configuraciones definidas en las secciones Horarios y Configuraciones Particulares, y por sobre lo establecido para producto, categoría y vertical de negocio.

