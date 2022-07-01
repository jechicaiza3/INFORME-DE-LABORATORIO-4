# INFORME-DE-LABORATORIO-4

**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

Integrantes : Maycon Caisaguano, Jefferson Chicaiza, Steven Lopez

NRC: 7309

***Objetivo General***
- Analizar el voltaje y la corriente solicitados en los diferentes componentes de un circuito cerrado, mediante una práctica de laboratorio para comprender cómo funciona el teorema de superposición. 

***Objetivo Especificos***
- Conocer los conceptos del teorema de superposición
- Realizar un circuito en un protoboard siguiendo la estructura dada por el docente para analizar la corriente y voltaje mendiante el terema de superposición
- Medir  con el multimetro valores de las corrientes de las diferentes componentes. 
- Comparar los valores calculados con los valores medidos para  determinar mayor validez a nuestro analisis.

**2.MARCO TEORICO**

![image](https://user-images.githubusercontent.com/94098157/148092703-7cf771bb-70e3-4cf5-a565-177203117051.png)

**3.MATERIAL Y EQUIPO REQUERIDO**

![image](https://user-images.githubusercontent.com/94098157/148092643-5ea01713-f0e8-438f-b8f3-d41afa9938bf.png)

**4.EXPLICACIÓN DEL PROCEDIMIENTO**

*1. Arme el circuito que se muestra en la figura 4.1.*
![image](https://user-images.githubusercontent.com/94098157/148013029-77bb9111-813f-48e2-b2fb-0c0deec04a10.png)
![image](https://user-images.githubusercontent.com/94098157/148013120-8ab7cbfb-4e0f-433f-82da-57932aacf9cb.png)
Primeramente se muestra el circuito realizado en el simulador tinkercad en el que se observa todos los componentes que se especifican en el diagrama como son los resistores, cables, fuentes de voltaje y además la inicialización de la simulación.

*2. Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.*
![image](https://user-images.githubusercontent.com/94098157/148013189-94e328cf-02bc-48ca-9d7c-0cbac95b2932.png)
Pues aquí claramente se evidencia la respectivas mediciones de los elementos solicitados, como es la corriente en IX y el voltaje VA 

*3. Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.*

![image](https://user-images.githubusercontent.com/94098157/148013207-5d037f32-e633-4b24-998a-c1e1b32b42ef.png)
Pues mediante el teorema de superposición se muestra como el voltaje de 12v se hace cero y se hace las respectivas mediciones de las mismas componentes como la corriente en IX y el voltaje VA. 

*4. Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.*

![image](https://user-images.githubusercontent.com/94098157/148013232-30a20b1b-054b-478f-bb74-d09041a762a4.png)
De la misma manera, con el teorema de superposición se hace cero a la otra fuente de voltaje de 20V y siguiendo el mismo procedimiento en medir las mismas componentes como la corriente IX y el voltaje VA. 


*Clculo de la corriente IX y voltaje VA analiticamente.*

Pues primeramente se hace cero a la fuente de voltaje de 12V haciendo corto a su rsistencia equivalente y despues calculamos la resistencia total del circuito y su corriente.
![image](https://user-images.githubusercontent.com/94098157/148059554-d978328b-597f-4746-abcc-cb2214e067e5.png)
![image](https://user-images.githubusercontent.com/94098157/148073898-4a1bff2f-ada8-4b18-9b28-387e116a4e45.png)

Despues determinamos el voltaje en VA y la correinte Ix mediante el conceptos de un circuito paralelo y serie.
![image](https://user-images.githubusercontent.com/94098157/148099337-cacff086-c7a1-463d-9085-1266dd259011.png)

Es importante mencionar que en un circuito en serie el volataje cae y en un circuito en paralelo el valtaje se mantiene es por esa razon que que el voltaje en VA y el volaje en la rsistecia 2.2 k ohmios es el mismo, por otra parte en la corriente Ix es lo mas aproximado a cero ya que existe una conexion donde no ahy componentes.


De la misma manera, se hace cero a la otra fuente de voltaje de 20V.
![image](https://user-images.githubusercontent.com/94098157/148082186-fa9f9e29-7a54-47ee-82ee-ecf3016dee0b.png)

De la misma forma, determinamos la correinte total del circuito mediante el calculo de la reisistencia total del cicuito. 

![image](https://user-images.githubusercontent.com/94098157/148084518-9e457f6c-decf-4f27-9732-64f563c2db6b.png)

Despues determinamos la corriente y el voltaje solicitados. Pues para la corriente Ix se puede observar que la resistencia 470 ohmios esta conectada en paralelo con la fuente de voltaje, por lo tanto la reisitencia tiene el mismo volatje. 

![image](https://user-images.githubusercontent.com/94098157/148086300-a169b251-1fa9-47b7-bc7b-97d6b4765237.png)

Por último para calcular el voltaje solicitado podemos deteminar la corriente que pasa en por la resietncia de 820 ohmios mediante la resta de la corriente total con la corriente Ix y despues mediante la ley de ohm camcular el voltaje VA

![image](https://user-images.githubusercontent.com/94098157/148090000-f3ee4c5e-7383-4daf-acc6-0e64aea13060.png)

Finalmente, realizamos las respectivas sumas algebraicas.

![image](https://user-images.githubusercontent.com/94098157/148095243-f61c9725-04f0-41e8-bfec-b6698c8e3266.png)

Tabla de comparación entre las corrientes y voltajes. 

![image](https://user-images.githubusercontent.com/94098157/148092401-834c2b15-396b-4543-8967-36f1cb42aefd.png)

![image](https://user-images.githubusercontent.com/94098157/148092423-82f05628-c0e4-4664-af5c-46afbbcc250f.png)

**5. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

La comprobación del teorema de superposición nos ayudó de manera experimental como calculado a determinar que es un método eficiente para obtener los valores de voltaje y corriente de zonas específicas de un circuito.

![image](https://user-images.githubusercontent.com/94098157/148094825-bdb001e1-bf95-4a40-b878-336eaf488d69.png)

**6. VIDEO:**
https://youtu.be/b5u6fVsB-fI

**7. CONCLUSIONES**
  
- Se pudo observar que el teorema de superposicion es un metodo muy eficiente para determinar las correintes y voltajes especificos de un circuto cerrad. 
- Tener los conceptos claros en lo que ue se refiere a corriente y al definición del teorema de superposicion  nos ayudó a medir de forma precisa la correinte y voltaje en el circuito.
- Los valores analiticos, experimentales, simulados muestran una gran semejanza entre ellos, lo que signfica que la corriente y voltaje obtenidos son en cierta manera precisos.
 
**8. BIBLIOGRAFÍA**
Floyd, T. (2007). *Principios de circuitos electricos* (Ed. 8va). Pearson EDUCATION
