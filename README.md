# TrabajoColaborativo

## Descripción

Este es un programa simple de gestión de ventas desarrollado en Python. Permite agregar, ver, eliminar ventas y calcular el total de las ventas registradas.

El programa utiliza una interfaz de consola para interactuar con el usuario y almacena las ventas en memoria durante la ejecución (no persiste los datos después de cerrar el programa).

## Características

- **Agregar ventas**: Permite ingresar el nombre del producto, cantidad y precio para registrar una nueva venta.
- **Ver ventas**: Muestra una lista tabular de todas las ventas registradas con ID, producto, cantidad y precio.
- **Eliminar ventas**: Elimina una venta específica proporcionando exactamente el producto, cantidad y precio.
- **Calcular total**: Calcula y muestra el total acumulado de todas las ventas (cantidad * precio por cada venta).
- **Menú interactivo**: Interfaz de menú simple para navegar entre las opciones.

## Requisitos

- Python 3.x instalado en el sistema.

## Instalación

1. Clona este repositorio:
   ```
   git clone https://github.com/DmnMarengo/TrabajoColaborativo.git
   ```

2. Navega al directorio del proyecto:
   ```
   cd TrabajoColaborativo
   ```

3. Ejecuta el programa:
   ```
   python Menu_Principal.py
   ```

## Uso

Al ejecutar `Menu_Principal.py`, se mostrará el menú principal con las siguientes opciones:

1. **Agregar ventas**: Ingresa el nombre del producto, cantidad (número entero) y precio (número decimal).
2. **Ver ventas**: Muestra una tabla con todas las ventas registradas.
3. **Eliminar ventas**: Proporciona el producto, cantidad y precio exactos para eliminar la venta correspondiente.
4. **Calcular total de ventas**: Muestra el total acumulado de todas las ventas.
5. **Salir**: Cierra el programa.

## Estructura del proyecto

- `Menu_Principal.py`: Archivo principal que contiene el menú y la lógica de ejecución.
- `agregar_venta.py`: Módulo para agregar nuevas ventas.
- `ver_ventas.py`: Módulo para mostrar las ventas registradas.
- `eliminar_venta.py`: Módulo para eliminar ventas específicas.
- `calcular_total.py`: Módulo para calcular el total de ventas.
- `README.md`: Este archivo de documentación.
