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

Cuando la fuente de voltaje V2 = 0

![image](https://user-images.githubusercontent.com/93958596/148107988-1567e662-2d8b-4cd9-bccd-a8ce0c0f82e7.png)

Para hallar la resistencia total:

Req1 = 820 Ω + 470 Ω = 1290 Ω = 1.29 kΩ

1/Req2 = 1/1.29 kΩ + 1/2.2 kΩ = 1.23 kΩ

Req2 = 1/1.23 kΩ = 0.813 kΩ

RT = 0.813 kΩ + 1 kΩ = 1.813 kΩ

Aplicando la ley de OHM se halla la corriente total:

IT = Vs / RT = 20 V / 1.813 kΩ = 11.03 mA

Hallamos la corriente en la resistencia de 2.2 kΩ (I1) con la fórmula de divisor de corriente:

I1 = (0.813 kΩ / 2.2 kΩ) * 11.03 mA = 4.08 mA

Aplicando la ley de las corrientes de Kirchoff, hallamos la corriente que circula por la resistencia de 820 Ω que, en este caso es la misma corriente Ix:

IT – I1 – Ix = 0, entonces: Ix = IT – I1 = 11.03 mA – 4.08 mA = 6.95 mA

Ahora hallamos el voltaje VA:

VA = 6.95 mA * 0.82 kΩ = 5.699 V = 5.7 V

Pero como el voltaje está en sentido contrario a como circula, VA = -5.7 V y la corriente es Ix = 6.95 mA

Cuando la fuente de voltaje V1 = 0

![image](https://user-images.githubusercontent.com/93958596/148107958-bb31e687-2a92-48fb-b828-430bf3086526.png)

Para hallar la resistencia total:

1/Req1 = 1/1 kΩ + 1/2.2 kΩ = 1.45 kΩ

Req1 = 1/1.45 kΩ = 0.69 kΩ

Req2 = 0.82 kΩ + 0.69 kΩ = 1.51 kΩ

1/RT= 1/1.51 kΩ + 1/0.47 kΩ = 2.79 kΩ

RT = 1/2.79 kΩ = 0.36 kΩ

Aplicando la ley de OHM se halla la corriente total:

IT = Vs / RT = 12 V / 0.36 kΩ = 33.33 mA

Hallamos la corriente Ix con la fórmula de divisor de corriente:

Ix = (0.36 kΩ / 0.47 kΩ) * 33.33 mA = 25.53 mA

Aplicando la ley de las corrientes de Kirchoff, hallamos la corriente (IA) que circula por la resistencia de 820 Ω

IT – IA – Ix = 0, entonces: IA = IT – Ix = 33.33 mA – 25.53 mA = 7.8 mA

Aplicando la ley de OHM hallamos el voltaje VA:

VA = 7.8 mA * 0.82 kΩ = 6.396 V = 6.4 V

Entonces VA = 6.4 V y la corriente Ix = 25.53 mA 

Realizando la suma algebraica entre los voltajes encontrados:

VA = 6.4 V – 5.7 V = 0.7 V = 700 mV

Realizando la suma algebraica entre las corrientes encontradas:

Ix = 25.53 mA + 6.52 mA = 32.05 mA

![image](https://user-images.githubusercontent.com/93958596/148009826-f2fb4d89-ca6c-434d-ad17-333e018610b2.png)

***

**6. Cálculo de error**

![image](https://user-images.githubusercontent.com/94011974/170057592-12d7c136-22cd-4cac-9532-0e92eb81f1b9.png)

![image](https://user-images.githubusercontent.com/105259459/176825460-132084ac-7bc0-4178-a635-4e078e5efa77.png)

***

**7. Vídeo**

***

**8. Conclusiones**

- A partir de lo investigado anteriormente, se puede concluir que el Teorema de Superposición, se utiliza cuando tenemos varias fuentes de voltaje o de corriente, se puede determinar el voltaje y la corriente algebraicamente, por la ley de ohm, leyes de Kirchhoff, métodos de mallas, tensiones en los nodos, etc. Las fuentes de voltaje igualadas a 0 equivale a un cortocircuito y las fuentes de corriente igualadas a 0 equivalen a circuito abierto, por lo que se les reemplaza respectivamente.

- Como se ha podido observar se realizó el cálculo de las medidas de voltaje, y de corriente, se construyó el circuito indicado y con la ayuda de un multímetro se tomó las medidas experimentales indicadas, después en Tinkercad se hizo una simulación del circuito obteniendo las medidas de voltajes y corrientes simuladas, finalmente se calculó el voltaje y la corriente utilizando el Teorema de Superposición, primero realizamos el circuito cuando V2=0 y hallamos la corriente y el voltaje por la ley de ohm y divisor de voltaje ohm, cuando V1=0 realizamos el mismo proceso que en V2 para hallar su voltaje y corriente.

- En la justificación del video se pude observar la construcción del circuito y su funcionamiento, se puede ver como se toman las medidas indicadas, también la construcción del circuito en el simulador de Tinkercad y su toma de medidas mediante simulación, se explica el análisis que se realizó para el Teorema de Superposición.

- Analizando el porcentaje de error, se concluye que el voltaje total se encuentra bien calculado y la variación mínima del error entre los datos calculados y los simulados es por los decimales que son tomados en cuenta en los cálculos realizados, mientras que el porcentaje de error entre los valores calculados y experimentales es mayor porque se conoce que los circuitos experimentales se ven afectados por distintos factores.
***

**9. Bibliografía**

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

García, A. (29 de marzo de 2021). Ley de corriente de Kirchhoff: Análisis de nodos. Panamahitek. Recuperado de http://panamahitek.com/ley-de-las-corrientes-de-kirchhoff-metodo-de-nodos/

***

10. Rubrica

![image](https://user-images.githubusercontent.com/94011974/169427061-265123c2-f557-4b9a-9ef6-5a545e89aff2.png)
