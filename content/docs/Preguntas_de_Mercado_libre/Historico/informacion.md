---
weight: 1020
title: "Información disponible para cada pregunta del Histórico"
description: "Información disponible para cada pregunta del Histórico"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---
A continuación se describirá la información que puedes visualizar para cada pregunta contenida dentro del listado Histórico.
1. En la sección superior se detallan:
{{< figure width="840px" height="600px" src="/images/general/historico8.png" >}}
    1. Título de la publicación. Presionando sobre la misma se abrirá en una nueva ventana la publicación en Mercado Libre.
    2. Información sobre la publicación consultada: Precio, stock y estado.
    3. Usuario y Ubicación: informa el nickname del usuario que realiza la pregunta y su ubicación.
    4. Id: id ítem corresponde al id de la publicación asociada a la pregunta (en caso de que corresponda también se mostrará el SKU y/o el GTIN) y debajo el ID de la pregunta.
    5. Estado: Hace referencia al estado de la pregunta. Los estados posibles son: Procesada, No procesada, Recibida, Eliminada y Error.
    6. Subestado: Cada pregunta tiene un subestado. En el subestado se detalla, por ejemplo, si la respuesta se envió en modo Automático (Automática) o fue generada la respuesta y quedó pendiente para revisión y envío manual (Manual).
    7. Indica la configuración que definió el comportamiento de respuesta. Por ejemplo, para el caso de la imagen, La respuesta quedó con estado Procesada y Subestado Manual por stock (es decir, se generó la respuesta pero no se envió en forma automática), dado que la tienda tiene definido ese comportamiento para las preguntas que ingresan en ese horario (Configuración Horarios) y son referidas a stock (Stock).
2. En la sección central se visualiza la pregunta ingresada, con su fecha y hora, y la respuesta generada por nuestro modelo, con la fecha y hora en que fue generada, si el comportamiento de respuesta está configurado para que la misma se genere. 
{{< figure width="840px" height="600px" src="/images/general/historico9.png" >}}
3.  A continuación tienes la posibilidad de calificar nuestra respuesta presionando sobre el botón CALIFICA ESTA RESPUESTA. En la sección [Calificar respuestas del Histórico](../Historico/calificar.md) se explica en detalle el proceso de Calificación.
{{< figure width="840px" height="600px" src="/images/general/historico10.png" >}}
4. Finalmente, en la parte inferior se detalla la respuesta que fue enviada a Mercado Libre, y la fecha y hora en que fue enviada. En caso de que la respuesta enviada haya sido exactamente la respuesta generada por la plataforma, se leerá la leyenda: Respuesta generada automáticamente por Botmeni. Caso contrario, se visualizará la respuesta enviada a Mercado Libre con las modificaciones que tu tienda haya realizado.
{{< figure width="840px" height="600px" src="/images/general/historico11.png" >}}
5. Cada respuesta tiene disponible en la esquina superior derecha la acción Visualizar.
{{< figure width="840px" height="600px" src="/images/general/historico12.png" >}}
Al presionar la acción Visualizar se desplegará el chat completo de interacción con el usuario y también tendrás disponible el contenido de la publicación.
