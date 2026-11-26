## Actividad 7

## Complejidad Computacional

#### Determinar complejidad espacial y temporal

<p>Ejercicio 1) 

$L = \{wcw^{-1} / w \in \Sigma^*\}$

Para la resolución de este ejercicio, vamos a tomar como ejemplo:

*  Alfabeto de entrada: $\Sigma = \{a, b, c\}$, donde $w \in \{a, b\}^*$
* Alfabeto de cinta: $\Gamma = \{a, b, c, X, Y, \square\}$ 
</p>

*JFLAP*

![Ej1](./archivos/MTEj1.png)

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTEj1.jff)

*Turing Machine simulator*
🔗 (http://turingmachinesimulator.com/shared/pppjgtvgmf)


*Cálculo de complejidad espacial*

En base a la resolución del ejercicio y analizando el peor caso, si llamamos $`n`$ a la longitud de la cadena $`w`$, la entrada completa ocupa $`n + 1 + n = 2n + 1`$ celdas. Necesitamos también dos celdas adicionales en blanco ($`\square`$) para detectar ambos extremos, con lo cual el total de celdas visitadas queda como $`2n + 3`$.

Como vamos reemplazando los símbolos por marcas auxiliares sobre la misma cinta, no necesitamos almacenar una copia adicional de la palabra.

Por lo tanto, $`S(n) = 2n + 3 \implies S(n) \in O(n)`$, es decir, la complejidad espacial es **lineal**.


<br>
<br>

<p>Ejercicio 2) f((ab)<sup>n</sup>) = (ab)<sup>n+1</sup></p>