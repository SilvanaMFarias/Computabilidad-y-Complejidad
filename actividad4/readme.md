## Actividad 4

## TP Máquina de Turing Calculable

<p>1 - Calcular la imagen especular de una cadena definida sobre {a,b}, es decir f(w)=reverso(w). Ejemplos: f(aabb)=bbaa y f(aba)=aba *</p>

<img src="./archivos/1.png" alt="MT1" width="800">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC1.jff)

<br>

<b>*Ejemplo*</b>

<p>Contenido inicial de la cinta</p>

<img src="./archivos/1Inicio.png" alt="Entrada 1" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/1Resultado.png" alt="Salida 1" width="350">

<br><br>

<p>2 - Duplicar una cadena de aes y bes en la cinta. Ejemplo: si la MT comienza con abbaa□ en su cinta, luego de procesar su programa debe terminar con abbaa□abbaa</p>

<img src="./archivos/2mejora.png" alt="MT3" width="850">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC2Mejora.jff)
<br>
<br>

<b>*Ejemplo*</b>

<p>Contenido inicial de la cinta</p>

<img src="./archivos/2Inicio.png" alt="Entrada 2" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/2Resultado.png" alt="Salida 2" width="350">

<br>
<br>

<p>3 - Se dispone de una cinta en la que hay un número m de 1s seguido de un número n ≥ m de Aes. Se desea definir una MT que cambie las primeras m Aes por Bes. Se supone que la cabeza de la cinta inicialmente está en el 1 más a la izquierda </p>

<img src="./archivos/3.png" alt="MT3" width="400">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC3.jff)

<br>

<b>*Ejemplo*</b>

<p>Contenido inicial de la cinta</p>

<img src="./archivos/3Inicio.png" alt="Entrada 3" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/3Resultado.png" alt="Salida 3" width="350">

<br>
<br>
<p>4 - Comprobar si dos palabras formadas con símbolos de Σ = {0, 1, 2} son iguales. Las dos palabras están separadas por el símbolo #</p>

En este ejercicio, el contenido final de la cinta estará dado por el contenido original, seguida de una letra 's' si las dos palabras son iguales, o seguida de una letra 'n' si las dos palabras no lo son.

<img src="./archivos/4_2.png" alt="MT4" width="900">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC4_2.jff)

<br>

<b>*Ejemplos*</b>

<div>a) 12#120 - Las palabras NO son iguales</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/4aInicio.png" alt="Entrada 4a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/4aResultado.png" alt="Salida 4a" width="350">

<br>

<div>b) 20#01 - Las palabras NO son iguales</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/4bInicio.png" alt="Entrada 4b" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/4bResultado.png" alt="Salida 4b" width="350">

<br>

<div>c) 012#012 - Las palabras SI son iguales</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/4cInicio.png" alt="Entrada 4b" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/4cResultado.png" alt="Salida 4b" width="350">

<br>
<br>

<p>5 - Sumatoria de (n + i) , con 1 ≤ i ≤ n, con n codificado en unario</p>

<p>6 - [(x*y) / 2], para x, y > 0 codificados en unario</p>

<p>7 - x mod y, para x, y > 0, codificados en unario</p>

<p>8 - La parte entera superior del promedio de n números mayores que cero codificados en unario. Usar como separador de números unarios en la cinta de entrada al símbolo 0. Ejemplo: * Cinta de entrada: 111110111010 (números 5, 3 y 1) * Cinta resultado: 111 (cálculo [(5 + 3 + 1) / 3] = 3)</p>

<p>9 - Calcular a^nba^m -> a^(n+m)b</p>

<p>10 - Decidir si m < n, a^nb^m / n, m > 0, escribiendo en la cinta T (true) o F (false)</p>

<p>11 - Que recibe un número binario (cadena no vacía de 0’s y 1’s) y devuelve el siguiente número binario (es decir, le suma 1)</p>


<img src="./archivos/11.png" alt="MT11" width="350">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC11.jff)

<br>

<b>*Ejemplos*</b>

<div>a) 11</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/11aInicio.png" alt="Entrada 11a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/11aResultado.png" alt="Salida 11a" width="350">

<br>

<div>b) 10</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/11bInicio.png" alt="Entrada 4b" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/11bResultado.png" alt="Salida 4b" width="350">

<br>
<br>

<p>12 - Para eliminar el blanco que separa los dos argumentos x e y, moviendo los símbolos de y un lugar hacia la izquierda. Σ = {a, b}</p>

En este ejercicio, al no encontrar la manera de ingresar un ▯ por teclado, se lo sustituyó por un guión bajo (_), y es por eso que en la transición de q0 a q1 figura con ambas formas. La primera vez que se encuentra un _ es sustituido por ▯, no afectando el funcionamiento de lo solicitado.

<img src="./archivos/12.png" alt="MT12" width="650">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC12.jff)

<br>

<b>*Ejemplos*</b>

<div>a) a▯bab</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/12aInicio.png" alt="Entrada 12a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/12aResultado.png" alt="Salida 12a" width="350">

<br>

<div>b)  abb▯a</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/12bInicio.png" alt="Entrada 12b" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/12bResultado.png" alt="Salida 12b" width="350">

