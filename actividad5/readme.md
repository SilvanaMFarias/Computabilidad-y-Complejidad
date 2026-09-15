## Actividad 5

## TP Máquina de Turing Universal

<p>1 - ¿Por qué se dice que una MTU es capaz de simular cualquier Máquina de Turing? </p>

<p>2 - Suponer que se tiene una MT M que acepta todas las cadenas que terminan en 01. Indicar qué debería hacer una MTU con las siguientes entradas. Explicar en cada caso si la MTU acepta o rechaza y por qué</p>

* U(⟨M⟩,1101)
* U(⟨M⟩,100)
* U(⟨M⟩,01)
* U(⟨M⟩,111)

<p>3 - Dada la siguiente MT M:</p>


|Q	|0|	1|
|:---:|:---:|:---:|
|q0	|(q1,1,R)	|(q1,0,R)|
|q1	|(qf,0,R)	|(qf,1,R)|
|qf|	-|	-|

<p>a) Explicar que hace M</p>
<p>b) Explicar qué información debería recibir una MTU para poder simular M</p>
<p>c) Codificar la cintar de MTU sabiendo que configuración de la cinta de MT M es 1 q0 0 1 1</p>
<br>
<hr>
<hr>

#### 1 - Codificación de una máquina simple

* Definir una máquina *M* que ...
* Codificar sus estados, símbolos y transiciones en forma numérica

#### 2 - Simulación básica

* Implementar en Python un programa que reciba
  
  - La codificación de una máquina 
    <math xmlns="http://www.w3.org/1998/Math/MathML">
      <mi>M</mi>
    </math>

  - Una cadena de entrada 
    <math xmlns="http://www.w3.org/1998/Math/MathML">
      <mi>w</mi>
    </math>

* El programa debe simular paso a paso la ejecución de
  <math xmlns="http://www.w3.org/1998/Math/MathML">
    <mi>M</mi>
  </math> 
    sobre
  <math xmlns="http://www.w3.org/1998/Math/MathML">
    <mi>w</mi>
  </math>

#### 3 - Pruebas de funcionamiento
* Probar la simulación con diferentes entradas

* Documentar los resultados

#### 4 - Informe final
* Explicar la codificación utilizada

* Mostrar ejemplos de ejecución

* Reflexionar sobre la relación entre la MTU y las computadoras modernas