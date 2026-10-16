# Informe Laboratorio: La raíz que se esconde

* Asignatura: Computación Numérica S2 [INF321].
* Integrantes: Cristobal Aguilera.
* Fecha: 9 de septiembre 2026.

## 1.Preguntas del Convergencia

### 1.1.¿Qué método convergió en menos iteraciones en cada función?¿Por qué?

El método que convergió en menos iteraciones fue el Newton-Raphson en sus dos versiones, como se ve a continuación:

- **x³ − x − 2, e^(−x) − x, √x − cos(x):** Newton-Raphson y Newton mejorado (2 iteraciones).
- **cos(x) − x:** Newton y Newton mejorado (3).
- **ln(x) + x − 4:** empate entre secante, Newton y Newton mejorado (3).
- **(x − 2)²:** Newton mejorado, con **1** iteración.

Esto de debe a que Newton-Raphson usa la pendiente exacta de la curva, y debido a eso en una raíz simple el número de digitos correctos se duplicar al aumentar los paso, o en otras palabras tiene convergencia cuadrática.


### 1.2.¿Qué orden de convergencia tiene cada método y cómo se refleja en el gráfico |error| vs iteración?






### 1.3.¿Qué métodos requieren un intervalo con cambio de signo y cuáles no?

Los métodos que requiren un intervalo con cambio de signo son los denominados **métodos cerrado**, los cuáles son:
* Método de bisección.
* Método de falsa posición.

Lo comprueban al inicio y, si no se cumple, no se pueden ejecutar.

Los métodos que **NO** requieren un intervalo con cambio de signo son los denominados **métodos abiertos**, los cuáles son:
* Método punto fijo.
* Método de la secante.
* Método Newton-Raphson y Newton-Raphson mejorado.

Parten de una estimación (o dos) y no necesitan encerrar la raíz, pero estos no garantizan una convergencia. 

### 1.4.En la función que toca el eje x (raíz doble): ¿qué métodos fallan o no aplican y cuál se comporta mejor?

### 1.5.¿Cómo influyen el intervalo inicial y la estimación inicial en las iteraciones y en la convergencia?

### 1.6.¿Qué método recomiendan según el tipo de función (velocidad vs robustez)?

## 2.Conclusión