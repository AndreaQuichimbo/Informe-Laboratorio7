# Informe-Laboratorio7

<div align="center">

# UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

AUTORES

Coba Flores Víctor Steve

Quichimbo Simba Andrea Estefania

Titoaña Tigse Leslie Brigitte

NRC
  
5412

INGENIERO

Ing. Darwin Omar Alulema Flores

# PRÁCTICA NO. 7. INDUCTOR Y CAPACITOR
  
</div>

# 1 OBJETIVOS

**1.1. OBJETIVO DE LA PRÁCTICA**

1.1.1. Objetivo general

1.1.2. Objetivos específicoso


**1.2. REQUISITOS PREVIOS**


**1.3. INFORMACIÓN GENERAL**

<div align="center">
  
**INDUCTOR Y CAPACITOR**

</div>

**Inductores**

Un inductor o bobina es un componente que almacena energía en forma de campo magnético.

**Usos y aplicaciones del inductor**

- Bobinado de electroimanes con CD.
- Los transformadores se utilizan principalmente para convertir una tensión a otra.
- Los motores de CD poseen inductores para generar los campos magnéticos necesarios para funcionar.
- Integran circuitos de filtrado para salidas de fuentes rectificadoras tanto pequeñas como de potencia.
- Inductores y capacitores se utilizan en circuitos de audio para filtrar o amplificar frecuencias específicas.
- En las fuentes de alimentación también se usan bobinas para filtrar componentes de corriente alterna, y solo obtener corriente continua en la salida.
- Se utilizan como filtros de línea telefónica, para eliminar las señales de alta frecuencia de banda ancha y se colocan en los extremos de los cables de señal para reducir el ruido.

**Capacitor**
  
Un condensador o capacitor es un dispositivo utilizado en electricidad y electrónica, capaz de almacenar energía sustentando un campo eléctrico. Aunque desde el punto de vista físico un condensador no almacena carga ni corriente eléctrica, sino simplemente energía mecánica latente; al ser introducido en un circuito se comporta en la práctica como capaz de almacenar la energía eléctrica que recibe durante la carga, a la vez que la cede de igual forma durante la descarga. Un condensador electrolítico es un tipo de condensador que usa un líquido iónico conductor como una de sus placas. Típicamente con más capacidad por unidad de volumen que otros tipos de condensadores, son valiosos en circuitos eléctricos con relativa alta corriente y baja frecuencia. Condensador de alta capacidad Los condensadores electroquímicos de doble capa, también conocidos como supercondensadores, supercapacitores, pseudocapacitores, ultracondensadores, ultracapacitores o simplemente EDLC por sus siglas en inglés, son dispositivos electroquímicos capaces de sustentar una densidad de energía inusualmente alta en comparación con los condensadores normales, presentando una capacitancia miles de veces mayor que la de los electrolíticos de alta capacidad.

**Usos y Aplicaciones del capacitor**
 
- Arranque de motores. 
- Fuentes de alimentación.
- Circuitos temporizadores.
- Filtros en circuitos de radio y TV.
- También son muy usados en los circuitos que deben conducir corriente alterna pero no corriente continua.
- Los condensadores electrolíticos pueden tener mucha capacitancia, permitiendo la construcción de filtros de muy baja frecuencia.
- En el caso de los filtros de alimentadores de corriente se usan para almacenar la carga, y moderar el voltaje de salida y las fluctuaciones de corriente en la salida rectificada.

| BASE	|CAPACITOR|	INDUCTOR |
|    :---:   |        :---:           | :---:               |
|Definición|El condensador almacena energía en forma de campo eléctrico.|Inductor almacena energía en forma de campo magnético.|
|Calculo de energia|La energía almacenada se calcula en términos de voltaje. es decir ½ CV2|La energía almacenada se calcula en términos de corriente. es decir ½ LI2|
|Flujo de corriente|	No hay flujo de corriente a través de las placas de condensadores. |	En una corriente inductora pasa a través de la bobina.|
|Comportamiento en circuito DC|	El condensador actúa como un aislante para el circuito de corriente continua.|	Inductor actúa como un conductor para el circuito de corriente continua.|
|Relación entre tensión y corriente.|En un circuito de corriente alterna, la tensión conduce la tensión en 90 grados.|En un circuito de corriente alterna, la corriente se retrasa en 90 grados.|
|Comportamiento de la corriente en el circuito de corriente continua.|	En un circuito de CC cuando el condensador se agrega en serie con una resistencia, la corriente inicialmente se vuelve alta pero luego cae a cero.|En un circuito de CC cuando el inductor se agrega en serie con una resistencia, el valor de la corriente es pequeño y luego aumenta con el tiempo.|
|Unidad|	Su unidad es Farad.	|Su unidad es Henry.|
|Los tipos|	Cerámica, electrolítica y tantalio son los tipos de condensadores.	|Inductor acoplado, multicapa, inductor de núcleo cerámico, inductor moldeado son los tipos de inductor.|
|Cortocircuito|	El condensador actúa como un cortocircuito para la corriente alterna.	|Es equivalente a un cortocircuito a la corriente continua.|
|Condición de estado estacionario|	El condensador actúa como un circuito abierto a la condición de estado estable en circuitos de CC.	|El inductor se comporta como un cortocircuito a la condición de estado estable en DC.|
|Resistir al cambio|	El condensador resiste el cambio de voltaje.|	Inductor resiste cambio en corriente.|
|Aplicaciones|	Condensador electrolítico en fuentes de alimentación de alto voltaje y donde se necesitan valores de alta capacidad.	|Los inductores se utilizan en radio, TV, estrangulaciones, bujías de automóviles, transformadores, etc.|

