---
weight: 1410
title: "Test: prueba cómo contesta Botmeni las preguntas de tus clientes"
description: "Prueba cómo contesta Botmeni las preguntas de tus clientes"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---

La plataforma cuenta con una sección especialmente diseñada para que puedas experimentar tú mismo cómo Botmeni contesta las preguntas de tus clientes. <br></br>
Esta sección es una gran aliada a la hora de obtener el resultado que más se acerque a tus necesidades. Por un lado, con ella puedes hacer todas las preguntas que necesites lo que te permitirá detectar, por ejemplo, puntos a ajustar en el contenido de tu publicación o que sería conveniente ampliar. Además, podrás conocer cómo se comporta el bot según las distintas configuraciones que vayas aplicando, tanto sobre el comportamiento de respuesta como la personalización de textos o centros de distribución, hasta encontrar la óptima para tu tienda.<br></br>
Las preguntas realizadas en esta sección son sólo de prueba dentro de nuestra plataforma, y nunca llegarán a Mercado Libre.

### Realizar preguntas de prueba

Para realizar preguntas de prueba:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página <https://prod.botmeni.com/login>.
2. Haz clic en Test.
{{< figure width="140px" height="100px" src="/images/general/test.png" >}}
3. En la parte superior de la pantalla tendrás disponible en primer lugar el recuadro donde ingresar el ID o URL de la publicación sobre la que deseas realizar la pregunta. Te explicamos cómo conocer dicho dato en la sección [Conocer el ID o la URL de una publicación](../Prueba_botmeni/ID_URL_del_producto.md).
{{< figure width="840px" height="600px" src="/images/general/test2.png" >}}
4. Otra forma de ingresar la publicación, es presionando la lupa ubicada a la derecha del campo.
{{< figure width="840px" height="600px" src="/images/general/buscador_ìtems_prueba1.png" >}}
5. Al presionar la lupa aparecerá el modal Busca un ítem. Ingresa el título de la publicación deseada. El buscador desplegará el listado de ítems de tu tienda que concuerdan con las palabras ingresadas. Selecciona el que corresponda.
{{< figure width="840px" height="600px" src="/images/general/buscador_ìtems_prueba2.png" >}}
6. Así, una vez definido el ítem, a continuación ingresa en el siguiente recuadro la pregunta.
{{< figure width="840px" height="600px" src="/images/general/test3.png" >}}
5. Presiona ANALIZAR.
{{< figure width="700px" height="500px" src="/images/general/test4.png" >}}
6. Se procesará la pregunta para la publicación ingresada, según la configuración de comportamiento que esté definida. Se desplegará la respuesta con toda la información disponible, igual que si la pregunta se hubiera ingresado desde Mercado Libre.
{{< figure width="840px" height="600px" src="/images/general/test5.png" >}}

### Información disponible para una pregunta de prueba.
A continuación se describirá la información que puedes visualizar para cada pregunta de prueba.
1. En la sección superior se detallan:
{{< figure width="840px" height="600px" src="/images/general/test6.png" >}}
    1. Título de la publicación. Presionando sobre la misma se abrirá en una nueva ventada la publicación en Mercado Libre.
    2. Información sobre la publicación: Precio, stock y estado. 
    3. Id: id ítem corresponde al id de la publicación asociada a la pregunta (en caso de que corresponda también se mostrará el SKU y/o el GTIN) y debajo el ID de la pregunta.
    4. Estado: Hace referencia al estado de la pregunta. Los estados posibles son: Procesada, No procesada, Recibida, Eliminada y Error.
    5. Subestado: Cada pregunta tiene un subestado. En el caso de la imagen, el subestado señala que la respuesta fue procesada y hubiera quedado pendiente para que la revises y envías a Mercado Libre (manual) dado que así estaba definido el comportamiento para las preguntas relacionadas con stock.
    6. Indica la configuración que definió el comportamiento de respuesta. Por ejemplo, para el caso de la imagen, La respuesta quedó con estado Procesada y Subestado Manual por stock (es decir, se generó la respuesta pero no se enviará en forma automática), dado que la tienda tiene definido ese comportamiento en la sección Configuraciones Particulares, para las preguntas relacionadas con stock
2. En la sección central se visualiza la pregunta de prueba ingresada, con su fecha y hora, y la respuesta generada por nuestro modelo, con la fecha y hora en que fue generada, si el comportamiento de respuesta está configurado para que la misma se genere.
{{< figure width="840px" height="600px" src="/images/general/test7.png" >}}
3.  A continuación tienes la posibilidad de calificar la calidad de nuestra respuesta presionando los círculos de color verde, amarillo y rojo en función de tu evaluación: Respuesta excelente, Respuesta mejorable y Respuesta incorrecta. Y en el espacio Calificación puedes ingresar un comentario asociado a la calificación que acabas de realizar, que nos ayudará a implementar las mejoras que sean necesarias.
{{< figure width="840px" height="600px" src="/images/general/test8.png" >}}