<br>
<br>

<p>13 - MT de 3 cintas que reste el número binario de la segunda cinta del número binario de la primera y deje el resultado en la tercer cinta. Hacer otra, suponiendo que la MT es de 2 cintas y que el resultado se deja sobre la segunda. Hacerlo también para que el resultado quede en la primera</p>

<p>14 - MT de 3 cintas que determine si el número binario que está en la primera cinta es menor que el de la segunda. Si es menor, escribir el símbolo S sobre la tercer cinta y si no lo es, escribir los símbolos GE sobre la tercer cinta</p>

<p>15 - Una cinta contiene dos cadenas binarias X e Y separadas por el símbolo * tales que la longitud de cada cadena es la mínima necesaria para representar el número correspondiente (es decir, que ninguno de los números comienzan con cero). En esas condiciones construir una MT que devuelva los valores 0, 1 ó 2 según sea X = Y, X > Y o X < Y respectivamente</p>

<br>

Para este ejercicio, al inicio, se lee todo el contenido ingresado, y se coloca un # al final del mismo. Al llegar a un estado final de la MT, lo siguiente al # indicará:
- con 0, que la cantidad de X es igual a la cantidad de Y
- con 1, que la cantidad de X es > a la cantidad de Y
- con 2, que la cantidad de X es < a la cantidad de Y

<br>

<img src="./archivos/15.png" alt="MT15" width="900">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC15.jff)

<br>

<b>*Ejemplos*</b>

<div>a) XX*YY / Caso X = Y - Resultado 0</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/15aInicio.png" alt="Entrada 15a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/15aResultado.png" alt="Salida 15a" width="350">

<br>

<div>b) XXXX*YY / Caso X > Y - Resultado 1 </div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/15bInicio.png" alt="Entrada 15b" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/15bResultado.png" alt="Salida 15b" width="350">

<br>

<div>c) X*YYY / Caso X < Y - Resultado 2 </div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/15cInicio.png" alt="Entrada 15c" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/15cResultado.png" alt="Salida 15c" width="350">

<br>
<br>

<p>16 - Dados dos números binarios separados por el símbolo *, defina y construya una MT que calcule la suma de ambos números</p>

Para este ejercicio, se usa la estrategia de decrementar el segundo número e incrementar el primero.


<img src="./archivos/16.png" alt="MT16" width="600">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC16.jff)

<br>

<b>*Ejemplos*</b>

<div>a) 01*01</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/16aInicio.png" alt="Entrada 16a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/16aResultado.png" alt="Salida 16b" width="350">

<br>

<div>b) 11*101 </div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/16bInicio.png" alt="Entrada 16b" width="350">

<br>
<p>Contenido final de la cinta</p>
<img src="./archivos/16bResultado.png" alt="Salida 16b" width="350">

<br>
<br>

<p>17 - Dadas dos cadenas de palotes, separadas por el símbolo * defina y construya una MT que decida si la primera cadena es submúltiplo de la segunda, y cuántas veces. Pruebe la solución hallada con las siguientes cadenas:</p>
<p>|||*|||||| (es submúltiplo, dos veces)</p>
<p>||*||||| (no es submúltiplo)</p>

Para este ejercicio, al inicio, se lee todo el contenido ingresado, y se coloca un # al final del mismo. Al llegar a un estado final de la MT, lo siguiente al # indicará:
- con 0, que la primer cadena no es submúltiplo de la segunda.
- con 1, la cantidad de veces que la primer cadena es submúltiplo de la segunda.

<br>
<img src="./archivos/17.png" alt="MT17" width="950">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC17.jff)

<br>

<b>*Ejemplos*</b>

<div>a) | | | * | | - No es submúltiplo </div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/17aInicio.png" alt="Entrada 17a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/17aResultado.png" alt="Salida 17a" width="350">

<br>

<div>b) | | | * | | | | | | - Es submúltiplo, 2 veces </div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/17bInicio.png" alt="Entrada 17b" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/17bResultado.png" alt="Salida 17b" width="350">

<br>

<div>c) | |  * | | | | |  - No es submúltiplo</div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/17cInicio.png" alt="Entrada 17c" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/17cResultado.png" alt="Salida 17c" width="350">

<br>
<br>
<p>18 - f(x, y)

0 si x <= y

x-y si x > y

x e y codificados en unario

x e y se encuentran en C1 separados por un símbolo cero

resultado de f(x, y) se dejará en C4

C2 se colocará c y en C3 y

Ejemplo x = 5 y = 3

C1: ...□111110111□...

C2: ...□11111□□□□□...

C3: ...□111□□□□□□□...

C4: ...□11□□□□□□□□...</p>

<br>
<br>
<img src="./archivos/18.png" alt="MT18" width="950">

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTC18.jff)

<br>

<b>*Ejemplos*</b>

<div>a) 111110111 - Según apunte x=5,y=3 </div>
<br> 
<p>Contenido inicial de la cinta</p>

<img src="./archivos/18aInicio.png" alt="Entrada 18a" width="350">


<p>Contenido final de la cinta</p>
<img src="./archivos/18aResultado.png" alt="Salida 18a" width="350">

<br>
No coincide con el ejemplo.
