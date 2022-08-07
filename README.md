# Informe-Laboratorio-Extra

Universidad de las Fuerzas Armadas - ESPE

Fundamentos de Circuitos Eléctricos

1. Objetivos

Objetivo General

Resolver los circuitos eléctricos presentados por medio de los Teoremas de superposición, Thevenin y transferencia de máxima potencia con la finalidad de obtener los valores solicitados.

Objetivos Específicos

•	Elaborar los circuitos eléctricos en el simulador de Tinkercad.

•	Resolver los circuitos eléctricos aplicando los teoremas correspondientes.

2. Marco teórico

Teorema de superposición

Cuando en un circuito se utilizan múltiples fuentes, el teorema de superposición proporciona un método de análisis

![image](https://user-images.githubusercontent.com/105565670/183274974-ddcd8ded-b2e4-4faf-a181-cc2658ee5781.png)

El método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias internas.

Por tanto, el Teorema establece:

En cualquier rama dada de un circuito con múltiples fuentes, la corriente puede calcularse al determinar en esa rama particular las corrientes producidas por cada fuente que actúa sola, con todas las demás fuentes reemplazadas por sus resistencias internas. La corriente total en la rama es la suma algebraica de las corrientes individuales presentes en dicha rama.

Los pasos para aplicar el teorema de superposición son:

Paso 1. Dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita.

Paso 2. Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito.

Paso 3. Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes.

Paso 4. Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la corriente resultante será la misma que la presentada por la cantidad más grande de las cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm.

Teorema de Thevenin

El teorema de Thevenin proporciona un método para simplificar un circuito a una forma equivalente estándar. Se utiliza para hacer más sencillo el análisis de circuitos complejos.

La forma Thevenin equivalente de cualquier circuito resistivo de dos terminales consta de una fuente de voltaje equivalente (VTH) y una resistencia equivalente (Rth)

![image](https://user-images.githubusercontent.com/105565670/183274995-6f665bbf-0f2f-48a0-9a6a-2a44bb63a20c.png)

Por tanto, se entiende como:

En un circuito eléctrico, el voltaje equivalente de Thevenin (VTH) es el voltaje de circuito abierto (sin carga) presente entre dos terminales de salida. 

La resistencia equivalente de Thevenin (RTH) es la resistencia total que aparece entre dos terminales en un circuito dado que tiene todas las fuentes reemplazadas por sus resistencias internas.

La importancia del teorema de Thevenin es que el circuito equivalente puede reemplazar al circuito original en cuanto a cualquier carga externa.

Los pasos para aplicar el Teorema de Thevenin son:

Paso 1. Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el circuito equivalente de Thevenin.

Paso 2. Determinar el voltaje (VTH) entre las dos terminales abiertas.

Paso 3. Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito y fuentes de corriente ideales abiertas).

Paso 4. Conectar VTH y RTH en serie para producir el equivalente de Thevenin completo del circuito original.

Paso 5. Reemplazar la carga eliminada en el paso 1 entre las terminales del circuito equivalente de Thevenin. Ahora se pueden calcular la corriente y el voltaje que haya en la carga utilizando solamente la ley de Ohm. Tienen el mismo valor que la corriente y el voltaje presentes en la carga del circuito original.

Teorema de transferencia de potencia máxima

El teorema de transferencia de potencia máxima es importante cuando se tiene que conocer el valor de la carga con la cual la fuente suministra la máxima potencia.

El teorema de transferencia de potencia máxima se fórmula como sigue:

Para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

La resistencia de la fuente, Rs, de un circuito es la resistencia equivalente vista desde la terminal de salida utilizando el teorema de Thevenin

![image](https://user-images.githubusercontent.com/105565670/183275019-d86b83ed-0544-4877-bacb-0e792731f514.png)

Para este teorema se usará las siguientes fórmulas:

![image](https://user-images.githubusercontent.com/105565670/183275024-23e6f893-cfbb-4664-b046-83669dd2fd78.png)

De tal forma, se puede calcular la potencia suministrada a la carga, determinando la potencia de carga máxima

3. Explicación del procedimiento

Circuito 1

![image](https://user-images.githubusercontent.com/105565670/183275039-5d5535a3-03f4-46ae-a04b-7576054a3415.png)

Elaboración del circuito

Materiales

Los materiales utilizados son

![image](https://user-images.githubusercontent.com/105565670/183275044-dad22acf-24a4-42d2-bd1f-45e435bd7beb.png)

Circuito armado

![image](https://user-images.githubusercontent.com/105565670/183275049-fb167b90-9e00-4f40-b877-28e63a85f54a.png)

Respuesta a interrogantes

Proceso

1. Desconecto la fuente de 16V y mido la corriente y el voltaje

![image](https://user-images.githubusercontent.com/105565670/183275053-de240d19-76c8-4205-9a46-aa1d6c16a18a.png)

2. Desconecto la fuente de 10V y mido la corriente y el voltaje

![image](https://user-images.githubusercontent.com/105565670/183275059-53b73a27-9eee-4a0e-8966-74c12da060c8.png)

Ahora con los datos obtenidos se calcula la corriente y voltaje en la resistencia de 12Ω

![image](https://user-images.githubusercontent.com/105565670/183275063-c150fd80-8433-415d-ad7c-90bbfced6d6e.png)

Como verificación, se mide la corriente y voltaje del circuito en la resistencia de 12Ω para constatar

![image](https://user-images.githubusercontent.com/105565670/183275065-fc687b55-6b93-4d6a-b1c5-c6ac336ea179.png)

Circuito 2

![image](https://user-images.githubusercontent.com/105565670/183275070-60ac29f8-23f0-4229-a356-4015f89f62ad.png)

Elaboración del circuito

Materiales

![image](https://user-images.githubusercontent.com/105565670/183275073-a498fc5d-8acf-4764-bb77-55c66a6203d3.png)

Circuito armado

![image](https://user-images.githubusercontent.com/105565670/183275076-c4689251-4b2d-4102-bc58-3d373b6f8a6d.png)

Respuesta a interrogantes

Proceso

1. Determino el voltaje de Thevenin

![image](https://user-images.githubusercontent.com/105565670/183275078-717fd902-15e6-4275-9ee8-6fd110b18c7b.png)

2. Determino la resistencia de Thevenin

![image](https://user-images.githubusercontent.com/105565670/183275082-b3622847-7412-4d03-9955-614a26302887.png)

3. Armo el circuito de Thevenin y mido la corriente en la resistencia de 5Ω

![image](https://user-images.githubusercontent.com/105565670/183275085-ea2cfdc1-a36c-4944-8890-b6f96d4143ea.png)

Verificación de la corriente en el circuito inicial

![image](https://user-images.githubusercontent.com/105565670/183275093-bbdf4de5-a308-4a5c-9543-dff4cbd7b360.png)

Circuito 3

![image](https://user-images.githubusercontent.com/105565670/183275098-b229c5c2-d181-4cd1-8d39-925e8eb6ad19.png)

Elaboración del circuito materiales

Materiales

![image](https://user-images.githubusercontent.com/105565670/183275108-1ea441bc-3939-47ef-ae70-8b024584bf71.png)

Circuito armado

![image](https://user-images.githubusercontent.com/105565670/183275110-f248ee51-0de8-410a-852f-d101221ce8ca.png)

1. Determino el voltaje de Thevenin

![image](https://user-images.githubusercontent.com/105565670/183275114-4450548f-fe14-4766-9488-02bab28ddaa5.png)

2. Determino la resistencia de Thevenin

![image](https://user-images.githubusercontent.com/105565670/183275118-978b0f58-7dfe-4412-b955-839e62a0f42c.png)

3. Armo el circuito de Thevenin para medir el voltaje y corriente, y aplicar la fórmula de la potencia, para obtener el valor solicitado

![image](https://user-images.githubusercontent.com/105565670/183275169-cb8df650-64f3-470b-b3f9-3f1e254ef9b4.png)


Con los datos obtenidos, calculo la potencia, siendo:

![image](https://user-images.githubusercontent.com/105565670/183275129-c697cfc9-4a4c-486d-b8f2-274acd89470a.png)

4. Resultados

Los valores calculados en cada proceso que se utilizó los teoremas, mantienen un margen de error milimétrico puesto que Tinkercad redondea a dos décimas, por ende los valores calculados mantienen su similitud.

5. Tinkercad

Link de tinkercad: https://www.tinkercad.com/things/0qm74Ywn6h1-bodacious-bombul/editel?sharecode=rHsJ51i9CJENvz2aa9dPEM6-WYKPe3RnxlRGuk1yoAw

6. Video

Link del video:

7. Conclusiones

•	Se realizó un correcto análisis y comprensión de los esquemas proporcionados para la correcta elaboración de los circuitos.

•	Se utilizó los teoremas solicitados en cada circuito correspondiente para resolver de manera efectivo el problema y obtener el valor solicitado.

8. Bibliografía

Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. México: Pearson Educación.
