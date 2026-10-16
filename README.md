# Problema Laboratorio: La raíz que se esconde

## Descripción del problema:
Laboratorio de métodos numéricos que compara seis algoritmos de búsqueda de raíces: bisección, falsa posición, punto fijo, secante, Newton-Raphson y Newton mejorado. Se aplican a seis funciones (polinómica simple, polinómica con raíz doble, logarítmica, exponencial, trigonométrica y mixta) con tolerancia 1e-6. Se mide cuántas iteraciones y cuánto error necesita cada método, y se analiza su orden de convergencia con gráficos de |error| vs iteración.

## Cómo ejecutar:
python src/scripts/main.py
python src/scripts/experimentos.py

## Estructura del proyecto:

```
evaluacion2-busqueda-raices/
├── README.md
├── requirements.txt
├── informe.md                 <- respuestas a las preguntas de convergencia y conclusión
└── src/
    ├── assets/                <- gráficos PNG generados
    ├── data/                  <- CSV generados
    └── scripts/               <- scripts de Python
```