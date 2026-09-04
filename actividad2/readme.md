## Actividad 2

### Máquina de Turing que duplica unos

### JFLAP

![MT duplica unos](./archivos/MTDuplicaUnos.png)

Haz clic aquí para [Descargar el archivo JFLAP](./archivos/MTduplicaUnos.jff)

<br>

### Turing machine simulator

🔗 (http://turingmachinesimulator.com/shared/pqxohhxrtg)

```
//-------CONFIGURATION
name: Duplica unos
init: p
accept: s

//-------DELTA FUNCTION:
p,0
p,0,<

p,1
q,0,>

q,_
p,0,<

q,0
q,0,>

q,1
q,1,>

p,_
r,_,>

r,0
r,1,>

r,_
s,_,-
```




