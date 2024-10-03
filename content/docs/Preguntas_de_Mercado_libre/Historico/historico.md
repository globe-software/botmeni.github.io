---
weight: 1015
title: "Histórico de preguntas de Mercado Libre"
description: "Histórico de preguntas de Mercado Libre"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---
El módulo Histórico contiene el listado completo de preguntas y respuestas de las cuentas de Mercado Libre asociadas a la cuenta de Botmeni, separado por cada cuenta, para un dado periodo de tiempo en función del plan suscripto.<br></br>
La información disponible para cada pregunta no se limita a la respuesta enviada, sino que también se detalla, entre otros, el tiempo/hora de pregunta y repuesta, la respuesta propuesta y la enviada, el estado de la misma, el link para visualizar el contenido de la publicación y también el acceso al chat completo intercambiado con el usuario.<br></br>
A su vez, una gran herramienta de este módulo son los filtros que tiene disponible, que te permitirán rápidamente encontrar y visualizar las preguntas asociadas a una característica particular de una pregunta o respuesta como, por ejemplo, el estado en que se encuentra o el producto sobre el que se realiza la consulta, o el usuario que generó las preguntas.<br></br>
A este listado lo pueden visualizar aquellos usuarios que tengan asociado el rol Solo responder o Administrador.

### Visualizar las preguntas del listado Histórico

Para visualizar el histórico de preguntas:
1. Inicia sesión en nuestra página de login <https://prod.botmeni.com/login>.
2. Selecciona el módulo Histórico en el menú.
{{< figure width="140px" height="100px" src="/images/general/historico.png" >}}
3. Las preguntas se encuentran separadas por cuenta de Mercado Libre. Para visualizar el listado de una cuenta presiona sobre el nombre de la misma.
{{< figure width="700px" height="500px" src="/images/general/historico2.png" >}}
4. La primera sección del módulo contiene los filtros disponibles que se pueden aplicar en el listado. Al seleccionarlos, definirás las preguntas que se visualizan en función de la o las características que selecciones en los mismos. 
{{< figure width="700px" height="500px" src="/images/general/historico3.png" >}}
5. Por ejemplo,si quisieras filtrar por el Estado de las preguntas para visualizar sólo las que tienen un estado determinado, debes desplegar las opciones disponibles para el filtro Estado y seleccionar el estado correspondiente.
{{< figure width="700px" height="500px" src="/images/general/historico4.png" >}}
6. Si quisieras filtrar las preguntas realizadas sobre un ítem específico, puedes ingresar el Id del mismo en el campo Id ítem. Otra forma de hacerlo es presionar la lupa a la derecha del campo.
{{< figure width="700px" height="500px" src="/images/general/bucador_item_historico1.png" >}}
7. Al presionar la lupa aparecerá el modal Busca un ítem. Ingresa el título de la publicación deseada. El buscador desplegará el listado de ítems de tu tienda que concuerdan con las palabras ingresadas. Selecciona el que corresponda.
{{< figure width="700px" height="500px" src="/images/general/bucador_item_historico2.png" >}}
8. Una vez definido el o los filtros que deseas aplicar, presiona el botón FILTRAR. Las preguntas desplegadas serán aquellas que cumplen con todas las condiciones establecidas en los filtros.
{{< figure width="700px" height="500px" src="/images/general/historico5.png" >}}
9. Si deseas borrar los filtros seleccionados, presiona el botón LIMPIAR.
{{< figure width="700px" height="500px" src="/images/general/historico6.png" >}}

### Información disponible para cada pregunta del Histórico

A continuación se describirá la información que puedes visualizar para cada pregunta contenida dentro del listado Histórico.
1. En la sección superior se detallan:
{{< figure width="840px" height="600px" src="/images/general/historico8.png" >}}
    1. Título de la publicación. Presionando sobre la misma se abrirá en una nueva ventana la publicación en Mercado Libre.
    2. Usuario y Ubicación: informa el nickname del usuario que realiza la pregunta y su ubicación.
    3. Id: ID de la publicación asociada a la pregunta. En caso de que corresponda también se mostrará el SKU y/o el GTIN asociado a la publicación.
    4. Estado: Hace referencia al estado de la pregunta. Los estados posibles son: Procesada, No procesada, Recibida, Eliminada y Error.
    5. Subestado: Cada pregunta tiene un subestado. En el subestado se detalla, por ejemplo, si la respuesta se envió en modo Automático o fue generada la respuesta y quedó pendiente para revisión y envío manual. Además, brinda información relacionada a cuál fue la configuración establecida para tu tienda que derivó en que la respuesta se enviara en modo Manual (por ejemplo, Manual por horario, Manual por stock, etc)
2. En la sección central se visualiza la pregunta ingresada, con su fecha y hora, y la respuesta generada por nuestro modelo, con la fecha y hora en que fue generada, si el comportamiento de respuesta está configurado para que la misma se genere.
{{< figure width="840px" height="600px" src="/images/general/historico9.png" >}}
3.  A continuación tienes la posibilidad de calificar la calidad de nuestra respuesta presionando los círculos de color verde, amarillo y rojo en función de tu evaluación: Respuesta excelente, Respuesta mejorable y Respuesta incorrecta. Y en el espacio Calificación puedes ingresar un comentario asociado a la calificación que acabas de realizar, que nos ayudará a implementar las mejoras que sean necesarias.
{{< figure width="840px" height="600px" src="/images/general/historico10.png" >}}
4. Finalmente, en la parte inferior se detalla la respuesta que fue enviada a Mercado Libre. En caso de que la respuesta enviada haya sido exactamente la respuesta generada por la plataforma, se leerá la leyenda: Respuesta generada automáticamente por Botmeni. Caso contrario, se visualizará la respuesta enviada a Mercado Libre con las modificaciones que tu tienda haya realizado. También se detallan la fecha y la hora en que se envió la respuesta a Mercado Libre.
{{< figure width="840px" height="600px" src="/images/general/historico11.png" >}}
5. Cada respuesta tiene disponible en la esquina superior derecha la acción Visualizar.
{{< figure width="840px" height="600px" src="/images/general/historico12.png" >}}
6. Al presionar la acción Visualizar se desplegará el chat completo de interacción con el usuario y también tendrás disponible el contenido de la publicación.
