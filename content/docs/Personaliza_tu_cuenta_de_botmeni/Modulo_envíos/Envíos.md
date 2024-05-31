---
weight: 910
title: "Centros de Logística y distribución"
description: "Centros de Logística y distribución"
icon: "category"
color: "primary"
date: "2024-04-08T23:13:49-05:00"
lastmod: "2024-04-08T23:13:49-05:00"
draft: false
toc: true
---
En el módulo Envíos es posible establecer para cada uno de sus centros de distribución o transportadoras utilizadas por la empresa, los costos y tiempos de entrega para una ciudad y/o región específica. Dicha información será tomada en cuenta al momento de procesar las respuestas para productos que no estén configurados para enviarse por Mercado Envio.<br></br>
Este módulo se mostrará disponible si en la sección [Configuración](../../Personaliza_tu_cuenta_de_botmeni/Configuración_comportamiento_respuesta/Caracteristicas_generales.md) dentro del módulo Configuración, seleccionaste NO en la pregunta relacionada a si todos los envíos se realizan a través de Mercado Envío, para aquellos planes que lo incluyen.<br></br>
### Establecer un Centro de Distribución
Para configurar un Centro de distribución:
1. Inicia sesión con un usuario con tipo de rol ADMINISTRADOR, en nuestra página de login <https://prod.botmeni.com/login>.
2. Selecciona el módulo Envíos en el menú.
{{< figure width="140px" height="100px" src="/images/general/envio.png" >}}
3. Ingresa el nombre del Centro de Distribución.
{{< figure width="700px" height="500px" src="/images/general/envio2.png" >}}
4. Ubica en el mapa dónde se encuentra el centro de distribución. Te ayudará ingresar su dirección en el casillero: Definir Centro de distribución. Si necesitas corregir la posición del ícono del local, presiónalo y manteniéndolo presionado muévelo hasta la ubicación correcta.
{{< figure width="700px" height="500px" src="/images/general/envio3.png" >}}
5. A continuación, ingresa en el espacio definido como Agregar región, la región correspondiente al punto de entrega del producto, y selecciona la opción deseada dentro de las propuestas. Por ejemplo, en la imagen siguiente se registra la región Tacuarembó.
{{< figure width="700px" height="500px" src="/images/general/envio4.png" >}}
6. Se desplegará una nueva sección donde podrás ingresar los datos específicos de costos y tiempos de entrega para la región recién definida. 
{{< figure width="700px" height="500px" src="/images/general/envio5.png" >}}
7. La primera sección se denomina GENERAL, ya que contendrá información general para todos los productos de tu tienda. Despliega el combo Precio y selecciona en función de qué parámetro se establecerá el precio. Por ejemplo, kilómetro.
{{< figure width="700px" height="500px" src="/images/general/envio6.png" >}}
8. Luego detalla el valor del precio en función del parámetro recién seleccionado.
{{< figure width="700px" height="500px" src="/images/general/envio7.png" >}}
9. Ingresa la información que quieres brindar a tus clientes sobre los envíos a esta ubicación. También puedes ingresar los tiempos de entrega asociadas al área de entrega.
{{< figure width="700px" height="500px" src="/images/general/envio8.png" >}}
10. Presionando el botón + ubicado a la derecha de la palabra GENERAL, puedes ingresar los datos de costo y tiempos de entrega para una categoría o producto específico.
{{< figure width="700px" height="500px" src="/images/general/envio9.png" >}}
11. Selecciona la categoría o ingresa el producto deseado.
{{< figure width="700px" height="500px" src="/images/general/envio10.png" >}}
12. De igual manera que en la sección general, establece el parámetro de precio, el valor del mismo y los textos específicos con la información que deseas brindar a tus clientes.
{{< figure width="700px" height="500px" src="/images/general/envio11.png" >}}
13. Para conservar toda la información que has ingresado, presiona GUARDAR 
{{< figure width="700px" height="500px" src="/images/general/envio12.png" >}}
14. De ser necesario, puedes agregar una nueva región de entrega para el centro de distribución. Para ello, ingresa una nueva región dentro del recuadro Agregar región.
{{< figure width="700px" height="500px" src="/images/general/envio13.png" >}}.
15. Una vez ingresada la nueva región, puedes repetir los pasos recién detallados para ingresar la información correspondiente.
{{< figure width="700px" height="500px" src="/images/general/envio14.png" >}}

Es posible establecer para un mismo Centro de Distribución más de un área de entrega y, además, un punto de entrega puede estar incluido en más de un área de un mismo centro de distribución. A su vez, el punto de entrega puede quedar incluido en más de un centro de distribución. Si un punto de entrega quedara incluido en más de una zona o en más de un centro de distribución, y por lo tanto le correspondiera más de un costo/tiempo de entrega, se tomará para procesar la respuesta la información relacionada al área más específica asociada al punto de entrega que se está consultando y al centro de distribución más cercano al punto de entrega. Por ejemplo, si para el Centro de distribución 1 se hubiera ingresado un costo para el pasí Uruguay, y además se hubiera establecido otro costo para la región Tacuarembó (perteneciente a Uruguay), ante consultas sobre envío a la región Tacuarembó se utilizará para generar la respuesta la información asociada a la región Tacuarembó, priorizándolo sobre lo que se ingresó para la región Uruguay.<br></br>
Si el producto no está configurado en Mercado Libre para enviarse por Mercado Envío y su tienda tampoco tiene detallada la información en el módulo Envíos, la información que se tendrá en cuenta al momento de generar la respuesta es la detallada en las secciones Políticas Envío y Tiempo/demora dentro del módulo [Textos](../Textos/informacion_relevante_texto.md).

### Habilitar y deshabilitar un Centro de Distribución

Es posible habilitar o deshabilitar los centros de distribución que tengas ingresados en el módulo Envíos. Al deshabilitar un centro, la información ingresada en el mismo no será tenida en cuenta al momento de generar las respuestas.
Para habilitar un centro de distribución:
1. Selecciona el módulo Envíos en el menú.
{{< figure width="140px" height="100px" src="/images/general/envio.png" >}}
2. Presiona sobre el nombre del centro que deseas habilitar.
{{< figure width="700px" height="500px" src="/images/general/envio15.png" >}}
3. Selecciona la casilla Habilitar centro. 
{{< figure width="700px" height="500px" src="/images/general/envio16.png" >}}
4. El centro quedará habilitado.
{{< figure width="700px" height="500px" src="/images/general/envio17.png" >}}
5. Para deshabilitarlo, presiona sobre la casilla para desmarcarla.
{{< figure width="700px" height="500px" src="/images/general/envio18.png" >}}
6. La casilla desmarcada implica que el centro está deshabilitado.
{{< figure width="700px" height="500px" src="/images/general/envio19.png" >}}

La cantidad de centros de distribución que pueden estar habilitados varían en función del plan al que estés suscripto. Para conocer la cantidad de centros habilitados para tu plan visualiza los [Detalles de tu suscripción actual](../../Suscripcíon_y_Pagos/Tu_Suscripcion/Ver_detalles_suscripción_actual.md).





