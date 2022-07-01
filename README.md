# CIRCUITOS-LAB-4

![image](https://user-images.githubusercontent.com/105686218/169063263-fec46540-3f80-4755-af10-c6e466470348.png)        

## CARRERA DE ELECTRONICA Y AUTOMATIZACION

## FUNDAMENTOS DE CIRCUITOS ELECTRICOS

## SEGUNDO PARCIAL

***

**1. Objetivos**

***

   **1.1. Objetivo General** 

Comprobar el cumplimiento del Teorema de Superposición, mediante el análisis de los circuitos eléctricos, las simulaciones y las prácticas de laboratorio físicas, para afianzar los conocimientos adquiridos en clase.

***

  **1.2. Objetivos Específicos:**

- Construir mapas conceptuales que resuman el Teorema de Superposición, a partir de una búsqueda bibliográfica

- Calcular las medidas de voltajes y corrientes de los nodos del circuito, mediante la construcción del circuito de forma física, en el simulador de Tinkercad y analíticamente utilizando superposición.

- Justificar el desarrollo del laboratorio, mediante la presentación de un video, en el que se explique la resolución del Teorema de superposición y el funcionamiento del circuito.

- Comparar los resultados que se obtienen analíticamente, simuladamente y experimentalmente


***

**2. Marco Teórico**

![image](https://user-images.githubusercontent.com/105686218/176813453-867b7216-02f1-4993-84f5-b93a04a84add.png)

![image](https://user-images.githubusercontent.com/105686218/176813481-a29b626a-9777-4c9b-89f9-82b04e8e8cc0.png)

![image](https://user-images.githubusercontent.com/105686218/176813524-2a1b19fc-ba81-4967-9212-5d5754615b3b.png)

![image](https://user-images.githubusercontent.com/105686218/176813551-52126556-2ad6-42df-9a5c-17d835e0bdca.png)

![image](https://user-images.githubusercontent.com/105686218/176813599-23eeaffd-1ce8-4c9b-b32e-72b131799e7c.png)


***

**3. Requerimientos previos**

Circuito armanado

![image](https://user-images.githubusercontent.com/93958596/148009620-469c75af-838b-486b-acd7-5c3ed40ff48c.png)

Medicion de Va

![image](https://user-images.githubusercontent.com/93958596/148009630-280717ef-b4ff-4bc8-9dcb-8dc1530fd4ba.png)

Medicion de Ix

![image](https://user-images.githubusercontent.com/93958596/148009653-de50a538-18a1-485e-844b-068d05861b64.png)

Medicion de Va con conrto circuito a la derecha

![image](https://user-images.githubusercontent.com/94011974/176892822-14eb7ede-6a8a-4214-aa28-4943af829b7d.png)

Medicion de Ix con corto circuito a la derecha 

![image](https://user-images.githubusercontent.com/94011974/176892836-99883fc7-f020-4cde-a1a6-3398466e40b1.png)

Medicion de Va con corto circuito a la izquierda

![image](https://user-images.githubusercontent.com/93958596/148009682-95a09dcb-4ca6-4eca-97e8-bd6e1121caac.png)

Medicion de Ix con corto circuito a la izquierda

![image](https://user-images.githubusercontent.com/93958596/148009696-f302f679-5073-410f-974e-69ce7722ba12.png)

![image](https://user-images.githubusercontent.com/94011974/176794631-1ef99fbb-93f3-4d1b-a699-8fc0c9adfca4.png)

![image](https://user-images.githubusercontent.com/94011974/176794642-f23e68fd-0b88-4ed1-a5ff-0613f08cc1a7.png)

![image](https://user-images.githubusercontent.com/94011974/176794655-e5bf63ce-764e-4f16-8ca6-6fa0f7efc045.png)

![image](https://user-images.githubusercontent.com/94011974/176794668-bc29ce89-a43d-452e-bc64-011d661b9547.png)

![image](https://user-images.githubusercontent.com/94011974/176794696-c2ae0460-1482-460c-8628-d23c570e3279.png)

![image](https://user-images.githubusercontent.com/94011974/176794678-d46bd41b-d53a-4b36-a5df-0e384a8b7591.png)

***

**4. Materiales y equipos requeridos**

![image](https://user-images.githubusercontent.com/93958596/148009719-8a28b48f-108e-4c44-b460-d238f9d1a56a.png)

***

**5. Procedimiento**

![image](https://user-images.githubusercontent.com/94011974/176898306-cbaa1832-5cf9-4fd7-9edb-0117393ffc90.png)

- Eliminando el voltaje de 12 V

![image](https://user-images.githubusercontent.com/94011974/176898376-3b87da6e-90ec-4a68-8c18-905ac2759131.png)

Puesto que la resistencia de 470 ohm esta en cortocircuito, sale de nuestro circuito original y ya no interviene en el análisis

Sacando resistencia equivalente

Re = ((0.82)(2.2))/(0.82+2.2) = 0.597 k[ohms] + 1 k[ohms] = 1.597 k[ohms]

It = V/R = 20/1.597 = 12.523 mA

Usando divisor de corrientes

Ia = (2.2/(2.2+0.82))*12.523 = 9.12 mA

Usando ley de ohm para hallar Va

V = IR

Va = 9.12 * 0.82

Va = 7.48 V

Ix = 0

- Eliminando el voltaje de 20V

![image](https://user-images.githubusercontent.com/94011974/176899169-e913fda9-f372-421f-a7d1-3be1de8df7c8.png)

Re = (1)(2.2)/(3.2) = 0.69 + 0.82 = 1.51

RT = (1.51)(0.47)/(1.51+0.47) = 0.35829

Ley de Ohm

IT = 12/0.35829 = 33.429

Divisores de corriente

Ix = ((1.5075)/(1.5075+0.47)) * 33.429 = 25.53 mA

IRe = ((0.47)/(1.5075+0.47))*33.429 = 7.96

Usando ley de ohm para halla Va

Va = 7.96*0.820 = 6.53V

- Teorema de superposición

Calculo de voltaje Va

Va = Va1 + Va2 = 7.48 - 6.53 = 0.95 V

Calculo de corriente Ix

Ix = Ix1 + Ix2 = 25.5mA + 0 = 25.5mA

***

Respuesta a interrogantes

4.5.1. Arme el circuito que se muestra en la figura 4.1.

![image](https://user-images.githubusercontent.com/94011974/176900606-affd1773-5ca4-414b-9f5d-afe4f3a116ac.png)

4.5.2. Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/94011974/176900726-5059b599-47ed-4565-96e3-f7c3c3542f56.png)

4.5.3. Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/94011974/176900766-dd157366-cac2-4138-b9b2-d6e4850f0e3f.png)

4.5.4. Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/94011974/176900790-1fefa6c2-9d2c-4ed3-b6c9-c9a03a7e7314.png)

Tabla 4.1. Medición de voltaje aplicando superposición.

![image](https://user-images.githubusercontent.com/94011974/176900839-653ca3ab-6d92-467c-84ce-bd1061466b97.png)

Tabla 4.2. Medición de corriente aplicando superposición.

![image](https://user-images.githubusercontent.com/94011974/176900872-aa90e80c-eb2d-4645-8393-1155572f3261.png)

4.5.5. Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones.

Como se observa, en los valores tanto de la tabla 4.1, como los de la tabla 4.2, los valores calculados y los valores medidos en el simulador no difieren, es decir son iguales y por lo tanto no existe ningun error.

***

**7. Cálculo de error**

![image](https://user-images.githubusercontent.com/94011974/170057592-12d7c136-22cd-4cac-9532-0e92eb81f1b9.png)

![image](https://user-images.githubusercontent.com/105259459/176933690-f9c1b1f6-5120-4188-9f57-1c6749720c53.png)

***

**8. Vídeo**

https://www.youtube.com/watch?v=QRnXTnPeEh0

***

**9. Conclusiones**

- A partir de lo investigado anteriormente, se puede concluir que el Teorema de Superposición, se utiliza cuando tenemos varias fuentes de voltaje o de corriente, se puede determinar el voltaje y la corriente algebraicamente, por la ley de ohm, leyes de Kirchhoff, métodos de mallas, tensiones en los nodos, etc. Las fuentes de voltaje igualadas a 0 equivale a un cortocircuito y las fuentes de corriente igualadas a 0 equivalen a circuito abierto, por lo que se les reemplaza respectivamente.

- Como se ha podido observar se realizó el cálculo de las medidas de voltaje, y de corriente, se construyó el circuito indicado y con la ayuda de un multímetro se tomó las medidas experimentales indicadas, después en Tinkercad se hizo una simulación del circuito obteniendo las medidas de voltajes y corrientes simuladas, finalmente se calculó el voltaje y la corriente utilizando el Teorema de Superposición, primero realizamos el circuito cuando V2=0 y hallamos la corriente y el voltaje por la ley de ohm y divisor de voltaje ohm, cuando V1=0 realizamos el mismo proceso que en V2 para hallar su voltaje y corriente.

- En la justificación del video se pude observar la construcción del circuito y su funcionamiento, se puede ver como se toman las medidas indicadas, también la construcción del circuito en el simulador de Tinkercad y su toma de medidas mediante simulación, se explica el análisis que se realizó para el Teorema de Superposición.

- Analizando el porcentaje de error, se concluye que el voltaje total se encuentra bien calculado y la variación mínima del error entre los datos calculados y los simulados es por los decimales que son tomados en cuenta en los cálculos realizados, mientras que el porcentaje de error entre los valores calculados y experimentales es mayor porque se conoce que los circuitos experimentales se ven afectados por distintos factores.
***

**10. Bibliografía**

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

García, A. (29 de marzo de 2021). Ley de corriente de Kirchhoff: Análisis de nodos. Panamahitek. Recuperado de http://panamahitek.com/ley-de-las-corrientes-de-kirchhoff-metodo-de-nodos/

***

11. Rubrica

![image](https://user-images.githubusercontent.com/94011974/169427061-265123c2-f557-4b9a-9ef6-5a545e89aff2.png)
