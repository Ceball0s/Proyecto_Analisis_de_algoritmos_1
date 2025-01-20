# Proyecto de Análisis de Algoritmos

## Descripción del Proyecto
Este proyecto aborda la resolución de problemas complejos utilizando tres enfoques algorítmicos: **programación voraz**, **backtracking** y **programación dinámica**. Se implementan soluciones para dos problemas principales: la transformación de cadenas y la asignación de acciones en subastas.

---

## Características Principales

### Transformación de Cadenas (Terminal)
- **Fuerza Bruta**: Encuentra la solución óptima explorando todas las posibles transformaciones.
- **Programación Dinámica**: Utiliza una tabla de memoria para almacenar soluciones parciales y evitar cálculos redundantes.
- **Algoritmo Voraz**: Realiza transformaciones basadas en la operación de menor costo en cada paso.

### Asignación de Acciones en Subastas
- **Fuerza Bruta**: Explora todas las combinaciones posibles para encontrar la solución óptima.
- **Programación Dinámica**: Utiliza una matriz para almacenar los costos mínimos de asignación de acciones.
- **Algoritmo Voraz**: Ordena las ofertas por precio y asigna acciones de manera óptima en cada paso.

---

## Interfaz Web
Se ha desarrollado una interfaz web utilizando **Flask** que permite a los usuarios:
- Ingresar datos.
- Seleccionar el método de resolución para los problemas de transformación de cadenas y subastas.
- Visualizar los resultados de manera clara y detallada.

---

## Ejecución del Proyecto

### Iniciar el Servidor
'''bash
python Main.py
'''

### Ejecutar Pruebas de Rendimiento
'''bash
python Main.py --test
'''

---

## Estructura del Proyecto

- **`Main.py`**: Archivo principal que inicia el servidor o ejecuta las pruebas de rendimiento.
- **`interfaz/server.py`**: Implementación del servidor Flask y las rutas para resolver los problemas.
- **`proyecto/Punto1.py`**: Implementación de los algoritmos para la transformación de cadenas.
- **`proyecto/Punto2.py`**: Implementación de los algoritmos para la asignación de acciones en subastas.

---

## Conclusión
Este proyecto demuestra:
- La capacidad para resolver problemas complejos mediante el uso de diferentes técnicas algorítmicas.
- La optimización del rendimiento de soluciones.
- El desarrollo de interfaces de usuario intuitivas para facilitar la interacción con los algoritmos.