</div>

# 2 MARCO TEÓRICO

<div align="center">

![image](https://user-images.githubusercontent.com/84587172/131427951-2136c219-2222-417a-9b6f-52b9c1d5fbc8.png)

![image](https://user-images.githubusercontent.com/84587172/131428663-a679e27f-f2fd-4d2d-bb8b-0f2e600750c0.png)
  
</div>

# 3 MATERIAL Y EQUIPO REQUERIDO

<div align="center">
     
|**CANTIDAD**|       **MATERIAL O EQUIPO**      |
|    :---:   |              :---:               | 
|      1     |       Generador de señales       |
|      1     |            Fuente DC             |
|      1     |           Osciloscopio           |
|      1     |            Protoboard            |
|      1     |            Multímetro            |
|      1     |        Cables conductores        |
|      1     |  Resistencias, bobinas y capacitores |
  
</div>

# 4 EXPLICACIÓN DEL PROCEDIMIENTO

**4.5 PROCEDIMIENTO**

**1.- Construya en el protoboard el circuito mostrado en la Figura 1.**

**a. Utilice el osciloscopio para observar el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los valores pico de las ondas observadas.**

**b. Utilice un multímetro para medir el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los resultados.**

**c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la frecuencia entre los valores 0, 10, 50, 100, 500, 1000 . Anote los resultados.**

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/130623489-8bccecf9-30ac-45db-a751-3e54b440f7b7.png)

</div>

1.- Seleccionamos los materiales con los cuales realizaremos la práctica de acuerdo a los circuitos planteados.

<div align="center">
  
![image](https://user-images.githubusercontent.com/84587293/131436213-907134c5-1538-4589-bd1d-84643812a616.png)

</div>

2.- Construya el circuito mostrado en la Figura 1**

<div align="center">
  
![image](https://user-images.githubusercontent.com/84587293/131436306-e5dcfca7-96cd-4280-baa0-e50a1b29f534.png)

</div>

**a. Utilice el osciloscopio para observar el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los valores pico de las ondas observadas.**

Para 0 Hz

<div align="center">
  
![image](https://user-images.githubusercontent.com/84587293/131436649-29bed6f8-9e50-4e4c-bfc1-a6b155f81967.png)

 </div>

Para 10 Hz

<div align="center">

![image](https://user-images.githubusercontent.com/84587293/131436637-3b0edbe2-a71b-42e9-919a-e3aa37cdab84.png)

 </div>
 
Para 50 Hz

<div align="center">

![image](https://user-images.githubusercontent.com/84587293/131436748-efcca21c-b476-4b9b-b405-fec3e60eaa66.png)

 </div>

Para 100 Hz

<div align="center">
  
![image](https://user-images.githubusercontent.com/84587293/131436788-e36fb859-cb85-464e-88c2-b3d648019417.png)
  
 </div>
 
 Para 500 Hz
 
 <div align="center">
  
 ![image](https://user-images.githubusercontent.com/84587293/131436950-9c5eac36-f9a5-4c09-b92f-e4cd59c92697.png)

 </div>
 
 Para 1000 Hz
 
 <div align="center">
  
![image](https://user-images.githubusercontent.com/84587293/131436992-200bf221-f88d-40ae-a10c-b3abf9d84781.png)
  
</div>

**2.- Construya el circuito mostrado en la Figura 2**

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/130623626-5988844a-0064-4ff3-b36f-d32ea3009f16.png)

</div
 

**a. Utilice el osciloscopio para observar el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los valores pico de las ondas observadas.**

<div align="center">
  
![1](https://user-images.githubusercontent.com/84587172/131399089-419c269d-8859-4e80-a8db-326792320a2e.png)

![2](https://user-images.githubusercontent.com/84587172/131399102-3f722abe-2d67-4c70-a65c-e9a97ae04035.png)
    
![3](https://user-images.githubusercontent.com/84587172/131398975-05191b5c-6e1e-4211-8141-a969487dbcb8.png)

![4](https://user-images.githubusercontent.com/84587172/131399032-f4e7d703-0ee2-4059-b36e-262222aaeb5f.png)

![5](https://user-images.githubusercontent.com/84587172/131399041-32a5c6d7-ebb9-4153-af89-a91b2b515e03.png)

![6](https://user-images.githubusercontent.com/84587172/131399118-2334335e-2bae-42d3-a964-23370aa10437.png)

![7](https://user-images.githubusercontent.com/84587172/131399127-4d53fef0-7c51-4dbd-9826-0ea2d9f8e2cb.png)  

</div>

**b. Utilice un multímetro para medir el voltaje  variando la frecuencia entre los valores
de 0, 10, 50, 100, 500, 1000 . Anote los resultados.**

<div align="center">
  
![8](https://user-images.githubusercontent.com/84587172/131399259-d24761bd-8e05-4c22-a54a-88fb88d4bb9d.png)

![9](https://user-images.githubusercontent.com/84587172/131399262-8eabb68d-2ec1-4298-9653-e840dc5a55dc.png)

![10](https://user-images.githubusercontent.com/84587172/131399272-ac1dc29b-e593-4090-a4d8-3da781b7eb9f.png)

![11](https://user-images.githubusercontent.com/84587172/131399324-9d40b697-3186-4f7d-a7e2-d2b3bfdf93b7.png)

</div>

**c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la
frecuencia entre los valores 0, 10, 50, 100, 500, 1000 . Anote los resultados.**

<div align="center">
  
![12](https://user-images.githubusercontent.com/84587172/131399459-dd342c0f-bcd3-445a-8d89-3bac8e4f857a.png)

![13](https://user-images.githubusercontent.com/84587172/131399489-cb982e6d-11af-4fb4-8f2a-82325182ab27.png)

![14](https://user-images.githubusercontent.com/84587172/131399496-f5f080bd-9571-4b5d-badb-67b55d3df029.png)
  
</div>

**4.6 Análisis de resultados**

**1.- Para cada uno de los circuitos anteriores, elabore una tabla con los resultados de las diferentes mediciones de voltaje realizadas con el osciloscopio y multímetro. Compare y comente los resultados obtenidos tomando en cuenta las distintas frecuencias utilizadas.**

![tabla](https://user-images.githubusercontent.com/84587172/131404703-db3c8601-1e9e-4f2a-a6a3-9240c9c7b335.png)

**4.7 Preguntas**

**1.- ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?**

Dentro de un circuito la bobina y el capacitor en corriente continua pasan por dos fases conocidas como fase de transición y fase de continua, fase de estabilización se produce fenómenos que ayudan a describir curvas de carga del capacitor a una fase continua, la corriente en su fase de intensidad atraviesa el capacitor es igual a cero. los inductores al ser la corriente constante la caída de tensión sobre ellos es igual a cero, por lo que lo interpretamos como simplemente un cable en el circuito.

**2.- ¿Cómo se comportan la bobina y el capacitor en corriente alterna?**

El comportamiento de capacitores en corriente alterna depende de funciones que describan su comportamiento dentro del intervalo de tiempo definido. 𝑖(𝑡) = 𝐶 (𝑑𝑣(𝑡) 𝑑/𝑣). El capacitor representa como un elemento pasivo. Al existir una variación de la corriente en un circuito de corriente alterna es puede conocer los valores que tomaran las corrientes y la caída de tensión por medio de las funciones que describan a estas variables dentro del intervalo de tiempo definido. 𝑖(𝑡) = 𝐶 (𝑑𝑣(𝑡)/ 𝑑𝑣)

**3.- ¿Qué cree usted que ocurriría con el voltaje  y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?**

En el voltaje Vo dentro de lo circuitos analizados varía en función de la impedancia, es decir su menor o mayor al valor total de impedancia, 𝑍 = 𝑅 + 𝑗X.

**4.- ¿Qué son los valores eficaces de voltaje y corriente?**

Valores de voltaje y corriente son funciones oscilatorias descrita en función de seno y el coseno representadas por su amplitud y frecuencia, dichos valores aumentan al calcular la potencia.

# 5 VIDEO 

# 6 CONCLUSIONES 

-	El módulo implementado en el simulador Multisim, se pueda simular el comportamiento de las ondas de voltajes o ya sea de señales en las diferentes configuraciones de circuitos que se analiza en dicho caso.

-	Se concluyo que a medida que la señal de frecuencia va en aumento o en deceso, los valores de la constante de tiempo y del voltaje máximo varían y todo esto depende de la configuración del circuito, ya que la impedancia del capacitor o inductor está en función de la frecuencia, El tiempo es una constante indicando el tiempo en que se carga totalmente el capacitor. 

# 7 BIBLIOGRAFÍAS

ANÁLISIS DE CIRCUITOS Y SISTEMAS LINEALES. (s.f.). Obtenido de https://innovacionumh.es/Proyectos/P_19/Tema_1/UMH_07.htm
