![image](https://user-images.githubusercontent.com/85137398/125888871-bc5bd21b-5eef-4e80-9e1f-ff8b16d97d36.png)

# Práctica de Laboratorio 4 

1. OBJETIVOS

*General* 

- Aplicar el teorema de superposicion para determinar los valores de voltaje en ciertas ramas de un circuito electronico y hacer uso de la tecnica de superposicion donde una fuente de voltaje se realiza corto circuito para trabajar con un solo de voltaje.

*Especificos*

- Identificar y Aplicar todos los conceptos teóricos basados en las leyes de Kirchhoff y la ley de Ohm, para obtener el voltaje Va, la corriente Ix y anotar los valores analíticos en la tabla de comparación.

- Calcular con el voltimetro y amperimetro en la simulacion la corriente Ix, el voltaje Va y comparar los valores con los resultados que se obtengan mediante el analisis algebraico.

- Experimentar todo el funcionamiento del circuito tomando en cuenta que por el teorema de superposicion se puede hacer 0 a una de las dos fuentes de voltaje.

2. MARCO TEORICO

![image](https://user-images.githubusercontent.com/85137398/125898322-89837123-8119-4a5b-80e3-7262da4d22ae.png)

3. EXPLICACIÓN DEL PROCESO

- Material y equipo requerido

![image](https://user-images.githubusercontent.com/85137398/125888278-f792207a-e0ec-4757-9fee-53b6a6e166a2.png)

- Descripcion de equipo y material

Protoboard: Un protoboard es una placa de pruebas en la que se pueden insertar componentes electrónicos y cables, donde se puede ensamblar un circuito sin la necesidad de soldar ningún componente. El protoboard tiene agujeros conectados entre sí, por medio de pequeñas láminas metálicas.

Resistores: Una resistencia o resistor al componente electrónico diseñado para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

Fuente de voltaje: En electrónica, el elemento activo que puede transferir energía se llama fuente de voltaje.

Multímetro digital: Un multímetro digital es una herramienta que sirve para medir dos o más valores eléctricos, principalmente tensión (voltios), corriente (amperios) y resistencia (ohmios).

- Armado del circuito

I. Escoger las fuentes de energia de 20v y 12v respectivamente.

![image](https://user-images.githubusercontent.com/85137398/125888352-b6be2483-7187-4275-9572-c3ed311bd0e8.png)

II. Escoger correctamente los resistores con su codificación de colores.

![image](https://user-images.githubusercontent.com/85137398/125888388-504dd1dc-20c1-4991-8d3e-8cb8b4bb2b92.png)

III. Conectar el circuito en base al diagrama de conexión.

- Diagrama esquemático

![image](https://user-images.githubusercontent.com/85137398/125888418-4402cb41-e7f0-4886-b760-af908a84440c.png)

- Conexión del circuito

![image](https://user-images.githubusercontent.com/85137398/125888508-d2c9f735-353f-4bc7-b7f7-9e945d587f48.png)

IV. Procedemos a medir con las dos fuentes conectadas, mida el voltaje VA y la corriente I_x con los respectivos instrumentos de medicion como voltimetro y amperimetro.



A continuacion calculamos los valores teóricos de voltaje y corriente en el circuito  para completar la siguiente tabla.

4. RESPUESTAS A INTERROGANTES Y CÁLCULO DEL ERROR

4.5.2. Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

El voltaje total entre las dos fuente es:

VAtotal = VA'-VA''

VAtotal = 7,48V - 6,52V

VAtotal = 0,96V

La Corriente total entre las dos fuente es:

IXtotal = Ix'+Ix''

IXtotal = 0 + 25,5 mA

IXtotal = 25,5 mA

![image](https://user-images.githubusercontent.com/84390686/125913717-e3ad7a2e-cce5-4d86-a1b7-dfb59eeff1cb.png)

4.5.3. Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

Realizamos haciendo 0 a la fuente de voltaje de 12 V

![image](https://user-images.githubusercontent.com/84390686/125914838-60be0ba9-6461-4969-a1b6-3e78bc64e943.png)

Req 1 = 597,35

Req 2 = 1597,35 

V1 = VT * Rx / RT

V1 = 20 * 597,35/1597

V1 = 7,48 V

V1 = VA' = 7,48 V

Ix = 0

![image](https://user-images.githubusercontent.com/84390686/125913803-73d62dc7-2d51-441c-9cae-a5968f4d1204.png)

4.5.4. Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/84390686/125915022-a924f3b8-9560-4820-80c9-60bdc2de9025.png)

Req 1 = 687,5

Req 2 = 1507,5

Req 3 = 358,29

IT = 12/358,29 = 0,03349 A

Ix = 12 / 470 = 0,025531 A 

I1 = IT – Ix

I1 = 0,033549 – 0,025531

I1= 0,00796 A  = 7,96 mA

VA'' = I1 * 820

VA'' = 0,00796 *820

VA'' = 6,52 V


![image](https://user-images.githubusercontent.com/84390686/125913858-5b54b459-b2a9-43ea-ab64-ea39502d4137.png)

Tabla 4.1. Medición de voltaje aplicando superposición.

![image](https://user-images.githubusercontent.com/84390686/125913909-e53cb660-79cd-488a-8451-47ed1428d7a8.png)

Tabla 4.2. Medición de corriente aplicando superposición.

![image](https://user-images.githubusercontent.com/84390686/125913956-21d03c68-a682-4abb-b5cb-f785cc0b4739.png)

4.5.5. Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus
conclusiones.

Para calcular el porcentaje de error de las mediciones, se tiene en cuenta la siguiente fórmula:

![image](https://user-images.githubusercontent.com/84390686/125915849-61331f5c-667b-413d-b35c-59ba54711bdc.png)

Y obtenemos los resultados con el margen de error de los resultados analíticos y los resulados simulados:

![image](https://user-images.githubusercontent.com/84390686/125917709-3d380593-09ac-4dab-95b9-ebf08076705a.png)

5. VIDEO

6. CONCLUSIONES

-	Con la información recolectada y los resultados obtenidos del circuito electrónico dado llegamos al cierre con la aplicación correcta del teorema de superposición.

- Los conocimientos obtenidos acerca de los conceptos teóricos nos ayudan a obtener el voltaje Va y la corriente Ix con la aplicación de superposición.

7. BIBLIOGRAFÍA

- CaraKenio (8 de noviembre de 2019). Principio de superposición – Análisis de circuitos eléctricos. from https://dademuch.com/2019/11/08/principio-de-superposicion-analisis-de-circuitos-electricos/

- Wikipedia (20 Junio de 2021). Teorema de superposición from. https://es.wikipedia.org/wiki/Teorema_de_superposici%C3%B3n
